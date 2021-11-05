# COMP 3021 Programming Assignment 2
## Demonstration Rubrics

> **Update:**
> - For the icon used in the `Alert`, message dialog means there is an information icon in the dialog.
> - For the dialog to show then losing the game, either error or information are fine since the example in readme shows an information icon. 

### Main menu (12pt)
 - The main menu should display correctly (6pt)
 - The layout should look similar to that in readme (Window size adjustment is allowed) (6pt)
### Load file (16pt)
 - The open file chooser is shown (2pt)
 - The title of the file chooser should be the provided string in the skeleton code (2pt)
 - The default directory of the file chooser should be the current working directory (2pt)
 - When loading an invalid file, an error dialog should be shown (4pt)
   - The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - When the user cancel selecting a file, a warning dialog should be shown (2pt)
   - The title and the content of the dialog should be the provided strings in the skeleton code (4pt)
 - When the user selected a valid file, the main game panel should be shown (2pt)
### Main game panel (12pt)
 - It should load successfully (6pt)
 - The layout should look similar to that in readme (Window size adjustment is allowed) (6pt)
### Gameboard rendering (12pt)
 - The cells in the game board should display correctly
### Game move (12pt)
 - Clicking on the arrows buttons should make move to the player in the game pane (3pt for each direction)
### Undo (12pt)
 - Clicking on the undo button should undo the last move (6pt)
 - Nothing should happen if there is nothing to undo (6pt)
### Game statistics display (6pt)
 - Game statistics should update correctly on each move
### Game Result (18pt)
 - When the player wins the game, a massage dialog should be shown (6pt)
   - The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - When the player loses the game, an error (or message) dialog should be shown (6pt)
   - The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - After the above-mentioned dialog is closed, the main menu should be shown (6pt)

> Note: Full mark will be given if the feature works correctly without exception.
> Half of the marks will be deducted if the feature works correctly but there are unhandled exceptions.
> Zero will be given if the feature does not work correctly.
