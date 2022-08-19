# tatarstan


git clone yolov5


python detect.py --weights runs/train/result6/weights/best.pt runs/train/result9/weights/best.pt  --source /home/powned/projects/test/images --save-txt --augment --conf-thres 0.02 --img-size 2200 --iou-thres 0.4 --save-conf
