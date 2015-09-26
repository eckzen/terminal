#My terminal commands

To open File manager in kali

    xdg-open

    xdg-open .

####To launch sublime text and open the current directory

na - nautilus

    subl na .
    subl .              - will suffice

xdg - file manager in kali linux

    subl xdg-open .

SWitch between root and user

    su - eckzen

###Deleting Files

    rm <file>
    rm <file> <file> <file> <file>  - to delete multiple files
    rm -i <file>                    - trash can

###Deleting FOLDERS/DIRECTORY

    rm -R <folder>
    rmdir <folder>      - Empty directory



###Moving the cursor:

<kbd>Ctrl</kbd> + <kbd>a</kbd>   Go to the beginning of the line (Home)
<kbd>Ctrl</kbd> + <kbd>e</kbd>   Go to the End of the line (End)
<kbd>Ctrl</kbd> + <kbd>p</kbd>   Previous command (Up arrow)
<kbd>Ctrl</kbd> + <kbd>n</kbd>   Next command (Down arrow)
<kbd>Alt</kbd> + <kbd>b</kbd>   Back (left) one word      or use Option+Right-Arrow
<kbd>Alt</kbd> + <kbd>f</kbd>   Forward (right) one word  or use Option+Left-Arrow
<kbd>Ctrl</kbd> + <kbd>f</kbd>   Forward one character
<kbd>Ctrl</kbd> + <kbd>b</kbd>   Backward one character
<kbd>Ctrl</kbd> + <kbd>xx</kbd>  Toggle between the start of line and current cursor position

###Editing:

<kbd>Ctrl</kbd> + <kbd>L</kbd>   Clear the Screen, similar to the clear command

<kbd>Alt</kbd> + <kbd>Del</kbd> Delete the Word before the cursor.
<kbd>Alt</kbd> + <kbd>d</kbd>   Delete the Word after the cursor.
<kbd>Ctrl</kbd> + <kbd>d</kbd>   Delete character under the cursor
<kbd>Ctrl</kbd> + <kbd>h</kbd>   Delete character before the cursor (backspace)

<kbd>Ctrl</kbd> + <kbd>w</kbd>   Cut the Word before the cursor to the clipboard.
<kbd>Ctrl</kbd> + <kbd>k</kbd>   Cut the Line after the cursor to the clipboard.
 <kbd>Ctrl</kbd> + <kbd>u</kbd>   Cut/delete the Line before the cursor position.

<kbd>Alt</kbd> + <kbd>t</kbd>   Swap current word with previous
<kbd>Ctrl</kbd> + <kbd>t</kbd>   Swap the last two characters before the cursor (typo).
<kbd>Esc</kbd>  + <kbd>t</kbd>   Swap the last two words before the cursor.

<kbd>ctrl</kbd> + <kbd>y</kbd>   Paste the last thing to be cut (yank)
<kbd>Alt</kbd> + <kbd>u</kbd>   UPPER capitalize every character from the cursor to the end of the current word.
<kbd>Alt</kbd> + <kbd>l</kbd>   Lower the case of every character from the cursor to the end of the current word.
<kbd>Alt</kbd> + <kbd>c</kbd>   Capitalize the character under the cursor and move to the end of the word.
<kbd>Alt</kbd> + <kbd>r</kbd>   Cancel the changes and put back the line as it was in the history (revert).
<kbd>ctrl</kbd> + <kbd>_</kbd>   Undo

<kbd>TAB</kbd>       Tab completion for file/directory names