==========
simpleMath
==========

About
=====

simpleMath is a LaTeX package that provides convenient math
functions for Physicists. Eg., ``\ket{a}`` gives ``|a>`` with nicely
sized bra-kets.

Usage
=====

Just include ``\usepackage{simpleMath}`` in your document's head.

Options
=======

The package knows switch-like options:

- Euler: use Euler font for i and e (provided by the commands ``\ii``
  and ``\ee``). By default, Roman font is used.

- oldVec: do not change standard LaTeX ``\vec`` definition. By default, bold
  italic letters are used for vectors.

- round: use round brackets in vector and matrix convenience commands such as
  ``\DreierVec``. By default, square brackets are used in vector and matrix
  convenience commands such as ``\twoMatrix``.

Commands
========

At the time being, there is no typeset list of commands. Have a look
at the source code itself.
