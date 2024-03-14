# Demo App: Document Scanner AI

This is a demo Android application showcasing the integration of Google's ML Kit Vision Document Scanner. The application allows users to scan documents using their device's camera and save the scanned pages as either JPEG images or a PDF file.

![image](https://github.com/Hasnain17/doc_scanner_ai/assets/62245237/f554c020-0765-40a7-9172-e2b6a506844c)


## Features

- **Document Scanning**: Utilizes Google's ML Kit Vision Document Scanner to capture document images.
- **Multiple Formats**: Supports saving scanned documents in both JPEG and PDF formats.
- **Gallery Import**: Provides the option to import images from the device's gallery for scanning.
- **Page Limit**: Allows setting a maximum page limit for scanning.

## Installation

To run the application locally, follow these steps:

1. Clone this repository to your local machine:

    ```
    git clone https://github.com/Hasnain17/doc_scanner_ai.git
    ```

2. Open the project in Android Studio.

3. Build and run the project on an Android device or emulator.

## Usage

1. Launch the application on your Android device.
2. Tap the "Scan PDF" button to start scanning documents.
3. Use your device's camera to capture images of the documents you want to scan.
4. After capturing all desired pages, the scanned images will be displayed in the app.
5. Optionally, save the scanned document as a PDF by tapping the "Save as PDF" button.

## Dependencies

- [Google ML Kit Vision](https://developers.google.com/ml-kit) - Used for document scanning functionality.
- [Coil](https://coil-kt.github.io/coil/) - For image loading and displaying scanned document pages.
- AndroidX Libraries - Standard Android libraries for UI components and activity result contracts.

## Contributing

Contributions are welcome! If you'd like to enhance the functionality of this application or fix any issues, feel free to submit a pull request.


## Acknowledgments

- Thanks to Google for providing ML Kit Vision, enabling document scanning capabilities.
- Special thanks to the developers and contributors of Coil for simplifying image loading in Android applications.
