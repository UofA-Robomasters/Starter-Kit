# LabelImg
[//]: # (Image References)

[image1]: ./images/start.PNG "start"
[image2]: ./images/add_images.PNG "add_images"
[image3]: ./images/image_added.PNG "images_added"
[image4]: ./images/draw_rect.PNG "draw_rect"
[image5]: ./images/label_dir.PNG "label_dir"
[image6]: ./images/hotkeys.PNG "hotkeys"

## installation

### Windows & Linux
Elsewhere:

https://tzutalin.github.io/labelImg/

Download the latest version (1.7)

In China:

百度云

链接:https://pan.baidu.com/s/1G7Yvtz7d-zj-FKdMS44_Aw  密码:ncc4

### Mac OS
in terminal

```commandline
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

git clone https://github.com/tzutalin/labelImg.git
cd labelImg

brew install qt
brew install libxml2
make qt5py3
python labelImg.py
```

## Usage
After the command above it done. This should show up.
![alt text][image1]

Add image directory
![alt text][image2]

Add label directory
![alt text][image5]

The image should be loaded by now
![alt text][image3]

Then you can label images
![alt text][image4]

Hotkeys are shown below
![alt text][image6]
