# Shravan: Visually Impaired Guidance Application

Shravan is an Android application that aims to provide guidance and assistance to visually impaired individuals. It leverages object detection using TensorFlow Lite to help users detect objects in their surroundings.

## Features
<!-- Add bullet points -->
  - Real-time object detection using a pre-trained model
  - Camera preview with object tracking overlay
  - Customizable model selection and inference settings

[//]: # ()
[//]: # (##Screenshots)

[//]: # (<!-- Add screenshots of the app in action -->)

[//]: # ()

## Getting Started

1. Clone the repository to your local machine.

```shell
git clone https://github.com/ssharmapavitra/Shravan.git
```

2. Open the project in Android Studio.

3. Build and run the application on an Android device or emulator with a minimum SDK version of 21.

## Usage

Once you have the Shravan application running on your Android device or emulator, it assists visually impaired individuals in detecting objects in their surroundings. The application provides a user-friendly interface for selecting images or accessing the device's camera.

1. Launch the app on your Android device.

2. The app will display a screen with two options: one for text reader and the other for object detection.

3. Choose the desired option:

   a. Text Reader: If you select this option, the app will use Optical Character Recognition (OCR) technology to capture and read out text from documents, books, or any printed material in real-time. Simply point your device's camera towards the text, and the app will provide voice output, making it easier for visually impaired individuals to access written information.

   b. Object Detection: If you select this option, the app will utilize TensorFlow Lite's object detection model to identify objects in your surroundings. The camera preview will open, and object detection will start automatically. Detected objects will be highlighted with bounding boxes overlaid on the camera view. The app will provide real-time voice output, describing the objects it detects.

4. Customize the object detection settings using the provided options in the app. You can adjust the sensitivity, enable or disable audio feedback, and explore other configuration options to enhance the user experience.

5. Enjoy real-time voice output and assistance as you use the Sharvan app to read text or detect objects around you.

Feel free to explore the features and functionalities of the app to provide a seamless and enhanced experience for visually impaired users.

Note: The Shravan app does not require an internet connection for its core functionality. All processing and voice output are done locally on your Android device, ensuring privacy and reliable performance.

## Customization

If you wish to use your own models for object detection, you can replace the default models used in the application. Place your custom models in the "assets" directory and modify the necessary code accordingly.

## Contributing

Contributions to the Shravan project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

The Shravan application is built upon the TensorFlow Lite examples and incorporates various open-source libraries and resources.

Feel free to customize and enhance the application based on your requirements.

