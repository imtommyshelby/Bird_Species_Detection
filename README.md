

<h2 align="center">Bird Species Detection</h2>

<p align="center">
  <strong>A VGG19-Based Algorithm for Bird Species Detection</strong>
</p>

<div align="center">
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#results">Results</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</div>

---

## About

Welcome to the Bird Species Detection repository! This project employs the power of deep learning using the VGG19 architecture to classify various bird species from images. The model has been trained on a dataset with over 5000 bird images, available on Kaggle.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/imtommyshelby/Bird_Species_Detection.git
cd Bird_Species_Detection
```
2. Install The Required Dependencies Using pip
   ```
   pip install -r requirements.txt
   ```
## Usage

- Download the pre-trained VGG19 model weights from here.

- Place the downloaded model weights in the models folder.

- Use the detect_species.py script to perform species detection on an image:
  ```
  python detect_species.py --image path/to/your/image.jpg
  ```
  The script will output the predicted bird species along with confidence scores.

## Results
Check out some of the impressive results achieved by the model in the Results folder. You can see the classification accuracy and example images from the dataset.

## Contributing
Feel free to contribute to this project! If you have any ideas, enhancements, or bug fixes, please open an issue or create a pull request.

## License
This project is licensed under the MIT License.

<p align="center">
  Created with 🦜 by Sagnik
</p>



