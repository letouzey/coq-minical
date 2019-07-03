
Coq-MiniCalc : a little demo of Lexing/Parsing in Coq
=====================================================

Pierre Letouzey, 2019

Licence : CC0

This is a toy demo of the recent Coq backend of `menhir`.

This micro-grammar recognizes arithmetic expressions : numbers, idents, `+` `*` `-` `/` and parenthesis.
We provide an hand-written lexer, and a minimal final test (compilation should display "OK").

Tested with Coq 8.8 + menhir 2019/06/13 + corresponding coq-menhirlib.
Anything more recent than that should be ok.