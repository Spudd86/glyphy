GLyphy is a signed-distance-field (SDF) text renderer using OpenGL ES2 shading language.

The main difference between GLyphy and other SDF-based OpenGL renderers is that most other projects sample the SDF into a texture.  This has all the usual problems that sampling has.  Ie. it distorts the outline and is low quality.

GLyphy instead represents the SDF using actual vectors submitted to the GPU.  This results in very high quality rendering.

This is a work in progress.

See this video for insight to how GLyphy works:

> http://vimeo.com/behdad/glyphy