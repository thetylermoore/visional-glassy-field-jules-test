Visional Glassy Field is a GLSL shader designed for Synesthesia Live, and is an adaptation of Abstract Glassy Field created by Shane (Original GLSL: https://www.shadertoy.com/view/4ttGDH). 
Aspects of the scene have been adjusted to utilize many of the Synesthesia Shader Format utilities to make the scene fully audio reactive. 

Audio Reactive elements include movement based on the audio input's time. Bass Hits will affect shadows and the purple glow.

Scene controls allow the user to adjust parameters within the scene like glow, intensity, vibrance, camera parameters, and more.
See the included `Scene Controls.png` for an overview of available controls.

Demo video: https://www.youtube.com/watch?v=3HpyvFEv1yg

NOTE: To use this scene, import the synScene file into Synesthesia Live.

License: WTFPL, Author: Kevin McIntosh (Visional), found: https://github.com/kmac303

------------------------------------------------------------------------------

An abstract, blobby-looking field - rendered in the style of hot, glowing glass. It was produced using cheap low-budget pseudoscience.

The surface was constructed with a spherized sinusoidal function, of sorts. I like it, because 
it's very cheap to produce, mildly reminiscent of noise and allows a camera to pass through it 
without having to resort to trickery.

The fluid filled glass look is fake, but at least interesting to look at. Basically, it was
produced by indexing the reflected and refracted surface rays into a 3D tri-planar texture
lookup. By the way, I've tried the real thing on this particular surface - with multiple ray 
bounces and so forth - and to say it's slower is an understatement.
