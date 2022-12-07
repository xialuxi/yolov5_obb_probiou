# Yolov5 for Oriented Object Detection  
+ 原始代码请参考：https://github.com/hukaixuan19970627/yolov5_obb  
+ 使用prob_iou，需要把角度的类别修改成181类, 同时修改datasets.py 中 use_gaussian=False
+ 损失函数参考：PP-YOLOE-R  
+ 论文：https://arxiv.org/pdf/2211.02386.pdf  
+ 旋转框的表示PP-YOLOE-R中使用90度，而这里使用180度表示，如果使用基于anchor的方法，推荐180度表示， anchor free推荐90度表示


