This project contains the template for a dynamically-updated "choice" dialog in Godot.

To use the dialog, set its "choices" array variable to a new array of strings.  eg.

choiceDialog.choices = ["Go left", "Go right"]

Then, connect your game logic to the dialog's SELECTED signal.

The signal handler takes a single integer as its parameter, which is the index of the choice that was selected by the user.

For example, if the user clicked on the first choice in the list, the index would be 0.
If they clicked on the second choice, the index would be 1.  And so on.
