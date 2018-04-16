# VSCode Hotkeys

Here is a list of hotkeys in vscode that you should all know. Some of them are absolutely necessary and you will use them every single day, while others you may only use occasionally.

These take just a few minutes to learn and can save you hours of repetitive typing.

---
### Official Docs

<li>

[Windows Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

</li>

<li>

[Mac Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)

</li>

---
### Content

<li>

[Auto Format](#format)

</li>

<li>

[Open / Close Terminal](#terminal)

</li>

<li>

[Save](#save)

</li>

<li>

[Copy, Cut, Paste](#copy)

</li>

<li>

[Undo](#undo)

</li>

<li>

[Delete Line](#delete)

</li>

<li>

[Move Lines / Copy Up/Down](#move)

</li>

<li>

[Select Multiple](#multiple)

</li>

<li>

[Indent](#indent)

</li>

<li>

[Extend / Decrease Selection](#extend)

</li>

---
## Absolutely Necessary:

These ones are crucial to know and will vastly increase your coding speed.

<a id="format"></a>
### Auto-Format

`ALT + SHIFT + F`

Alt Shift F will auto-format whatever file you are currently in. This is an easy way to keep your code clean and consistent. It is also an easy way to find syntax errors as these will mess up the formatting and make them obvious.

<a id="terminal"></a>
### Open / Close Terminal

`CTRL + ~` - Opens or closes vscode's built-in terminal.

<a id="save"></a>
### Save

`CTRL + S` - Saves your current file.

<a id="copy"></a>
### Copy, Cut, and Paste

`CTRL + C` - Copy - copies your current selection to the clipboard.

`CTRL + X` - Cut - cuts your current selection to the clipboard.

`CTRL + V` - Paste - replaces your current selection with whatever is on the clipboard.

Vscode provides additional copy-paste functionality to make your life easier:

<li>If you haven't selected anything, cut and copy will simply cut or copy your current line - this is super useful for deleting one or a few lines without having to select anything.</li>
<li>After you have cut or copied an entire line, paste will insert that line immediately before the line your cursor is on.</li>

---
## Extremely useful:

<a id="undo"></a>
### Undo

`CTRL + Z` - Undo last action.

<a id="delete"></a>
### Delete Line

`CTRL + SHIFT + K` - Delete current line

<a id="move"></a>
### Move Lines / Copy up/down

Mac:

`OPTION + UP` / `OPTION + DOWN` - Move current line

`OPTION + SHIFT + UP` / `OPTION + SHIFT + DOWN` - Copy current line up/down

Windows:

`ALT + UP` / `ALT + DOWN` - Move current line

`ALT + SHIFT + UP` / `ALT + SHIFT + DOWN` - Copy current line up/down

Alt Up/Down will switch all currently selected lines with the next one up or down.
Alt Shift Up/Down will copy all currently selected lines and insert them on the next line up/down.

<a id="multiple"></a>
### Select Multiple

`CTRL + D` - Select next instance of current selection

`CTRL + Click` - Select

You kinda have to see this one to know how it works, but it'll blow your mind when you do.

If you select a word, then press CTRL D, vscode will select the next instance of that word. If you hold CTRL D, it will select all matches of that word in the current file.

If you just want to select multiple different places, you can hold CTRL and click wherever you would like to place another cursor.

---
## Good To Know:

<a id="indent"></a>
### Indent Selection

`CTRL + ]` - Indent all selected lines

`CTRL + [` - Remove indent from selected lines

If you haven't selected anything, CTRL ]/\[ will indent or remove the indent from the current line.

If there is no indent to remove, CTRL \[ will not do anything.

<a id="extend"></a>
### Extend / Decrease Selection

`SHIFT + LEFT` / `SHIFT + RIGHT` - Extend/decrease selection by one character

`SHIFT + UP` / `SHIFT + DOWN` - Extend/decrease selection by one line

`SHIFT + CLICK` - Extend selection

If you haven't selected anything, start with the cursor at one end of the content you want to select, then either click or use the arrow keys to move to the end of the content you want to select.

---
## Corrections / Recommendations

If you have any recommendations or see any mistakes, just submit them under issues in this repository - or Slack me, email me, or talk to me in person!


