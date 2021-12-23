Dictionary tools
================

This contains two executable scripts, dict and spell.

Dict performs a dictionary lookup (gives definition of word).

Spell checks the spelling of a word, and gives correction suggestions if incorrect.

Installation is super easy:


DICT:
Copy the dict executable into your $PATH.
Copy the dict.txt dictionary into the same folder as the executable. Or, put
  it somewhere else and change the path at the top of the executable.


SPELL:
Copy the executable into your $PATH.
You will need to install the aspell program as well as an aspell dictionary for your language.
On Arch Linux, the packages are 'aspell' and 'aspell-en' for the English dictionary.

You can also use hunspell instead of aspell, but I find that aspell gives better results.
To use hunspell, on line 19 of the script change aspell to hunspell.
On Arch the packages are 'hunspell' and 'hunspell-en_US'.





The dict.txt file is Webster's Unabridged Dictionary, digitized by Project
  Gutenberg: https://www.gutenberg.org/ebooks/29765
The code (dict and spell scripts) are licensed under the GNU Affero General
  Public License (AGPL) version 3.
