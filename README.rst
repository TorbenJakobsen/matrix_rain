######################
  Matrix Digital Rain
######################

From Wikipedia:

    Matrix digital rain, or Matrix code, is the computer code featured in the Ghost in the Shell series and the Matrix series. The falling green code is a way of representing the activity of the simulated reality environment of the Matrix on screen by kinetic typography.

The classic green body with a white haed.

.. image:: ./media/matrix_run_green.png

| The script has options to control the color of head, body, and background.
| Here it is blue body and red head.

.. image:: ./media/matrix_run_blue.png

========
  TODO
========

* Code breaks after resize when folowing writing to lower right corner.  
* What to do with Windows
* Version due to type hints

* Colors are numbered, and start_color() initializes 8 basic colors when it activates color mode.
* Color pair 0 is hard-wired to white on black, and cannot be changed.
* Coordinates are always passed in the order y,x, and the top-left corner of a window is coordinate (0,0)
* Writing lower right corner...
* https://docs.python.org/3/howto/curses.html

