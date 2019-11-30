Demo for beginners using GLFW.

Note
------
1. glad.h + glad.c + khrplatform.h (api v4.6)
    - https://glad.dav1d.de/
2. glad/gl.h => glad/glad.h
3. gladLoadGL(glfwGetProcAddress) => gladLoadGL()
4. linmath.h
    - https://github.com/glfw/glfw/tree/master/deps
5. CMakeLists.txt Link List:
    - libglfw.so libdl.so libm.so
