===========================================================
Hacking Device Drivers - How to get into kernel development
===========================================================

Workshop - Open Source Summit North America 2019

Presented by: Tobin C. Harding <me@tobin.cc>

Welcome to the workshop, thank you for giving up your time to come here.  For
the workshop we will be hacking on staging drivers within the kernel tree.

The hoped outcome of the workshop is to get everyone to submit a three patch
series to LKML.  Like all good projects the workshop should be challenging but
achievable.  In order to achieve this there are multiple projects.  Please pick
the one that looks the most enjoyable to you.  Please consider working in a
group of two or three, pair programming is fun and you will almost certainly
learn something from each other.

All projects require the same set up to get started, please see setup_.

Once you have a kernel built (or building) please select from one of the
following (listed in order of complexity).

The aim of this workshop is to fill the current knowledge gap I ran into between
creating your first kernel patch and being a 'real' kernel developer.  For me at
least, the next step after my first patch was to *really* learn the kernel
development process.  With this experience I feel that patching
``drivers/staging`` a **lot** is a good method for learning this process and
getting comfortable patching the kernel.  As such, I would expect most people to
work on project one.  The others were really added just in case project one
was too easy.

1. Checkpatch your way to glory: checkpatch_

2. Probe and release: probe-and-release_

3. Sparse, spatch, and Coccinelle: further-tools_

   
Other material
--------------

This workshop is a re-write of the tutorial I gave in LA for OSS in 2017.  Some
of the material from that may bu useful, specifically

- tutorial/cheat-sheet_
- tutorial/trouble-shoot_

.. _cheat-sheet: ../tutorial/cheat-sheet.rst
.. _trouble-shoot: ../tutorial/trouble-shoot.rst


Thanks,
Tobin.

.. _setup: ./setup.rst
.. _checkpatch: ./checkpatch.rst
.. _probe-and-release: ./probe-and-release.rst
.. _further-tools: ./further-tools.rst
