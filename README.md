# detection--

# - 模型性能比较


| 场景     | 模型       |参数FLOPS  | 环境    |map@0.5|
| :-: | :-: | :-: | :-: | :-: | 
| 目标检测 | yolov3-320 |           | rknn    | /     |
| 目标检测 | yolov3-416 |           | rknn    | /     |
| 目标检测 | yolov3-416 |           | keras   | 100ms | 
| 目标检测 | yolov3-416 |           | darknet | -     |
| 目标检测 | yolov3-416 |           | openvino| /     |
| 目标检测 | yolov3-416 |           | tensorRT| /     |
| 目标检测 | yolov3-416-fp16 |      | tensorRT|35ms   | 
| 目标检测 | yolov3-608-fp16 |      | tensorRT|70ms   |
| 目标检测 | yolov3-tiny-416 |      | rknn    | /     |
| 目标检测 | yolov3-tiny-416 |      | keras   | -     |
| 目标检测 | yolov3-tiny-416 |5.571B|darknet  | 33ms  | 
| 目标检测 | yolov3-tiny-608-fp16|  |tensorrt | 11ms  |
| 目标检测 | yolov4-416 |59.7B      |darknet  | 38ms  |
| 目标检测 | yolov4-608 |           |pytorch  | 100ms |
| 目标检测 | yolov4-608 |           |ncnn     | -     | 
| 目标检测 | yolov4-608 |           |ncnn+vulkan| -   |
| 目标检测 | yolov4-608 |128.5B     |darknet  | 70ms  |
| 目标检测 | yolov4-608-fp16 |      |tensorrt | 90ms? |
| 目标检测 | yolov4-tiny-416 |6.91  |darknet  | 33ms  |
| 目标检测 | yolov4-tiny-416 |      |pytorch  | 40ms  |
| 目标检测 | yolov4-tiny-416 |      |ncnn     | -     |
| 目标检测 | yolov4-tiny-416 |      |ncnn+vulkan| -   | 
| 目标检测 | yolov4-pacsp-384-512|  |pytorch  | 30ms  |
| 目标检测 | enetb0-yolov3|3.73B    |darknet  | 103ms | 
| 目标检测 | yolov5s-640  |13.2B    | pytorch | 15ms  |
| 目标检测 | yolov5m-640  |39.4B    | pytorch | 33ms  |
| 目标检测 | yolov5l-640  |88.1B    | pytorch | 50ms  |
| 目标检测 | yolov5l-640  |166.4B   | pytorch | 84ms  |
| 目标检测 | mobilenetv3-ssd |      | python  | -     | 
| 目标检测 | R-FCN      |           | mmdetection  | -     | 
