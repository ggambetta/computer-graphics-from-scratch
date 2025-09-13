{% block header %}{% endblock %}
{% set html_class="cgfs" %}
{% set html_title="Afterword - Computer Graphics from Scratch" %}
# Afterword {{'{#'}}afterword .unnumbered}

Congratulations! You now have a good understanding of how 3D rendering works. You've created a raytracer and a rasterizer and gained a good conceptual understanding of the algorithms and math that power them.

However, as I explained in the introduction, it's impossible to cover the entirety of 3D rendering in a single book. Here's a few topics you might want to explore on your own to expand your horizons:

Global illumination, including radiosity and path tracing

:   Find out how deep the "ambient light" rabbit hole goes!

Physically based rendering

:   Illumination and shading models that don't just look good, but model real-life physics.

Voxel rendering

:   Think Minecraft, or MRI scans in hospitals.

Level-of-detail algorithms

:   This includes offline and dynamic mesh simplification, impostors, and billboards. These algorithms are how we efficiently render forests with billions of plants, crowds of millions of people, or extremely detailed 3D models.

Acceleration structures

:   This includes binary space partition trees, k-d trees, quadtrees, and octrees. These structures help efficiently render massive scenes, such as an entire city.

Terrain rendering

:   How to efficiently render a terrain model that might be as big as a country yet have human-scale detail.

Atmospheric effects and particle systems

:   Fog, rain, and smoke, but also some less intuitive materials like grass and hair.

Image-based lighting

:   Similar to environment mapping, but for diffuse lighting.

High dynamic range, gamma correction

:   The color representation rabbit hole also goes deep.

Caustics

:   Also known as "the moving white patterns at the bottom of the swimming pool."

Procedural generation of textures and models

:   Add more variety and possibly infinitely big scenes.

Hardware acceleration

:   Using OpenGL, Vulkan, DirectX, and others to run graphics algorithms on GPUs.

Of course, there are many other topics, and that's just 3D rendering! Computer graphics is an even broader subject. Here are some areas you might want to investigate:

Font rendering

:   This is surprisingly more complex than you might think.

Image compression

:   How to store images in the least amount of space.

Image processing (e.g. transforming and filtering)

:   Think Instagram filters.

Image recognition

:   Is that a dog or a cat?

Curve rendering, including Bezier curves and splines

:   Find out what these weird arrows on the curves of your favorite drawing program really are!

Computational photography

:   How does the camera on your phone take such good pictures with almost no light?

Image segmentation

:   Before you can "blur the background" of your video call, you need to determine which pixels are background and which aren't.

Congratulations again on taking your first step into the world of computer graphics. Now you get to choose where to go next!