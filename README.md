# WebGL_es3x

Intension:
This project is used to expose OpenGL ES 3.x features to web via WebGL
extensions. It includes:
1) a webgl extension to expose multisample texture
2) a big webgl extension to expose OpenGL ES 3.1 core features (except multisample
texture)
3) a webgl extension to expose geometry shader
4) some other webgl extensions to expose features in OpenGL 3.1 or 3.2 features

How to use this project:
Download the project into your local machine. Copy it to ./extensions/proposals/
in KhronosGroup/WebGL.git project.
Run 'make' at ./extensions filefolder. You will get .html file under different
extensions filefolder, say ./extensions/proposals/WEBGL_multisample_texture/.
Then open that .html file with Chrome browser, check it.

Contributions are welcome.
