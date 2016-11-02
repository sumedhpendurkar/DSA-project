TITLE : new feature to gnu-nano : complete a fragment to a longer word found in the buffer
NAME: PENDURKAR SUMEDH DATTAGURU
MIS ID: 111503051

Details of work :
1) Added a completion shortcut that is bound to "^]"
2) It searches for the the current word (definition of a word can be modified in nanorc, once installed) in the entire current file and cycles through the list of words. This is very similar to that of (M-/) of Emacs.
3) Displays appropriate message at statusbar. Also works well with undo.
4) Supports ASCII as well as UTF8 character encoding.

the link to my commit on gnu-nano(not on master branch yet)
http://git.savannah.gnu.org/cgit/nano.git/commit/?h=word-completion&id=ab228e06e3f0985c02d6cd4f842854372eaad834
