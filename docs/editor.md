# Editor

The editor is where you edit the content of a file. A file consists of study
blocks called **cells**, and each cell can be related to zero or more
repetitions that you actively review based on a specified interval, 
the number of repetitions are determined by the type of cell. 

## Cell types

Here are the types of cells that are currently supported:

- **Flash Card**: This is like the traditional flash cards you're familiar 
with, such as those from Anki, where you have a question and an answer.
- **Cloze**: In cloze cards, all text is shown during review except for
specific parts that you specify. For cloze cells you can have one or more groups,
where each group gets its own repetition.
- **True/False**: This type presents a question that has a true or false answer.
- **Note**: These cells help organize the file but do not appear during review.

## Focus tools

In the editor, you can select one cell at a time, marked by the border color. 
When you select a cell, a set of buttons called focus tools will appear. 
These include:

- **Insert Cell Button**: This allows you to insert a new cell after 
the current one.
- **Reset All Repetitions Button**: This resets all repetitions related 
to the cell.
- **Repetitions Info**: Clicking this shows information about the repetitions 
of the cell.
- **Delete Cell Button**: This shows a confirmation dialog, and upon 
confirmation, the cell and all its repetitions will be deleted.
- **Drag Button**: This allows you to drag and rearrange cells as desired.

## Text editors

Cells can contain text editors that provide an enriched text editing experience,
including the ability to format text, insert images, and more. In any of these
text editors, when you select a portion of the text, a bubble menu will appear, 
allowing you to apply various formatting options. Cloze cells also have 
additional buttons on this bubble menu:

1. A button to add or remove the selected text into a cloze group.
1. Two buttons to increase or decrease the cloze group number.

## Shortcuts

A set of shortcuts has been added to the editor to make your editing experience
faster and more efficient:

| Keyboard shortcut        | What it does                                    |
|--------------------------|-------------------------------------------------|
| Ctrl + Enter             | Insert new cell at the end of the file          |
| Ctrl + Shift + Enter     | Insert new cell after the current selected cell |
| Ctrl + Arrow up/down     | Move the focus to the previous/next cell        |
| Ctrl Alt + Arrow up/down | Move the selected cell to the up/down           |
| Ctrl + F                 | Search                                          |
| Alt + DEL                | Delete current cell                             |
| Ctrl + Space             | Move the focus to the text editor               |
| F5                       | Start studying/review session                   |
