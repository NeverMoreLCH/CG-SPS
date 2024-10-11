# Compositional Substitutivity of Visual Reasoning for Visual Question Answering
Implementation for the ECCV 2024 paper "Compositional Substitutivity of Visual Reasoning for Visual Question Answering"

[paper link](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06434.pdf)

![Example Image](https://github.com/NeverMoreLCH/CG-SPS/blob/main/framework-fig.png)

<br>
<br>

## Dataset Download

![Example Image](https://github.com/NeverMoreLCH/CG-SPS/blob/main/SPS.png)

### GQA-SPS Dataset

**DownLoad Link:** 
[[Google Drive](https://drive.google.com/drive/folders/1eKcw-vj0O3bN1oo6esBgG6gdlOZ-bizl?usp=sharing)] 
[[Baidu NetDisk (password: DSPS)](https://pan.baidu.com/s/1FsRUjSxHot_lG0Kp6LaMtw)]

**Format:**

1. "gqa-sps-balanced-_X_-val-_Y_.json" is the question json for the val-_Y_ split of _X_ SPS,  where _X_ $\in$ {word, visual entity, referent}, and _Y_ $\in$ {A, B}.
2. "images_for_visual_enity_sps.zip" contains the images for "gqa-sps-balanced-visual-entity-val-A&B.json", for each image, "_image_id_.jpg" is used for model input, and "_image_id_\_hl.jpg" high lights the substituted objects.

### VQA-SPS v2 Dataset

**DownLoad Link:** 
[[Google Drive](https://drive.google.com/drive/folders/1V-WIionK0mQLiBD2x3yki2ASUXw6vuF_?usp=drive_link)]
[[Baidu NetDisk (password: DSPS)](https://pan.baidu.com/s/1PhIQsFE2bEUQzwP1LTqd-g)]

**Format:**

1. "vqav2-sps-questions-_X_-val-_Y_.json" is the question json for the val-_Y_ split of _X_ SPS,  where _X_ $\in$ {word, visual entity, referent}, and _Y_ $\in$ {A, B}.
2. "vqav2-sps-annotations-_X_-val-_Y_.json" is the annotation json for the val-_Y_ split of _X_ SPS,  where _X_ $\in$ {word, visual entity, referent}, and _Y_ $\in$ {A, B}.
3. "images_for_visual_enity_sps.zip" contains the images for "vqav2-sps-questions-visual-entity-val-A&B.json", for each image, "_image_id_.jpg" is used for model input, and "_image_id_\_hl.jpg" high lights the substituted objects.
