  C-M-f     Move forward over a balanced expression
  C-M-b     Move backward over a balanced expression
  C-M-k     Kill balanced expression forward
  C-M-SPC   put the mark at the end of the sexp.
  C-M-n  Move forward over a parenthetical group 
  C-M-p  Move backward over a parenthetical group 
  ;; C-M key binding can also be done by --> ESC Control-key

  ;;And put this to .emacs, it will highlight opening/closing parens:
  (show-paren-mode 1)
