# Heart Animation

An animated particle heart drawn with Python's built-in `turtle` module.

Thousands of short, randomly angled strokes are scattered along scaled copies of the classic parametric heart curve, then a second pass adds a bright glowing outline.

## Heart curve

```
x = 16 sin³(t)
y = 13 cos(t) − 5 cos(2t) − 2 cos(3t) − cos(4t)
```

## Run

Requires Python 3 with Tkinter (included in most Python installs). No third-party packages.

```bash
python heart.py
```

Close the window to exit.
