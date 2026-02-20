<p align="center">
<strong>Image-Level Domain Alignment for Real-time Underwater Crack Detection Using YOLO with an ROV</strong><br>
<small>P.C. Negue Kala, C. Viel et L. Bergantin, ICRA 2026</small>
</p>

This repository contains the validation dataset associated with P.-C. Negue-Kala et al., ICRA 2026.

The dataset consists of 175 underwater RGB images collected with a camera mounted on an ROV during field tests in a turbid lake environment. The images include examples of cracks on submerged concrete surfaces, as well as a few examples of ropes and tethers (three and one images, respectively).

All images were annotated using Roboflow in the YOLO format, including bounding boxes and segmentation masks defined with polygon coordinates. Note that manual annotations of segmentation masks are often unreliable due to low visibility and challenging image conditions. Therefore, this dataset is not suitable for evaluating segmentation metrics, but it can still be used for object detection evaluation, since object detection is less sensitive to pixel-level errors.

## Citation

If you use this dataset, please cite our paper:

```bibtex
@inproceedings{Negue-Kala2026,
  author    = {P.C. Negue Kala and C. Viel and L. Bergantin},
  title     = {Image-Level Domain Alignment for Real-time Underwater Crack Detection Using YOLO with an ROV},
  booktitle = {ICRA 2026},
  year      = {2026}
}
