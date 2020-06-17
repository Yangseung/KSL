# KSL
The Korean Sign Language Dataset

# Dataset
- [RGB](https://www.dropbox.com/s/6jw50r784k36q5e/KSL_rgb.zip?dl=0)
- [RGB train/val/test]

- [Optical Flow](http://www.dropbox.com/s/uns43wmq0dl0ali/KSL_opflow.zip?dl=0)
- [Optical Flow train/val/test]

- [Video](http://www.dropbox.com/s/8wse0lmxngysl2h/video.zip?dl=0)
- [Label](https://drive.google.com/file/d/1nFF_VsilnJv1jyshtdUKtoX_kNbwCk3w/view?usp=sharing)

# Format
- RGB, Optical Flow datasets

RGB : 255 * 255

Optical flow : x, y, magnitude (3 channel) from "High accuracy optical flow estimation based on a theory for warping."

- RGB train/val/test and Optical flow train/val/test file


# Networks
- TSN

BN inception

consensus type: average

segments: 7

batch size: 8

dropout rate: 0.7

lr: 0.001

- I3D

Inception-v1

input frames: 32

batch size: 8

lr: 0.001

- LRCN

Vggnet+LSTM

input frames: 16

batch size: 48

lr: 0.001

# Paper
- [The Korean Sign Language Dataset for Action Recognition](https://link.springer.com/content/pdf/10.1007%2F978-3-030-37731-1_43.pdf)
