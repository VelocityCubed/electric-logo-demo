# Electric Logo Demo

An interactive 3D VelocityCubed logo with bevelled geometry, reflective lighting, and animated electric edges.

**[Open the live demo](https://velocitycubed.github.io/electric-logo-demo/)**

Move the pointer to tilt, drag to rotate, or click to send a surge. Use the appearance controls to adjust colour, depth, electricity, and motion.

The logo slowly rotates by default, making one full turn per minute. Use **Rotation speed** to stop or accelerate it and **Rotation direction** to turn left or right. Dragging holds automatic rotation temporarily; **Pause** freezes the entire animation.

A glowing arc cursor follows the pointer, with fine electric strands and sparks on click. It matches the selected light colour, hides on pause, and is disabled for touch and reduced-motion settings. The effect is an original implementation inspired by the public [React Bits Pro Arc Cursor preview](https://pro.reactbits.dev/docs/components/arc-cursor).

This repository contains the built website. The application source is maintained in a separate private repository.

The electricity effect is adapted from [React Bits Electric Logo](https://reactbits.dev/animations/electric-logo). Its upstream copyright and MIT + Commons Clause licence are included in [REACT-BITS-LICENSE.txt](REACT-BITS-LICENSE.txt). No licence is granted here for VelocityCubed's logo.
