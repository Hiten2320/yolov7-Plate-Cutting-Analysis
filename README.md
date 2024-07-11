## Classes:
``` shell
0:hook
1:spark
2:plate
3:lifter

```
## Inference

On video:
``` shell
python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source yourvideo.mp4
```

On image:
``` shell
python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source inference/images/horses.jpg
```

## for saving data into database

1. open Xampp and in that start apache and my sql
2. Make batabase then table in that
4. now run the inference (real_sheetcutting.py)


## In this there logic of ROI and loading and unloading of plate 
