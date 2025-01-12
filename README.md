# Pong with GDScript

A simple Pong game. This demo shows best practices
for game development in Godot, including

Check out this demo on the asset library: https://godotengine.org/asset-library/asset/121

## How does it work?

The walls, paddle, and ball are all
[`Area2D`](https://docs.godotengine.org/en/latest/classes/class_area2d.html)
nodes. When the ball touches the walls or the paddles,
they emit signals and modify the ball.

