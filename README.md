# Objectify:Object Finder

A streamlit web application that utilizes Google's generative AI to identify objects in an image. Users can upload an image, and the application will detect objects present in the image and output them in a list in alphabetical order.

## Features

- Upload an image in JPG, JPEG, or PNG format.
- Detect objects present in the uploaded image.
- Display the dimensions of the uploaded image.
- Output a list of detected objects in alphabetical order.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/rishii100/Objectify.git
cd Objectify
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project directory and add your Google API key:

```plaintext
GOOGLE_API_KEY=your_google_api_key
```

Replace `your_google_api_key` with your actual Google API key.

## Usage

Run the Streamlit application using the following command:

```bash
streamlit run app.py
```

Once the application is running, open the provided URL in your web browser. You can then upload an image, click on the "Identify the objects" button, and view the detected objects.

## Acknowledgments

- This project utilizes the Google generative AI library for object detection.
- Streamlit is used for building the interactive web application.
- PIL (Python Imaging Library) is used for image processing.

## License

This project is licensed under the [Apache2.0 License](LICENSE).
