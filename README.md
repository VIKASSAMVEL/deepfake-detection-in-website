# Deepfake Detection Website

This project is a web application for detecting deepfake images using a YOLO (You Only Look Once) model. Users can upload images or capture images using their webcam, and the system will analyze the images to determine if they have been manipulated.

## Features

- **Upload Image**: Users can upload an image from their device for deepfake detection.
- **Live Webcam Feed**: Users can capture an image using their webcam for deepfake detection.
- **Upload History**: View the history of uploaded images and their detection results.
- **Feedback**: Users can submit feedback about the application.
- **How It Works**: Detailed explanation of how the deepfake detection system works.

## Technologies Used

- **Flask**: A lightweight web framework for building the server-side application.
- **YOLO**: A real-time object detection system used to detect manipulations in images.
- **HTML, CSS, and JavaScript**: Front-end technologies used to build the user interface.
- **Bootstrap**: A CSS framework for responsive design.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/deepfake-detection-website.git
    cd deepfake-detection-website
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python app.py
    ```

5. Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

- **Upload Image**: Click on the "Upload Image" section, choose an image file, and click "Upload and Detect".
- **Live Webcam Feed**: Click on the "Capture and Detect" button to capture an image using your webcam.
- **Upload History**: Click on the "View Upload History" button to see the history of uploaded images and their detection results.
- **Feedback**: Click on the "Submit Feedback" button to provide feedback about the application.
- **How It Works**: Click on the "How It Works" button to learn more about how the deepfake detection system works.

## Feedback

If you have any feedback or suggestions, please feel free to submit them through the feedback form on the website.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
