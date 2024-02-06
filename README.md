# YOLOv7
1. 請將 Yolo7 內容放在 c:\Yolo7 下 (不然要自行更改一些絕對路徑)
2. 在 c:\Yolo7 中執行 python .\train.py --weights yolov7x.pt --cfg .\cfg\training\yolov7x.yaml --data .\data\key.yaml --epoch 100 --batch-size 1 --img 640 640 --device 0
3. 裡面是老師提供的車牌圖檔
4. 如果不是高階電腦, 請改用 python .\train.py --weights yolov7x.pt --cfg .\cfg\training\yolov7x.yaml --data .\data\key.yaml --epoch 100 --batch-size 1 --img 640 640 --device CPU
