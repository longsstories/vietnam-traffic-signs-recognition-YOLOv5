# vietnam-traffic-signs-recognition-YOLOv5
Recognize Traffic Signs using YOLOv5 architecture

Download the data : https://drive.google.com/file/d/13M6nntnZJacxWQDPfyPcUYFjcb__20HM/view?usp=sharing

Set up file data_info.yalm

train: ../data1/images/train    #path to images/train data

val: ../data1/images/valid      #path to images/valid data

nc: 15    #number of classes

names: [ 'Cấm ngược chiều', 'Cấm xe tải', 'Cấm rẽ trái', 'Cấm rẽ phải', 'Cấm đỗ xe','Nơi đỗ xe','Dành cho người đi bộ','Cấm quay đầu','Điểm dừng xe buýt','Giao nhau với đường không ưu tiên','Vòng xuyến','Đi thẳng','Dừng lại','Giao nhau với đường sắt','Cấm bấm còi'] #class names
