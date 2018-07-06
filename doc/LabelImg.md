# LabelImg
- **Author:** Chenrui Lei (chenrui@ualberta.ca) and Wenzhang Qian (wenzhangq@gmail.com)
- **Date:** July 5th, 2018

[//]: # (Image References)

[image1]: ./images/start.PNG "start"
[image2]: ./images/add_images.PNG "add_images"
[image3]: ./images/image_added.PNG "images_added"
[image4]: ./images/draw_rect.PNG "draw_rect"
[image5]: ./images/label_dir.PNG "label_dir"
[image6]: ./images/hotkeys.PNG "hotkeys"
[image7]: ./images/yolo.PNG "yolo"

## installation

### Windows & Linux
Elsewhere:

https://tzutalin.github.io/labelImg/

Download the latest version (1.7)

In China:

百度云

链接:https://pan.baidu.com/s/1G7Yvtz7d-zj-FKdMS44_Aw  密码:ncc4

### Mac OS

There are two ways. Using Linux in virtual machine or build from source.
### 1. Virtual machine
Follow the instructions here : https://pan.baidu.com/s/10SMnZVMeOjKWI9wF6MxVnQ

### 2. Build from source

Since the original installation instructions on [lebalImg](https://github.com/tzutalin/labelImg) repository might not work for brand new Mac, I wrote this additional note to guide you for setting up [lebalImg](https://github.com/tzutalin/labelImg) on a brand now Mac.

#### Xcode

You can install Xcode in iTune store. The reason we install Xcode is because it will install other useful tools along with it automatically.

#### Homebrew

Please follow the instructions on [homebrew's website](https://brew.sh/) to install it or just use the cammand below.

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Git

Git is a tool for software version controlling. We need to use it for downloading the source code of labelImg. You should have Git installed already if you have installed the Xcode. Otherwise, you can use the follow command to install it (note: this command uses Homebrew).

```bash
brew update
brew install git
```

Now, we got the tools that we need. We can download the source code and install the labelImg on our brand now Mac.

#### Step 1: Download the source code

To download the source code of labelImg, we can use the folloing command,

```bash
git clone https://github.com/tzutalin/labelImg.git
cd labelImg
```

#### Step 2: Install dependencies

There are 3 dependencies we need for the labelImg. They are python3, pyqt5, and lxml. We will use the following command to install them.

- python3
```bash
brew install python3
```

- pyqt5
```bash
pip3 install pyqt5
```

- lxml
```bash
pip3 install lxml
```

#### Step 3: Compile the program

Run the command below,

```bash
make qt5py3
```

If there is not errors, your compilation is successful.

#### Step 4: Try to run the program

```bash
python labelImg.py
```

If there is a graphic window pops up, that means your labelImg is good to use.






## Usage
After the command above it done. This should show up.
![alt text][image1]

Add image directory
![alt text][image2]

Add label directory
![alt text][image5]

The image should be loaded by now
![alt text][image3]

FORMAT MUST BE SET TO YOLO!!!!!!!!!!!
#YOLO!!!!!!!!!
YOLO!!!!!!!!!
![alt text][image7]

Then you can label images
![alt text][image4]

Hotkeys are shown below

![alt text][image6]


# References

- https://github.com/tzutalin/labelImg
- https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/