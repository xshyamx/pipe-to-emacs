# Emacs Pipe #

Solves the problem of sending text from stdin to emacs. emacsclient
can handle files but, not stdin. The common solution is to redirect to a temporary file and open it via emacsclient (See [Piping things into Emacs][emacs-wiki]). Alternatively, we can leverage the eval argument of emacsclient to create a buffer in emacs without creating a temporary file (See [Reading stdin with Emacs Client][emacs-stdin])

[emacs-wiki]: https://www.emacswiki.org/emacs/EmacsPipe
[emacs-stdin]: https://mina86.com/2021/emacs-stdin/
