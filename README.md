# Vangogh Crazy World

One Paragraph of project description goes here, example: Neural Style Transfer, Van Gogh Crazy World
Descriptions:
* Background, example: Learning what is neural style transfer, short explination of the neural style transfer history

## Neural style transfer

Neural style transfer is the process of taking the style of one image then applying it to the content of another image.
Offering you a variety of beautiful styles some of which are paintings by famous artists like Starry Night by Van Gogh.

* Motivation, example: We would like to pay tribute to MR. Van Gogh, who is the ...maybe more link to wiki
* Experience, example: A full package of build neural style transfer training on Linux and Android inference applications (and Windows link in another repository)

## Table of Contents (Optional)

* Features
* Getting Started
* Prerequisites
* ...

## Features

Features supportted, example:
In this project, it will provide the following packages
* Training Van Gogh gallery with Python
* Inference with real time camera and still images
* Deployment on Windows application
* Deployment on Windows application
* Deployment on web browser


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Getting the Code

```
git clone https://github.com/acerwebai/VangoghCrazyWorld.git
```

### Get Pre-Trained Model
Pre-trained models can be download from here

### Prerequisites

What things you need to install the software and how to install them

* Python

If your machine support nVidia GPU, please refer to the installation from nVidia 
* CUDA (optional): 
https://docs.nvidia.com/cuda/
* cuDNN (optional): 
https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html


### Create Virtual Environment

In creating a virtual environment you will create a directory containing a python3 binary and everything needed to run VangoghCrazyWorld. You can create it using this command:

```
virtualenv -p python3 $HOME/tmp/VangoghCrazyWorld-venv/
```

Activate the virtual environment

```
source $HOME/tmp/VangoghCrazyWorld-venv/bin/activate
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

Change directory to VangoghCrazyWorld

```
cd VangoghCrazyWorld
```

Required packages are listing in the requirements.txt, all you need to do is just as following command

```
pip install -r requirements.txt
```
Note: If your machine do not support nVidia GPU, please replace Tensorflow-gpu as Tensorflow in the requirements.txt


### Run Pre-Trained Models
If possibile, end with an example of getting some data out of the system or using it for a little demo




## Training

Explain how to do the training with the script

```
Give an example
```

### Tuning parameters

Explain parameters and how to tuning parameters to see different results with the script

```
Give an example
```


## Testing

Explain how to do the testing with the script and show the results

```
Give an example
```

## Transfer Taining, build your own model

Explain how to build your model with your data with the script

```
Give an example
```
### Find Your Checkpoint
### Freezing Model


## Deployment

Add additional notes about how to deploy this on a live system

## Built With

### Android APP
See [Android_README.md](Android_README.md)
### Windows APP
See [Windows_README.md](Windows_README.md)
### Web pages
See [Web_README.md](Web.md)

## Implementation Details
The implementation is based on the [Fast Style Transfer in TensorFlow from ](https://github.com/lengstrom/fast-style-transfer) from [lengstrom](https://github.com/lengstrom/fast-style-transfer/commits?author=lengstrom)

It use roughly the same transformation network as described in Johnson, except that batch normalization is replaced with Ulyanov's instance normalization, and the scaling/offset of the output tanh layer is slightly different. We use a loss function close to the one described in Gatys, using VGG19 instead of VGG16 and typically using "shallower" layers than in Johnson's implementation (e.g. we use relu1_1 rather than relu1_2). Empirically, this results in larger scale style features in transformations.

### Paper
### Framework
### Model
### Optimization
### ...

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.
See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## Versioning

Version and release note

## Team

Team member

## FAQ

Frequently ask questions

## Support

Who you should contact with, email


## License

This project is licensed under the Apache License 2.0, see the [LICENSE.md](LICENSE)

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* ...


