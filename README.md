# Sketch2Stitch: Generating Realistic Clothing Images from Sketches

## Dataset
You can find the dataset used in this project by following the link below:
[Dataset Link](https://drive.google.com/drive/folders/1DErJwBZQrAPkaluW-QmJo2pBaj78U62c?usp=sharing)

For training the Pix2Pix model, you'll need a dataset containing pairs of input sketches and corresponding real images. Ensure that your dataset is appropriately formatted before proceeding with training.

## Training
1. Preprocess your dataset to create pairs of input sketches and real images.
2. Define and compile the Pix2Pix model architecture.
3. Train the model using the prepared dataset.
4. Adjust hyperparameters as necessary to achieve desired results.
5. Evaluate the trained model on validation data to assess its performance.

## Usage
Once the model is trained, you can use it to generate realistic images from input sketches. Here's how to use the trained model:
1. Load the trained Pix2Pix model weights.
2. Provide a sketch image as input to the model.
3. Generate a realistic image from the input sketch using the trained model.
4. Save or display the generated image.

## Acknowledgments
- This project was inspired by the Pix2Pix paper by Isola et al. (2017).
- Thanks to the TensorFlow and Keras teams for their excellent libraries.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
