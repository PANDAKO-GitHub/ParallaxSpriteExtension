# Parallax Sprite Extension for GDevelop
Pre-release.

This extension adds a parallax effect to the sprite.  
~~This is not Fake 3D.~~ Images cannot be skewed. However, it is now possible to generate a skewed surface by using the ParallaxShapePainter Behavior.

## Games created using this extension:
- [Falconer](https://pandako.itch.io/falconer)
- [ParallaxShooter](https://pandako.itch.io/parallaxshooter)

## 🤝
Please suggest a better description, sentence and function name for this extension.  
By doing so, we will be able to submit this extension to GDevelop.

## FAQ
**Q1** : I saw a video of you rotating the camera on your Twitter. Is it even possible with this extension?

**A1** : No.  
This extension does not support camera rotation. The reason is that enabling rotation makes the controls more complex and increases the load.

## Release notes
### v0.6.3
- Minor fixes.

### v0.6.2
- Added "Load ParallaxSprite Extension" action.
- Added skip drawing process if the object with "ParallaxShapePainter" behavior is not visible.

### v0.6.0
This version of the "ParallaxShapePainter" behavior is not compatible with previous versions.
- "ParallaxShapePainter" behavior now supports multiple draws.
- Revised the "ParallaxShapePainter" and "PlatformerExample" examples.

### v0.5.0
- Add ParallaxShapePainter Behavior.
- Reset the camera position when the scene starts.
- Use Accurate Z Depth.
- Added "ParallaxShapePainter" and "PlatformerExample" examples.