# OpenCV-MinGW-Builds

---

It couldn't build OpenCV 5.0.0 for some reason. The build action has set to disabled.

---

The Builds of OpenCV with Windows and MinGW, support OpenCV version 4.12.0 and higher.

Github Actions will check and build the latest version of OpenCV, and releases its `install` folder.

compilation configures(only show edited):

| Entity | Changes | interpretations |
| --- | --- | --- |
| `BUILD_EXAMPLES` | Enable | Build all examples |
| `BUILD_opencv_world` | Enable | Include opencv_world module into the OpenCV build |
| `CPU_DISPATCH` | Clear all values | Specify list of dispatched CPU optimizations |
| `WITH_OPENGL` | Enable | Include OpenGL support |
