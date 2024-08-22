Welcome to the world of MicroEMACS
---

This is a collection of MicroEMACS source code repositories.
My goal is to keep track of the numerous variants of MicroEMACS that have been developed over the years.

I am Charlie Gordon ([chqrlie](https://github.com/chqrlie), co-author with [Fabrice Bellard](https://bellard.org/)
([bellard](https://github.com/bellard)) of our own emacs clone: [QuickEmacs](https://github.com/qemacs).
This one has no common code with MicroEmacs, but the same goal: provide a functional alternative for 
developers who cannot or do not want to install GNU Emacs but still want to take advantage of an efficient
environment with familiar commands and key bindings.

Here you can find numerous versions of MicroEmacs and mg.  Each repository is either a fork of an existing version
maintained by someone else or an import of sources found on the Internet and no longer maintained.

For each repository, I create multiple branches:
- the **master** branch tracks the original archive or repository (the upstream)
- the **port** branch only has minimal modifications to allow compilation on modern operating systems.
- the **bugfixes** branch contains bug fixes that ought to be merged in the upstream, when possible.
- the **wip** branch contains modifications ported from my own work or other sources to make this version
  more usable while keeping the same philosophy.

Here is a description of some of the repositories:

- [hboetes-mg](https://github.com/uEmacs/hboetes-mg), a fork of [github.com/hboetes/mg](https://github.com/hboetes/mg)
  a version maintained by [Han Boetes](https://github.com/hboetes/):
  Portable version of the OpenBSD maintained mg, micro emacs clone.
- [ibara-mg](https://github.com/uEmacs/ibara-mg), a fork of [github.com/ibara/mg](https://github.com/ibara/mg)
  a version by [Brian Callahan](https://github.com/ibara/):
  OpenBSD Mg editor. Portable Public Domain Micro Emacs for *BSD, Cygwin, Linux, Mac OS X.
- [troglobit-mg](https://github.com/uEmacs/troglobit-mg), a fork of [github.com/troglobit/mg](https://github.com/troglobit/mg)
  a version by [Joachim Wiberg](https://github.com/troglobit/):
  Micro (GNU) Emacs-like text editor ❤️ public-domain
- [troglobit-uemacs](https://github.com/uEmacs/troglobit-uemacs), a fork of [github.com/troglobit/uemacs](https://github.com/troglobit/uemacs)
  a repository maintained by [Joachim Wiberg](https://github.com/troglobit/) to host
  the original MicroEMACS version by Dave G. Conroy <!--https://www.tiredofit.ca/-->.

Here is a list of other resources for emacs enthousiasts:

- Lars Brinkhoff's [Historical Emacs Software Preservation](https://github.com/larsbrinkhoff/emacs-history/)
- The wikipedia article on [MicroEMACS](https://en.wikipedia.org/wiki/MicroEMACS)
- The homepage for [JASSPA MicroEmacs](http://www.jasspa.com/)
- The homepage for [Daniel Michael Lawrence](https://www.aquest.com/author.htm)'s [MicroEMACS 5.00](https://www.aquest.com/emacs.htm). Dan passed away on June 7th, 2010.

Feel free to file an [issue](https://github.com/uEmacs/uEmacs/issues)
or start a [discussion](https://github.com/uEmacs/uEmacs/discussions) if you have questions or suggestions.

chqrlie
