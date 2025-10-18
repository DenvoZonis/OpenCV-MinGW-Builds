This my own custom builds(OpenCV version: 4.13.0-dev).Compared to the main branch, I have added the following compilation configuration:

| Entity | Changes | interpretations |
| --- | --- | --- |
| `BUILD_CUDA_STUBS` | Enable | Build CUDA modules stubs when no CUDA SDK |
| `OPENCV_DNN_OPENVINO` | Enable | Build with OpenVINO support(2021.4+) |
| `OPENCV_ENABLE_NONFREE` | Enable | Enable non-free algorithms |
| `OPENCV_TEST_DNN_OPENVINO` | Enable | Build test with OpenVINO code |
| `WITH_OPENVINO` | Enable | Include Intel OpenVINO toolkit support |
| `WITH_VULKAN` | Enable | Include Vulkan support |