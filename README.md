# Overview

This is a collection of weird filename edge cases. Its intended use is as a testcase for other programs that deal with the filesystem.

## List of wtfiles

* File whose name is just a space (Github doesn't render it)
  * ` `
* Directory whose name is just two spaces (Github doesn't render it)
  * `  `
* Symlink to file whose name is just three spaces (Github doesn't render it)
  * `   ` -> ` `
* Symlink to directory whose name is just four spaces (Github doesn't render it)
  * `    ` -> `  `
* Symlink to directory
  * `dir-symlink` -> `somedir`
* Symlink to non-existent file
  * `broken symlink` -> `__BROKEN__`
* Files containing spaces
  * `file with spaces.txt`
  * `file with spaces and no extension`
* File with symbols
  * `` file with symbols {}!\@\#$%^&*()_+~`'";:<>.,?[]|\\ ``
* File whose name contains new lines `\n`
  * `file with\nnew lines\n`
* File whose name contains tabs `\t`
  * `file with\ttabs\t`
* File whose name is <dot><space>"
  * `. `
* File whose name is <dot><dot><dot>"
  * `...`
* File starting with spaces
  * `   file starting with spaces`
* Files with long filenames
  * 32, 64, 128, and 256 character files
* Directories with long names
  * 32, 64, 128, and 256 character directories
* Unicode files
  * `ελληνικά`
* Unicode with spaces
  * `ελληνικά με κενά`
* Pile of poo file
  * `💩`
* Hidden files
  * `.hidden.`
* File with all ASCII codes from 1 to 127
  * `ASCII-LOVE-1-127...`
* File with all ASCII codes from 128 to 255
  * `ASCII-LOVE-128-255...`
* Non UTF-8 ISO umlaut file
  * `test-umläut-file.txt`

## Contributing

Do you know an edge case that's not included in this collection? Please send a pull request.
