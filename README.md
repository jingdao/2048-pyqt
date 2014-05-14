2048-pyqt
=========

clone of 2048 game on PyQt

Required packages
-----------------

- python
- python-pyqt4

Usage
-----

from command line:

	python 2048-pyqt.py

embed in another PyQt program

	from 2048-pyqt import Game2048
	g = Game2048(parent,width,gridSize)
	#call these functions to change settings on the fly!
	g.move(x,y)
	g.resize(width,height)
	g.changeGridSize(5)
	g.show()

Features
--------

- supports arbitrary size and number of tiles
- supports both keyboard inputs and swipe gestures

Screenshot
----------

![Screenshot](screenshot.png?raw=true)

References
----------

- https://github.com/gabrielecirulli/2048
- https://github.com/bulenkov/2048

