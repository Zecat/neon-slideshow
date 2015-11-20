# neon-carousel

##TODO

### attributes

- direction = "horizontal | vertical | right | left | up | down" : set the carousel direction, default to horizontal.
- reverse : if true, when using direction="horizontal | vertical" reverse the animation's direction (up=down, right=left…)
- fade : add a fade in/out effect.
- jump-over : if true, when selecting a distant item, do not perceive the items between, animation only concerns the initial and selected items.
- no-loop : if true, the animation's direction is chosen according to the items list order.

### api methods
- _setAnimations() has to handle up and down direction

### Issues

- play the animation while the previous one isn't finished should not leave a blank
- on delay change, it souldn't be inferior to the animation duration

### Around

- add doc
- generate gh-page
- better demo

### ???

- use dynamic html import for animations.
- using on-track to slide.
