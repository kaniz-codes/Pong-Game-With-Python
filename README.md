# Pong-Game-With-Python
Demonstration of what I've exercised as far as I learned!


#Steps are given below as Flow Chart


![board-adorable-unicorn](https://github.com/kaniz-codes/Pong-Game-With-Python/assets/138873297/9255bcfa-8a4d-41bb-930f-8c8af752a110)



*Before Setting up border for the Left and Right Paddles

![codeimage-snippet_5](https://github.com/kaniz-codes/Python-Projects/assets/138873297/547b1f57-8d7b-47c9-b40f-3924ce85ee73)

The code below had to work on mentioned things but failed.
1. The ball reverses its direction when it touches either vertical boundary (left or right).
2. The ball resets to the center when it crosses either vertical boundary.
3. Scoring is appropriately handled when the ball crosses either vertical boundary.

![codeimage-snippet_5 (1)](https://github.com/kaniz-codes/Pong-Game-With-Python/assets/138873297/6cf85c47-a8a5-478d-9195-a475fce7e02e)

*A few key things have been corrected:

1. Added the case where the ball crosses the left boundary, and Player B scores a point.
2. Modified the paddle collision checks to be more consistent in terms of logic.
3. Made adjustments to the ball-paddle collision check, considering the size of the paddles.
![codeimage-snippet_5 (2)](https://github.com/kaniz-codes/Pong-Game-With-Python/assets/138873297/1278cee7-b9ee-45ff-b843-def9553ab828)
