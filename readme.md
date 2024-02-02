
# Sign Language Detection using YOLOv8


## Overview

This project demonstrates the use of YOLOv8 for real-time sign language detection. It leverages a dataset from Roboflow Universe to train the model and achieve accurate detection of various sign language gestures.

## Key Features

- **Real-time Detection:** The model processes video frames efficiently, enabling real-time detection of sign language gestures.
- **Accurate Recognition:** Trained on a diverse dataset, the model effectively recognizes a range of sign language signs.
- **Compatibility with YOLOv8:** Built using YOLOv8, a state-of-the-art object detection model, for optimal performance.
- **Roboflow Integration:** Leverages Roboflow for dataset management and conversion, streamlining the development process.

## Dataset

- **Source:** Roboflow Universe. Link to dataset: [sign_recognition Computer Vision Project ](https://universe.roboflow.com/ss-hwnzd/sign_recognition)
- **Format:** YOLOv8 compatible format 

## Model Architecture

- **YOLOv8:** Employs the YOLOv8 model architecture for object detection.

## Training Process

1. **Dataset Download:** Obtained the dataset from Roboflow Universe in YOLO-v8 format.
3. **Model Training:** Trained the YOLOv8 model on the converted dataset.

## Dependencies

- Python
- PyTorch
- YOLOv8
- Roboflow (for dataset management and dataset)

## Usage

1. Clone this repository.
1. Get dataset from roboflow universe.
3. Download the pre-trained model weights.
4. Run the notebook named `instance_segmentation_sign_recognition.ipynb`

## Results

- Results are stored in result_dir directory. Feel free to check the result. 
- sample predictions are stored in prediction_samples directory 

## Future Work

- Explore model optimization techniques to enhance speed and accuracy.
- Expand the dataset to include a broader range of sign language gestures.
- Integrate the model into applications for real-world sign language interpretation.

## Contributing

I welcome contributions to this project!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any queries or feedback, please reach out to _(Mukund Kumar/mukundwh8@gmail.com)_
