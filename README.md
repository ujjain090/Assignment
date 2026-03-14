# Playing Card Detection

Used YOLOv5 to detect playing cards from images and video. Trained on a kaggle dataset.

Only 1 class (playing_card) since the dataset didnt have labels for individual cards.

## Setup

```
cd code
pip install -r requirements.txt
```

Then open `Playing_card_inference.ipynb` and run the cells.

You can also run directly:
```
python detect.py --weights weights.pt --source images/ --conf-thres 0.5
```

## What's in here

- `Playing_card_inference.ipynb` - main notebook for running detection
- `code/weights.pt` - trained weights
- `code/detect.py` - detection script
- `code/images/` - test images i used
- `code/output_video.avi` - sample video

## Dataset

https://www.kaggle.com/datasets/luantm/playing-card
