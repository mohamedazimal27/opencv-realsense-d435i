# Depth Measurement using OpenCV and RealSense Camera

This repository contains Python scripts for measuring distances using OpenCV and RealSense Camera. The scripts utilize the RealSense Camera's depth sensing capabilities along with OpenCV's computer vision functionalities to accurately measure distances between objects in the captured scenes.

## Contents

1. **01-depth:**
   - This directory contains Python scripts for capturing depth information from the RealSense Camera using the Intel RealSense SDK.

2. **02-measure-distance:**
   - This directory contains Python scripts for measuring distances between objects detected in the captured scenes using OpenCV.

## Prerequisites

- Intel RealSense Camera
- Intel RealSense SDK
- Python 3.x
- OpenCV
- NumPy

## Usage

1. Ensure that the RealSense Camera is properly connected to your system and the Intel RealSense SDK is installed.
2. Install the required Python dependencies by running:
```bash
pip install opencv-python numpy pyrealsense2
```
3. Navigate to the respective directory (`01-depth` or `02-measure-distance`) containing the script you want to execute.
4. Run the Python script using:
```bash
python script_name.py
```
5. Follow the on-screen instructions to capture depth information and measure distances between objects.

## Contributing

Contributions to enhance the functionality or fix issues are welcome. If you find any bugs or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Intel for developing the RealSense Camera and SDK.
- Thanks to the OpenCV community for providing a powerful computer vision library.

## Contact

For any inquiries or support regarding this repository, you can contact [Your Name] via email at [mohamedazimal27@gmail.com].

## Note

Ensure that you have appropriate permissions and follow all legal and safety guidelines while using this software, especially in scenarios involving measurement and analysis. The developers of this software hold no responsibility for any misuse or consequences arising from its usage.
