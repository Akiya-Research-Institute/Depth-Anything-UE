# Depth Anything UE

UE5 project for real-time monocular depth estimation with Depth Anything ONNX. Nanite Tessellation is used to visualize the result.

## Environment

- OS: Windows 10 64bit
- Unreal Engine: 5.3.1
- [NNEngine plugin](https://www.unrealengine.com/marketplace/product/74892c770dc149b1b5c4e872804e6ade): v1.7

## Setup

You need to use ONNX Runtime v1.15.1.
Follow [the instruction in the manual](https://akiya-research-institute.github.io/NNEngine-API/en/tips-latest-ort/).

## Download

Please download from the [release](https://github.com/Akiya-Research-Institute/Depth-Anything-UE/releases) page.

## Run the demo

1. Extract the downloaded zip file and double-click `DepthAnythingDemo.uproject`.  
2. Click `Play`.
3. Open `Content/Common/MediaPlayer_webcam` and specify your camera.

## Model details

See the following pages for the details of the model used in this project.

- [Depth Anything](https://github.com/LiheYoung/Depth-Anything)
- [Depth Anything ONNX](https://github.com/fabio-sim/Depth-Anything-ONNX)
