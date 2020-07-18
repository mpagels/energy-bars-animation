# Energy bars simple css animation

## Live full-version:

https://mpagels.github.io/energy-bars-animation/

## Live "one"-bar-version:

https://mpagels.github.io/energy-bars-animation/one-bar-animation.html

Refresh live-page to view animation again

<hr>

### Little documentation:

```
animation: energy__you--10 0.5s forwards;
```

`energy__you--10`: how you name you animation (for the `@keyframe` part)  
`0.5s`: how long your animation should take  
`forwards`: this means, the animation freezes at the last frame of animation

### Animation

```
@keyframes energy__you--10 {
  from {
    height: 0px;
  }
  to {
    height: 120px;
  }
}
```

`from`: startpoint of height  
`to`: endpoint of height
