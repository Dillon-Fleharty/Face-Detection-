# AdaBoost-based Face Detection

## Overview
This project implements a face detector using AdaBoost, combining both skin color information and rectangle filters. It incorporates the concept of classifier cascades to efficiently and accurately detect faces in color images.

## Features
- **AdaBoost Training**: Utilizes AdaBoost with rectangle filters to train the face detection components.
- **Skin Detection**: Employs a skin detector to enhance face detection efficiency.
- **Classifier Cascades**: Implements a sequence of classifiers, ranging from fast and less accurate to slow and more accurate, with appropriately selected thresholds to minimize classification errors.

## Data
The dataset for training and testing is provided in `training_test_data.zip`. It includes:
- Positive examples in `training_faces`
- Negative examples from `training_nonfaces`
- Test data in `test_cropped_faces`, `test_face_photos`, and `test_nonfaces`
- Face annotations in `face_annotations.py`

## Training
The system should be trained using images from `training_faces` as positive examples and windows from `training_nonfaces` as negative examples.

## Testing
The test datasets can be found in the aforementioned directories. A detection is considered correct if there's at least a 50% overlap with the bounding boxes provided in `face_annotations.py`.

## Usage
Instructions for setting up, training, and testing the detector will be provided here.

## Requirements
List of libraries and dependencies to run the project.

## Contributing
Guidelines for contributing to this project (if applicable).

## License
Specify the license under which this project is made available.

## Acknowledgements
Credits to the course materials and any third-party libraries or tools used.

---

Please note that the test data provided should not be used for training purposes.

Happy detecting!
