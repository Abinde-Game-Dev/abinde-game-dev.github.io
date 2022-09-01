layout: page
title: "Abinde Documentation Page"
permalink: /docs/

## Before You Continue

Please note this project is still under __heavy development__, which means it will probably change __a lot__. However, all of the versions will be available to install on [__PyPI__](https://pypi.org/project/Abinde).

This project is stable on Debian Linux, Raspberry Pi, and Mac.

Want to be a tester? take a look at [__this__](https://github.com/desvasicek/Abinde/discussions/6)!

## About

Abinde is an open-source wrapper around pygame.

## Install

To install Abinde, you can open your shell and run:

```sh
pip install Abinde
```

### or

```sh
pip3 install Abinde
```

Make sure you have python and pip installed!

## Import

To import Abinde, open your IDE for python and add:

```python
import Abinde as ab
```

## Making a Game

To make the game object, you can add:

```python
game_name = ab.Game(str(title), list(size), color(color), str(warn), str(log))

game_name.mainloop()
```

Run `help(ab.Game)` for more technical information.

## Sprites

### Rectangle

To create a simple rectange/square, you can add:

```python
rectangle_name = ab.sprite.Rectangle(list(position), list(size), color(color), str(title))
```

Run `help(ab.sprite.Rectangle)` for more technical information.

### Line

To create a line, you can add:

```python
line_name = ab.sprite.Line(list(pos), list(size), color(color), str(title))
```

Run `help(ab.sprite.Line)` for more technical information.

### Ellipse

To create an ellipse/circle, you can add:

```python
ellipse_name = ab.sprite.Ellipse(list(pos), list(size), color(color), str(title))
```

Run `help(ab.sprite.Ellipse)` for more technical information.

### Text

To create text, you can add:

```python
text_name = ab.sprite.Text(str(fontname), str(text), int(fontsize), tuple(pos), color(color))
```

Run `help(ab.sprite.Text)` for more technical information.


## Events

### On Mouse Down

Trigger event on mouse down:

```python
OnMouseDown(game(game), def(do))
```

### On Mouse Up

Trigger event on mouse up:

```python
OnMouseUp(game(game), def(do))
```

### On Mouse Motion

Trigger event on mouse motion:

```python
OnMouseMotion(game(game), def(do))
```

### On Update

Trigger event on update:

```python
OnUpdate(game(game), def(do))
```

## Audio

To play audio:

```python
audio_name = Audio(str(file), int(volume))

audio_name.play()
audio_name.pause()
audio_name.unpause()
```

## Colors

Run `help(ab.color)` for more info.
