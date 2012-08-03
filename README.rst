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

The package knows options:

- Euler: use Euler font for i and e (provided by the commands ``\ii``
  and ``\ee``)

- noEuler (default): use roman e, i.

- newVec (default): use bold italic letters for vectors.

- oldVec: do not change standard LaTeX ``\vec`` definition.

- square: use square brackets in vector and matrix convenience commands such
  as ``\twoMatrix``.

- round: use round brackets in vector and matrix convenience commands such as
  ``\DreierVec``.

Commands
========

At the time being, there is no typeset list of commands. Have a look
at the source code itself.
