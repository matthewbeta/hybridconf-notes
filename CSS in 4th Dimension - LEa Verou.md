# Lea Verou - CSS in the 4th dimension

4th Dimension?
1. X 
2. Y
3. Depth (x)
4. Time

## "Abruptness is bad UX"
- Transitions are not just fluff
- Delays can be bad for experienced users
- Context is important "Show me the damn line"
- *Delays are even worse*. Don't piss of your users 

## Transitions
TIP: use box shadow to make the modal overlay

height auto doesn't work. - What is 75% auto?!? (thats why it doesn't work) You need to interpolate between the two states (eg. no block > static)

[animatable github](http://leaverou.github.io/animatable/)

Display property not animatable but you could hack it. Can't show an item from none to block, but!!! you could with transform scale (0) to 100%

CSS4 crossfade

CSS transitions to persist state

[cubic-bezier.com](http://cubic-bezier.com)

## Animations

You con ommit the from or to state in keyframes to animate from/to default states
