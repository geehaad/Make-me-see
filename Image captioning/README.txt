It's used to understand the scene then play it as an audio to help blind people to understand what is going around them.
Using MS-COCO dataset only a supset 45,000 caption and their corresponding images to train.
Then preprocess the image using Inception V3:
	resize the image to 299x299.
	normalize the image so that it contains pixels in the range of -1 to 1.
Train for 20 epochs with batch size equal 64.

