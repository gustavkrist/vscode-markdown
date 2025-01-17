## R Markdown math highlighting and completion

Fork of Markdown All In One, but enables the extension to work
in R Markdown files. 
Provides syntax highlighting and code completion in inline and display
math blocks.
Inline math is contained within two `$`, math blocks
are between two pairs of `$$`.
There must be a character immediately after the starting `$` in inline math for
syntax highlighting to work.

Example:

![Example](assets/installation_2022-04-26-22-24-25.png)

Math mode can be toggled with `cmd + m` on mac and 
`ctrl + m` on Windows.

## Installation

[Download the extension file](https://github.com/gustavkrist/vscode-markdown/raw/master/r-markdown-all-in-one-3.5.0.vsix)

Requires the vscode R extension

![Vscode R Extension](assets/installation_2022-04-26-22-19-14.png)

Disable Markdown All In One if you already have it installed

![Markdown All In One](assets/installation_2022-04-26-22-19-56.png)

Then install the downloaded .vsix extension file.

![Install from VSIX](assets/installation_2022-04-26-22-20-41.png)

Click extensions in the sidebar, then the three dots in the upper right
corner of the menu, then install from VSIX and locate the downloaded file.

Or you can open the command pallet and type vsix, and there should be a command to
install from VSIX.

## Notes

The completion seems to break when R Markdown All In One is enabled

![R Markdown All In One](assets/installation_2022-04-26-22-37-28.png)
