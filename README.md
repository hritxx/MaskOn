# MaskOn README

Welcome to MaskOn, a project aimed at detecting whether individuals are wearing masks using computer vision techniques.

## Introduction

MaskOn is a project designed to assist in enforcing mask-wearing policies by automatically detecting whether individuals in a given video stream are wearing masks. The project utilizes deep learning algorithms to analyze video frames and determine whether a person's face is covered by a mask or not.

## Features

- **Real-Time Mask Detection**: MaskOn can analyze live video streams and provide real-time feedback on whether individuals are wearing masks.
- **High Accuracy**: The underlying deep learning model used in MaskOn provides high accuracy in detecting masks, ensuring reliable results.
- **Customizable Thresholds**: Users can adjust detection thresholds to suit their specific requirements or environments.
- **Easy Integration**: MaskOn can be easily integrated into existing security systems or monitoring setups.
- **Scalability**: The project can scale to handle large volumes of video streams and analyze them concurrently.

## Technologies Used

- **Backend**:
  - Python: Programming language used for backend development.
  - OpenCV: Library for computer vision tasks such as image and video processing.
  - TensorFlow: Deep learning framework used for training and deploying the mask detection model.
  
- **Frontend**:
  - HTML/CSS/JavaScript: Frontend technologies for creating the user interface.
  - Bootstrap: Frontend framework for responsive and mobile-first design.
  
## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hritxx/MaskOn.git
   ```

2. Navigate to the project directory:

   ```bash
   cd MaskOn
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the MaskOn server:

   ```bash
   python maskon_server.py
   ```

5. Open your web browser and visit `http://localhost:5000` to access the MaskOn dashboard.

## Usage

1. Access the MaskOn dashboard in your web browser.
2. Configure the video stream source (e.g., webcam, IP camera).
3. Adjust the detection thresholds if needed.
4. Start the mask detection process.
5. Monitor the live video stream and observe the mask detection results.

## Contributing

Contributions to MaskOn are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request or open an issue on the GitHub repository.

## License

MaskOn is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
