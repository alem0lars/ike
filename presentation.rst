:title: Introduction to Kernel Exploitation
:author: Alessandro Molari <molari.alessandro@gmail.com>

:data-transition-duration: 1000
:skip-help: true

----

Introduction to Kernel Exploitation
===================================

----

User-space vs Kernel-space
==========================

----

Why Kernel-space?
=================

* User-space has become harder to exploit:
  * Canaries + ASLR + W^X + Fortify + RELRO + BIND_NOW + BPF_SECCOMP + ...
  * User-space uses kernel-space / user-space privileges to enforce security
  * Many protections are provided by the Kernel
* Kernel is privileged -> More reward :)

----

:data-y: r800
:data-scale: 0.1

...and zoom!
============

.. note::

    Zooming is cool. But one day it will grow old as well. What will we do
    then to make presentations interesting?

----

:data-x: r800
:data-scale: 1

But Prezi is a GUI
==================

So we are back to square one.

(And it is closed source to boot)

.. note::

    It's probably back to making bad jokes again.

----

What about impress.js?
======================

It's open source!

Supports pan, tilt and zoom!


.. _`alem0lars/ike`: https://github.com/alem0lars/ike
.. _hovercraft: https://github.com/regebro/hovercraft
