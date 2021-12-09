# Set solver
## Installation
`pip install -r requirements.txt`
## Usage
### Running on an image
`python solver_final.py --image path/to/img.jpg`
### Running on a video
`python solver_final.py --video path/to/video.mov [-o output/video/path.avi] [--display]`
(Note that it was only tested with `.mov` inputs and `.avi` outputs)
The `display` flag will optionally show each frame as its processed.
The `o` flag will write the video.
## Directory
`./test_img/` contains a sampling of frames taken from videos I captured when playing set.
`./train/` contains images of each shape, for template matching by the solver.
