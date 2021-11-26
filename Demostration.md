# COMP 3021 Programming Assignment 2
## Demonstration Rubrics

> **Update:**
> - For the icon used in the `Alert`, message dialog means there is an information icon in the dialog.
> - For the dialog to show that losing the game, either error or information are fine since the example in readme shows an information icon. 

### 1. Main menu (12pt)
 - [1.1] The main menu should display correctly (6pt)
 - [1.2] The layout should look similar to that in readme (Window size adjustment is allowed) (6pt)
### 2. Load file (16pt)
 - [2.1] The open file chooser is shown (2pt)
 - [2.2] The title of the file chooser should be the provided string in the skeleton code (2pt)
 - [2.3] The default directory of the file chooser should be the current working directory (2pt)
 - [2.4] When loading an invalid file, an error dialog should be shown (4pt)
   - [2.4.1] The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - [2.5] When the user cancel selecting a file, a warning dialog should be shown (4pt)
   - [2.5.1] The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - [2.6] When the user selected a valid file, the main game panel should be shown (2pt)
### 3. Main game panel (12pt)
 - [3.1] It should load successfully (6pt)
 - [3.2] The layout should look similar to that in readme (Window size adjustment is allowed) (6pt)
### 4. Gameboard rendering (12pt)
 - [4.1] The cells in the game board should display correctly
### 5. Game move (12pt)
 - [5.1] Clicking on the arrows buttons should make move to the player in the game pane (3pt for each direction)
### 6. Undo (12pt)
 - [6.1] Clicking on the undo button should undo the last move (6pt)
 - [6.2] Nothing should happen if there is nothing to undo (6pt)
### 7. Game statistics display (6pt)
 - [7.1] Game statistics should update correctly on each move
### 8. Game Result (18pt)
 - [8.1] When the player wins the game, a message dialog should be shown (6pt)
   - [8.1.1] The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - [8.2] When the player loses the game, an error (or message) dialog should be shown (6pt)
   - [8.2.1] The title and the content of the dialog should be the provided strings in the skeleton code (2pt)
 - [8.3] After the above-mentioned dialog is closed, the main menu should be shown (6pt)

> Note: Full mark will be given if the feature works correctly without exception.
> Half of the marks will be deducted if the feature works correctly but there are unhandled exceptions.
> Zero will be given if the feature does not work correctly.
