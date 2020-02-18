# 人工标注的人脸与戴口罩人脸数据集
- 数据来源：Google、Baidu
- 数据质量：最小图像为10.8K，全部为jpg格式
- 数据集大小：

| 图像总数 | 人脸总数 | 未佩戴口罩人脸数 | 佩戴口罩人脸数 |
| ---------- | -----------| ---------- | -----------|
| 498 | 1245 | 619 | 626 |

全部使用lableImg工具手工标注

**标注样例：**
![](https://github.com/MacwinWin/face_mask_dataset/blob/master/samples/Screenshot%20from%202020-02-18%2008-12-56.png)

使用Darknet YOLOv3默认参数训练4000 iterations

**loss：**
![](https://github.com/MacwinWin/face_mask_dataset/blob/master/yolov3_result/chart_my-yolov3-mask.png)

**检测结果：**
![](https://github.com/MacwinWin/face_mask_dataset/blob/master/yolov3_result/Screenshot%20from%202020-02-18%2008-22-06.png)

![](https://github.com/MacwinWin/face_mask_dataset/blob/master/yolov3_result/result.gif)

**模型下载：**
这是我训练4000次迭代后的参数文件，有兴趣的可以继续调参训练，看那个loss图还有下降的趋势
地址：https://drive.google.com/file/d/1r7A3Mh_L4vx9P7i-a0nCr_SD-f_yPF7z/view?usp=sharing

如有疑问可通过邮箱与我联系！

天佑武汉！加油！
