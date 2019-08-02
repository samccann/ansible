
:orphan:

Markup Test
===========

This page shows the results of semantic markup options in Sphinx/rst.

RST Markup
----------

:literal:
    Example: :literal:`this is a literal block of text`.

:code:
    Example: :code:`ansible-playbook -i inventory myplay.yml`.



Sphinx
-------

:abbr:

    An abbreviation. If the role content contains a parenthesized explanation, it will be treated specially: it will be shown in a tool-tip in HTML, and output only once in LaTeX.

    Example: :abbr:`LIFO (last-in, first-out)`.


:command:

    The name of an OS-level command, such as rm.

    Example: :command:`rm`.

:dfn:

    Mark the defining instance of a term in the text. (No index entries are generated.)

    Example: A :dfn:`collection` is a new distribution format in Ansible.

:file:

    The name of a file or directory. Within the contents, you can use curly braces to indicate a “variable” part.

    Example:  ... is installed in :file:`/usr/lib/python2.{x}/site-packages` ...

    In the built documentation, the x will be displayed differently to indicate that it is to be replaced by the Python minor version.

:guilabel:

    Labels used in the GUI should be marked with this role, including button labels, window titles, field names, menu and menu selection names, and even values in selection lists.

    Example: :guilabel:`Cancel`.


:kbd:

    Mark a sequence of keystrokes.

    Example: :kbd:`Control-x Control-f`.


:makevar:

    The name of a make variable.

    Example: :makevar:`make variable`.

:manpage:

    A reference to a Unix manual page including the selection

     Example: :manpage:`ls(1)`.


:menuselection:

    GUI Menu selections should be marked using the menuselection role.

    :menuselection:`Start > Programs`


:program:

    The name of an executable program.

    Example: :program:`eat-at-joes`.

:regexp:

    A regular expression. Quotes should not be included.

    Example: :regexp:`rege(x(es)?|xps?)`.

:samp:

    A piece of literal text, such as code. Within the contents, you can use curly braces to indicate a “variable” part, as in file.

    Example, in :samp:`print 1+{variable}`, the part variable would be emphasized.

    If you don’t need the “variable part” indication, use the standard ``code`` instead.
