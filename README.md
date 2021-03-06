# TensorDash
<img src="readme_resources/cover_image.jpeg">
TensorDash is an application that lets you remotely monitor your deep learning model's metrics and notifies you when your model training is completed or crashed.

#### Check out the documentation [here](https://cleanpegasus.github.io/TensorDash/)

## Why Tensordash?

1. Watch your model train in real-time
2. Supports all major deep learning framework
3. Remotely get details on the training and validation metrics
4. Get notified when your model has completed trainng or when it has crashed.
5. Get detailed graphs on your model’s metrics.


## Installation ##

### Installing the Python Package ###

There are two ways to install tensordash:

- **Install tensordash from PyPI (recommended):**

Note: These installation steps assume that you are on a Linux or Mac environment.
If you are on Windows, you will need to remove `sudo` to run the commands below.

```sh
sudo pip install tensor-dash
```

If you are using a virtualenv, you may want to avoid using sudo:

```sh
pip install tensor-dash
```

- **Alternatively: install tensordash from the GitHub source:**

First, clone TensorDash using `git`:

```sh
git clone https://github.com/CleanPegasus/TensorDash.git
```

 Then, `cd` to the TensorDash folder and run the install command:
```sh
cd TensorDash
sudo python setup.py install
```


### Installing the Android App ###

Install the android app from the play store.<br>
[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="30%" width="30%">](https://play.google.com/store/apps/details?id=tech.tensordash.tensordash)

## [How to use](https://cleanpegasus.github.io/TensorDash/usage/)

TensorDash supports all the major deep learning frameworks. You can check out the documentation of the project [here](https://cleanpegasus.github.io/TensorDash/usage/).

## Support

<div class="container">
    <div style="float:left;width:49%">
	    <img src="readme_resources/tensorflow.png">
		<h4> Tensorflow </h4>
    </div>
    <div style="float:left;width:49%">
	    <img src="readme_resources/keras.png">
		<h4> Keras </br>
    </div>
    </div>
</div>
<br>
<div class="container">
    <div style="float:left;width:49%">
	    <img src="readme_resources/pytorch.png">
		<h4> Pytorch </h4>
    </div>
    <div style="float:left;width:49%">
	    <img src="readme_resources/fastai.png">
		<h4> Fastai </br>
    </div>
    </div>
</div>
<br>
</br>
