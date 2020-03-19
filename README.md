# NX-Game-Directory-Trees
Directory trees for various Nintendo games

This is a collection of directory heirachy trees for Nintendo Switch games.
This repo has never, does not, and will not ever host any copyrighted files or software.
This is intended as a resource for ROM Hackers and dataminers who wish to see a vanilla game NCA heirachy.

To generate a directory tree of an extracted game on Windows, enter the following command in a CMD window while in the working directory of the Section 1 partition of the NCA.

`tree /a /f > output.txt`

Pull requests are happily accepted.

#Notes:
Patch trees are *just* the changes--not the full romFS with the base game. This is achieved with hactool's `--basefake` flag.
