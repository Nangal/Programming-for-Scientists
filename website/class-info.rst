=================
Class Overview
=================

**Instructor**: Luis Pedro Coelho <lpc@cmu.edu>

**Class Number**: 98-111

**Meeting Times**: 6.30PM SH 220

The class is broken up into three modules: *Programming and Software Carpentry*, *Scientific Programming* and *Applied Topics*. The class is also broken into two sections: a lecture and a lab session. During lecture, we will cover general interest material. Lab session will also have a lecture format. However, it will cover specific technologies and methods.


Textbooks
+++++++++

There is no official textbook for the course, but *Python Programming: An Introduction to Computer Science* by John Zelle is a good Python introduction. Also, you can check out *Dive Into Python*, which is available for free online_ or (in printed form) in the CMU library. Another quality online resource is `A Byte of Python`_.

.. _online: http://www.diveintopython.org/
.. _A Byte of Python: http://www.swaroopch.com/notes/Python

Homeworks
+++++++++

Grades will depend on homeworks and final project. For a passing grade, you need 7 (out of 10) on at least 7 homeworks (there will be at least 9 homeworks) and a 7 on the final project. Homeworks will be assigned on Tuesdays and are due the next Tuesday at mid-night. *Late penalties*: up to 24 hours delay: 20% penalty. Up until beginning of lab-session: 30% penalty. Thursday sessions will often include discussion of homeworks. Therefore, after that, you can no longer turn in homeworks for grading.

Homework will normally consists of a multiple-choice/short answer section plus a programming question. Homeworks are to be turned in by email, with the answers either typed-in directly in the body of the email (text-only emails, please), or as a text (.txt) or PDF format for the question and as an attached .py file for the programming assignments. In particular, *doc, docx, odt* will not be accepted.

Expectations
++++++++++++

This is what I expect that students will have learned by the end of the course:

    (i) Software carpentry: source control, unit testing, profilers. Students should know how to use Subversion, nosetest, and the Python profiler as well as understand the concepts behind these tools (which will enable them to use a different implementation of the same ideas).

    (ii) Modern programming paradigms: object oriented. Students should know how polymorphism works and understand when and why it can be useful.

    (iii) Students should know how floating-point numbers are represented and their limitations. Detailed knowledge of specific formats is not required.
   
    (iv) Technologies: Python, including numpy. Students should be able to comfortably write medium-sized programs (a few thousand lines of code) using these technologies in an effective way.

Most importantly, I expect students to be (and consider themselves) more efficient programmers. The overall goal is a twenty per-cent improvement in productivity.

Outline
+++++++

This outline is my current thinking on the course. The general topics are very much fixed upon (except for the last module, which is flexible by-design), but the content of each lecture might still be tweaked.

Programming and Software Carpentry
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Lecture 1.1: Introduction
-------------------------

Overview of the course, course policies. Principles of readable code.

Extra Lectures E1 & Lab Session EL1: Introduction to Programming
-----------------------------------------------------------------

This is only for people who don't know programming and will teach you the basics.

Lab Session 1: Introduction to Python
-------------------------------------

What is Python? Basic types and iterations.

Lecture 1.2: Object Oriented Programming
----------------------------------------

Introduction to object-oriented code.

Lab Session 2: Python Odds & Ends
-----------------------------------

More Python. 

Lecture 1.3: Error-handling
---------------------------------

Exception-handling. Defensive programming (assert statement)

Lab Session 3: Python wrap-up
------------------------------

Odds & ends of python 2. In-class exercises on Python.

Lecture 1.4: Software Carpentry
-------------------------------

Using the shell.

Lab Session 4: Software Carpentry II
------------------------------------

Version control: Subversion.

Lecture 1.5: Software Carpentry III
------------------------------------

Defensive Programming & Unit testing (nosetest).

Lab Session 5: Software Carpentry IV
---------------------------------------

Debugger & Profiler.

Scientific Programming
~~~~~~~~~~~~~~~~~~~~~~

We focus on both basic issues of scientific computing (floating point representation) and an overview of basic algorithms for scientific tasks (in particular, numerical optimisation).

Lecture 2.1: Number Representation
-----------------------------------

Binary representation. How integers are represented in memory (positive and negative numbers), integer sizes. Discussion of fixed-point vs. floating point. How floating point numbers are represented internally. Ieee numbers, nan's, Infs.

Lab Session 5: Introduction to numpy
------------------------------------

Using arrays to write code, reductions and broadcasting.

Lecture 2.3: Optimisation as a programming tool
-----------------------------------------------

*Feb 24*.

Reformulating your problems as an optimisation problem. Limitations of this approach.  Newton's method. Gradient descent.

Lab Session 6: Introduction to other scipy Tools
------------------------------------------------

*Feb 26*

Thinking about memory allocation and temporaries. Projects

Lecture 2.5: Random processes
-----------------------------

*Mar 3*

Pseudo-random numbers. Issues with stochasticity. Metropolis-Hastings Algorithm

Lab Session 7: OpenOpt/Scipy
-----------------------------

*Mar 5*

Introduction to OpenOpt. Discussion of possible projects.

Homework: Students should submit a project proposal (or choose from the instructor proposed projects).

Lecture 2.5: File parsing and regular expressions
-------------------------------------------------

*Mar 17*

Discussion of file formats, encodings. Basic syntax of regular expressions.

Lab Session 8: Implementation of a Simple Program
------------------------------------------------------

*Mar 19*


Lecture 2.6: Open Source. Packaging your code for others
--------------------------------------------------------

*Mar 24*

Publishing code is often part of the publication process with benefits for both the community and the author. In this lecture, we focus on the aspects inherent to a good, re-usable, software package. We also go over open-source licenses. Re-produceable research.


Lab Session 9: setup.py
------------------------

*Mar 26*

Discussion of open source distribution licenses and models.

Lab Session 10: TBA
------------------------------------

*Mar 31*


Applied Topics
~~~~~~~~~~~~~~

This final section consists of more advanced topics. No homeworks will be assigned as students should be working on their projects. The topics covered in this module is open to change based on student interests.

Lecture 3.1: Graphical User Interfaces
--------------------------------------

Simple design principles behind an effective graphical user interface.

Lab Session 13: PyQT
--------------------

Tools for building a user interface: pyqt.

Lecture 3.2: Databases
----------------------

Organising large quantities of data using a relational database.

Lab Session 14: Databases
-------------------------

How to build a database.

Lecture 3.3: Django
--------------------

Buffer time for overflow from other lectures.

Lab Session 15: Multi-Language Programming
------------------------------------------

Tools for interface Python/C/C++/Fortran/R/...

