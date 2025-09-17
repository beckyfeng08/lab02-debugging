
# Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solution with the bugs corrected
- In the README, describe each bug you found and include a sentence about HOW you found it.
- Make sure all three of your shadertoys are set to UNLISTED or PUBLIC (so we can see them!)

https://www.shadertoy.com/view/3fXfDl
Teammates:
Gavin Sears

Link: https://www.shadertoy.com/view/3fXfDl

Bugs:
1. Compile-time error line 99 vec syntax error fixed to vec2
2. Compile-time error line 99 normalize UV coordinates to [-1, 1] on both x and y axes
3. Compile time error line 102 raycast argument take in uv2 instead of uv
4. Runtime error line 11 iResolution.x changed to iResolution.y to get the length of the horizontal screen correctly
5. Runtime error line 75 change reflect argument from eye to dir to account for finding the direction of the ray bouncing off of the sphere and not a consistently valued ray
   
