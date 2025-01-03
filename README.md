# Desmos Plot Picture

## Getting started

### Installation

To be able to run the python programme, you need to have OpenCV installed.

```bash
pip install opencv-python
```

You will also need to install 2 software, ImageMagick, and Potrace.

### Preparation

Download a picture you like (in format of `.jpg`, `.jpeg`, or `.png`), and put it in the same directory as `desmos_plot.py`.

If you are using linux, change the command in line 24 of `desmos_plot.py` from magick to convert.

## Usage

Run the following command.

```bash
python desmos_plot.py
```

After this, the file `desmos_api.js` will be generated. This contains all the formulae. Open `desmos.html` with your favourite browser to see the result!

### Final tweaks

If your plot contains too much, or too little detail, you may need to change the value in line 13 and 14 of `desmos_plot.py`

## Demo video

Click [demo](https://youtu.be/mvcZi3s1ik8) for the video!

## Result

Click [doraemon plot](https://law-chun-man.github.io/desmos_plot/desmos.html) for the interactive plot.

|Original Image|Desmos Plot|
|:---:|:---:|
|![doraemon](README_pictures/doraemon.png)|![doraemon plot](README_pictures/doraemon_plot.png)|
|![adele drawing](README_pictures/adele_drawing.jpg)|![adele plot](README_pictures/adele_plot.png)|
