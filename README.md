# Team16 - Wav2Lip: Precision Lip-syncing for Real-world Videos"


**About**
----------
This repository hosts the code for "A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild". It provides a comprehensive toolkit for generating accurate lip movements from speech in diverse real-world scenarios. With this technology, achieve seamless lip-syncing for any speech input, offering a versatile solution for various applications.


**Highlights**
----------
 - The visual quality discriminator's weights have been recently revised in the readme.
 - Achieve precise lip-syncing in videos to match any target speech with utmost accuracy :100:.
 - Compatible with all identities, voices, and languages, including CGI faces and synthetic voices. :sparkles: .
 - Access comprehensive training code, inference code, and pretrained models :boom:
 - Alternatively, get started quickly using the Google Colab Notebook [Link](https://colab.research.google.com/drive/1VHof_jhHvWlCtIeQNLFBGqJzDqCdJ9U4?usp=sharing).

**Prerequisites**
-------------
- `Python 3.6` 
- ffmpeg: `sudo apt-get install ffmpeg`
- Install necessary packages using `pip install -r requirements.txt`. Alternatively, instructions for using a docker image is provided [here](https://gist.github.com/xenogenesi/e62d3d13dadbc164124c830e9c453668). Have a look at [this comment](https://github.com/Rudrabha/Wav2Lip/issues/131#issuecomment-725478562) and comment on [the gist](https://gist.github.com/xenogenesi/e62d3d13dadbc164124c830e9c453668) if you encounter any issues. 
- Face detection [pre-trained model](https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth) should be downloaded to `face_detection/detection/sfd/s3fd.pth`. 
