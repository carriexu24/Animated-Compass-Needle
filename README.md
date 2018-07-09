# Animated-Compass-Needle
Animate the needle taking the shortest path from the current needle direction to the correct direction.


## Rules

You are to part of a team developing animated compass needle. The API is simple: the compass needle is currently in some direction (between~0 and~359 degrees, with north being~0, east being~90), and is being animated by giving the degrees to spin it. If the needle is pointing north, and you give the compass an input of~90, it will spin clockwise (positive numbers mean clockwise direction) to stop at east, whereas an input of~-45 would spin it counterclockwise to stop at north west.

## Examples

Git clone the repository and run the code in the terminal.

1. Return 90.

```
python compas.py 315 45
```

2. Return 90.

```
python compas.py 180 270
```

3. Return -135.

```
python compas.py 45 270
```
