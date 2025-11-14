1. >G
increase the indent level to the end of file.
2.  $
move to the end of the current line.
3. A = $a
append text at the end of the current line.
4. C = c$
change text from the cursor position to the end of the line.
5. S = cc
substitute (change) the entire line.
6. f{char} find the next occurrence of {char} in the current line.
    ; find the next occurrence of {char} in the current line.
    , find the previous occurrence of {char} in the current line.
7. F{char} find the previous occurrence of {char} in the current line.
    ; find the previous occurrence of {char} in the current line.
    , find the next occurrence of {char} in the current line.
8. cw
change word from the cursor position to the end of the word.
9. daw
delete the word
10. cW
change (replace) the entire WORD (a WORD is a sequence of non-blank characters separated by white space)
11. <c-a>
increment the number under the cursor or the number after the cursor.
12. <c-x>
decrement the number under the cursor or the number after the cursor.
13. quickfix
    :copen open the quickfix window.
    :cclose close the quickfix window.
    :cnext go to the next error in the quickfix list.
    :cprev go to the previous error in the quickfix list.
    :clist list all errors in the quickfix list.

