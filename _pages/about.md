---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a 3rd-year M.Phil. student in Electronic and Information Engineering at SIGS, Tsinghua University(THU), supervised by [Prof. Lu Fang](http://www.luvision.net/) and [Prof. Ruiqi Huang](https://rqhuang88.github.io/). Prior to that, I spent wonderful 4 years at Southeast University(SEU), advised by [Prof. Yangang Wang](https://www.yangangwang.com/) and obtained my bachelor's degree in 2022.

**My research interests mainly lie in 2D and 3D computer vision**, especially in:
* Visual Cognition: Human-centric Visual Analysis in Complex Scenes with Gigapixel Resolution.   
* Embodied AI: Perceive, Comprehend, and Interact with the Environment through Physical Entities.   




# 🔥 News
<span class='anchor' id='news'></span>

- *2024.03*: &nbsp;🎉🎉 Our paper **DynamicTrack** is accepted by **ICME 2024** and scheduled for **Oral** presentation! 
- *2024.02*: &nbsp;🎉🎉 Our paper **GigaTraj** is accepted by **CVPR 2024**!




# 📖 Educations
<span class='anchor' id='educations'></span>

- *2022.08 - 2025.06*, M.Sc. in Electronic Information Engineering, Tsinghua University (THU), Beijing, China. 
- *2018.08 - 2022.06*, B.Sc. in Automation, Southeast University (SEU), Nanjing, China.




# 📝 Publications 
<span class='anchor' id='publications'></span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2024</div><img src='images/dynamictrack.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<b>DynamicTrack: Advancing Gigapixel Tracking in Crowded Scenes</b>
<p><b>Yunqi Zhao</b><sup>&#42;</sup>, Yuchen Guo<sup>&#42;</sup>, Zheng Cao, Kai Ni, Ruqi Huang, Fu Fang<sup>&dagger;</sup></p>
<p><i>The IEEE International Conference on Multimedia & Expo (<b>ICME</b>), 2024.</i></p>
[Paper](https://yuchy-zhao.github.io/files/DynamicTrack.pdf) / [Project Page](https://yuchy-zhao.github.io/dynamictrack)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/gigatraj.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<b>GigaTraj: Predicting Long-term Trajectories of Hundreds of Pedestrians in Gigapixel Complex Scenes</b>
<p>Haozhe Lin<sup>&#42;</sup>, Chunyu Wei<sup>&#42;</sup>, Li he<sup>&#42;</sup>, Yuchen Guo<sup>&#42;</sup>, <b>Yunqi Zhao</b>, Shanglong Li, Fu Fang<sup>&dagger;</sup></p>
<p><i>Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), 2024.</i></p>
[Paper](https://yuchy-zhao.github.io/files/GigaTraj.pdf) / [Dataset](https://gigavision.cn/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIG 2021</div><img src='images/animal3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<b>Occluded Animal Shape and Pose Estimation from a Single Color Image</b>
<p>Yiming Xie, <b>Yunqi Zhao</b>, Shijian Jiang, Jiangyong Hu, Yangang Wang<sup>&dagger;</sup></p>
<p><i>International Conference on Image and Graphics, (<b>ICIG</b>), 2021.</i></p>
</div>
</div>




# 🎖 Honors and Awards
<span class='anchor' id='honors-and-awards'></span>

* *2022*, Excellent Graduate, Southeast University.
* *2021*, Outstanding students, Southeast University.
* *2019, 2020*, National Encouragement Scholarship, the Minister of Education, China.




# 🖥️ Research Experiences
<span class='anchor' id='research-experiences'></span>

* **Pedestrian Trajectory Prediction in Gigapixel Complex Scenes**
*2023.07 – 2024.11*   
Propose a trajectory prediction dataset featuring hundreds of pedestrians in gigapixel complex scenes.       
Generate pedestrian trajectories, conduct data annotation, and perform statistical analysis.   
Mentor: [Prof. Lu Fang](http://www.luvision.net/)

* **Multi-object Tracking in Gigapixel Complex Scenes**
*2022.09 – 2023.06*    
Propose a contrastive learning-based detector for simultaneous head and body detection.    
Design a hierarchical association algorithm to utilize head and body cues for multi-object tracking.   
Mentor: [Prof. Lu Fang](http://www.luvision.net/) and [Prof. Ruqi Huang](https://rqhuang88.github.io/)




# 💡 Projects
<span class='anchor' id='personal-projects'></span>

* **Interactive General Object Grasping (Internship Program)**
*2024.04 – 2024.07*    
Develop an interactive general object grasping system for robotic applications in open-world.   
Employ SAM for interactive target localization and GraspNet for general object grasping.    
Project Page: [GraspAnything](https://yuchy-zhao.github.io/graspanything)

* **Scene Reconstruction and Understanding for Intelligent Interaction (B.S. Thesis)**
*2021.11 – 2022.08*    
Design a real-time system for indoor scene reconstruction, segmentation, and simplification.    
Develop local and global interaction patterns to improve 3D perception for visually impaired people.   
Project Page: [AutoExplore](https://yuchy-zhao.github.io/autoexplore)

* **3D Reconstruction of Animals from Single Color Images**
*2020.10 - 2021.05*   
Employ a parametric model SMAL for 3D reconstruction of animals from a  single color image.      
Predict the shape and pose parameters using the skeletal and contour information of animals.    
