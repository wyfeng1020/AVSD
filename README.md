## Aerial Video Segmentation Dataset (AVSD)

  Video segmentation refers to the task of partitioning pixels that exhibit homogeneous appearance and motion into coherent spatial-temporal groups, which can be applied to a wide variety of practical aerial applications, such as landscape detection and recognition, ground scene classification, and urgent safe landing. However, few works about aerial video segmentation for higher-altitude platforms are developed in the current literatures due to the lack of common evaluation dataset. Therefore, we collected a new aerial video dataset, which exhibits the simple and challenging conditions of video complexity and motion, for the evaluation of aerial video segmentation algorithms.

### Description
<div align=center>
<img src="https://raw.githubusercontent.com/wyfeng1020/AVSD/master/examples/ImgData_0351.bmp" width = "240" height = "180" alt="ImgData_0351">
<img src="https://raw.githubusercontent.com/wyfeng1020/AVSD/master/examples/ImgData_1702.bmp" width = "240" height = "180" alt="ImgData_1702">
<img src="https://raw.githubusercontent.com/wyfeng1020/AVSD/master/examples/ImgData_4006.bmp" width = "240" height = "180" alt="ImgData_4006">  
</div>
<div align=center>
<img src="https://raw.githubusercontent.com/wyfeng1020/AVSD/master/examples/ImgData_0351_gt.bmp" width = "240" height = "180" alt="ImgData_0351_gt">
<img src="https://raw.githubusercontent.com/wyfeng1020/AVSD/master/examples/ImgData_1702_gt.bmp" width = "240" height = "180" alt="ImgData_1702_gt">
<img src="https://raw.githubusercontent.com/wyfeng1020/AVSD/master/examples/ImgData_4006_gt.bmp" width = "240" height = "180" alt="ImgData_4006_gt">
</div>

  The dataset consists of 10 diverse sequences and total 525 images, of which 131 images are annotated with pixel-wise segmentation labels. The videos are all captured at 12 fps and 1280*1024 spatial resolution. The images contain a variety of man-made and natural “objects” whose appearance varies across sequences and comprises homogenous and textured parts. We select 6 sequences to be annotated by experts. The primary subjects of the aerial videos are mainly various land surfaces and we define six most common types: bare land, grassland, forest, building, road, and vehicles.

  Each folder contains video sequence with same ground scene. For each sequence, there are following files:
  - bmp folder: *.bmp, initial video image;
  - gt_rgb folder: *.bmp, RGB segmentation masks for visualization;
  - gt_label folder: *.bmp, index segmentation masks;
  - gt_mat folder: *.mat, index segmentation masks,  
                   - groundTruth{1,1}.Segmentation,  
                   - groundTruth{1,1}.Boundaries.

### Download
**Representative examples:** [[GoogleDrive](https://drive.google.com/open?id=1GnCoeg-qwfJgLCXCFCAXhjfx7cY2RGvb)]       [[BaiduYunPan](https://pan.baidu.com/s/1yC1ggKRJD0WjmlzY1OcQVw)]

**Full Resolution:** [[GoogleDrive](https://drive.google.com/open?id=1SqkaDPmGxs5YzKSZBHlDszaFMQZkVaJd)]       [[BaiduYunPan](https://pan.baidu.com/s/1gx6BGTEpPFgb4M8Hck8L8A)]

### Contact
  If you have any question, please contact Yufeng Wang (wyfeng@buaa.edu.cn).

### Citation
  If you find this dataset useful, please cite the following publication:
