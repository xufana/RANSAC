# NDT-RANSAC implementation for 3D-pointcloud segmentation

[![University: HSE](https://img.shields.io/badge/University-HSE-blue?&style=for-the-badge)](https://www.hse.ru/)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

This project is an implementation of [Li, L., Yang, F., Zhu, H., Li, D., Li, Y., & Tang, L. (2017). An Improved RANSAC for 3D Point Cloud Plane Segmentation Based on Normal Distribution Transformation Cells. Remote Sensing, 9(5), 433. doi:10.3390/rs9050433](https://www.researchgate.net/publication/316697320_An_Improved_RANSAC_for_3D_Point_Cloud_Plane_Segmentation_Based_on_Normal_Distribution_Transformation_Cells) as a part of the second year coursework.

---

It does not work with Google Colab, so use Jupiter Notebook or just something else.

---
## Results

The results completely depend on the pointcloud you have. The one I had tested on had a mirror reflection and bad light spot. Somewhere it was chunky, but in general it worked good with the less noisy parts.

Pointcloud I had:
![Cells](https://github.com/xufana/RANSAC/blob/master/photo_2020-06-27_22-08-23.jpg)

Meshes I had got before fine-tuning and piece combining
![Meshes](https://github.com/xufana/RANSAC/blob/master/photo_2020-06-27_22-10-32.jpg)

After the piece combining. Orange mesh is a celling, green one is a floor.
![Floor and Celling](https://github.com/xufana/RANSAC/blob/master/photo_2020-06-28_22-28-38.jpg)

One more 3D picture of the mesh.
![???](https://github.com/xufana/RANSAC/blob/master/photo_2020-06-28_22-29-53.jpg)
