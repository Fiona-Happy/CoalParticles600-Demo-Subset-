# CoalParticles600 (Demo Subset)

This repository provides a **demo subset** of the coal particle dataset described in our manuscript *CoalParticles600: Development of a Diversified Coal Particle Dataset for Image-Based Morphological Analysis*.  
During the peer-review period, we release a **representative subset for verification**; the full dataset (with complete annotations and documentation) will be released after acceptance.

> 中文说明：论文审稿阶段，本仓库仅提供**代表性 Demo 子集**，用于读者/审稿人快速验证数据组织形式与可用性；论文录用后将公开完整数据、标注与文档。

---

## Demo Overview

- **Image type:** coal particle group images (cropped patches)
- **Patch resolution:** 1024 × 1024  
- **Annotation:** generated with **SAM pre-annotation + manual refinement**
- **Particle size ranges covered in the dataset:** 1–2 mm, 1–3 mm, 2–3 mm, and >3 mm  
- **Data diversity factors (dataset design):** coal samples from four different mines, multiple size ranges, and varying particle densities

> Note: The full dataset described in the manuscript contains **600 cropped images** and **~63,000** coal particles (instance masks).  
> (This demo subset is sampled for review/verification.)

---

## Download (Demo Subset)

Google Drive link (shared by the authors):  
https://drive.google.com/file/d/11QOKnd6v_P6c7EZrod1UjqW-v8g4rTjQ/view?usp=sharing

---

## File Naming (Reference)

In the manuscript, an image naming rule is used where:  
- **Capital letter** denotes coal mine (Y/J/S/C)  
- **Lowercase letter** denotes particle size range (a/b/c/d)  
- **“1g–5g”** denotes sample weight  
- **Last digit** denotes the image index in the same group

(Your demo subset may keep the same convention or a simplified version.)

---

## License

For the review-stage demo subset: **research/verification use only**.  
A formal license and full release details will be provided upon paper acceptance.

---

## Citation

If you use this demo subset in academic work, please cite the corresponding paper (to be updated after acceptance).

```
