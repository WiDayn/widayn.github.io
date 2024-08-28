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

I am an undergraduate student studying at College of Computer Science and Software Engineering(计算机与软件学院),  Hohai University([河海大学](https://en.wikipedia.org/wiki/Hohai_University)).

My major is Computer Science and Technology(计算机科学与技术), with an average course grade of 87.78/100. 

I primarily worked under the guidance of Prof. JunFeng Jiang on medical image processing. I participated in several projects and tasks at the ChangZhou Key Laboratory of Digital Technology on Graphics and Orthopaedic implants([常州市图形图像与骨科植入物数字化技术重点实验室](https://dtgoi.hhu.edu.cn/main.htm)) and SuZhou Institute of Biomedical Engineering and Technology Chinese Academy of Sciences([中国科学院苏州生物医学工程技术研究所]("https://sibet.cas.cn/")). My work involved 3D/2D registration, object detection, and image segmentation.

I was involved in three College Students’ Innovation Program projects, one of which was at the national level and two at the university level. During my time at the university, I received multiple university-level scholarships.

In terms of competitions, I have won two national-level award, two provincial-level award, and several university-level awards.

# 🔥 News
[^_^]: #- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Projects
- *2024.07* Fraud APP intelligent identification and analysis system

![](/images/cnsoft_1.png){:width="400px" style="display: block; margin: auto"}

We developed a comprehensive system for analyzing fraudulent applications, utilizing the Vue+SpringBoot architecture. My primary focus was on APK analysis, where I implemented dynamic analysis using emulator tools and MITMProxy. Additionally, I employed JADX and Selenium to facilitate APK download and static parsing. Moreover, I actively contributed to the design of the system architecture, as well as its overall integration and coordination.
- *2024.04(Now Working, Cooperating with NEAU)* Field-Road Classification Based on Pixel Mapping

![](/images/wheat_prediction.png){:width="300px" style="display: block; margin: auto"}

We proposed a precision farmland road segmentation algorithm based on Swin-Unet, aiming to achieve accurate classification of field roads and support real-time visualization with satellite maps. Through steps such as data filtering, image mapping, and Swin-Unet pixel-level classification, this method effectively integrates detailed statistical features of each GNSS point with visual features, thereby improving the accuracy and reliability of traditional farmland road segmentation methods that rely solely on visual information. Experimental results demonstrate that this algorithm achieves promising results in segmentation tasks.

- *2024.04* CT Lumbar Spine Segmentation with nnU-Net

![](/images/ct_lumbar_segmentation_1.png){:width="300px" style="display: block; margin: auto"}

We developed a CT lumbar spine segmentation approach using nnU-Net, focusing on a level of detail not found in current datasets. By annotating nine datasets to differentiate each part within the vertebrae—unlike existing datasets that segment the vertebral body as a whole—my work supports more accurate surgical planning for procedures such as pedicle screw fixation, leading to safer and more precise interventions.

- *2024.03(Under Review)* ABLSpineLevelCheck: Localization of Vertebral Levels on Fluoroscopy via Semi-supervised Abductive Learning

![](/images/Localization_fig1.jpg){:width="400px" style="display: block; margin: auto"}

Deep learning has demonstrated promising efficacy in the localization of vertebrae within X-ray imagery, although it is recognized for its deficiencies in compositional generalization, data efficiency, and interpretability. To address this issue, we introduce an abductive learning mechanism, situated within the neuro-symbolic paradigm, tailored for semi-supervised vertebral localization. Initially, unannotated spinal fluoroscopic images are processed by the networks to infer pseudo-labels for vertebra localization. Subsequently, these pseudo-labels undergo abductive reasoning via a knowledge base comprised of first-order logical clauses. The networks are then retrained utilizing the abducted outcomes. Additionally, we propose an ensemble technique that amalgamates semantic detection of vertebral levels with instance detection. To further augment performance, we have synthesized a dataset and annotated the BUU dataset for network pretraining. Ablation studies validate the efficacy of the proposed components in our methodology. Furthermore, comparative analyses reveal that our approach significantly surpasses leading object detection algorithms, exhibiting superior performance with minimal annotations.

- *2023.12* Tibial Midline Recognition Technology Based on U-Net

![](/images/u-net-architecture.png){:width="300px" style="display: block; margin: auto"}

![](/images/tibia-segmentation.png){:width="300px" style="display: block; margin: auto"}

We employed the SAM model for simple annotation of the existing dataset and utilized U-Net for training and prediction. To obtain the tibial midline, we connected the midpoint at the top of the mask with the midpoint of the middle segment. The actual algorithm demonstrated good robustness and recognition performance on the dataset.

- *2023.09* Intraoperative X-Ray Image Vertebrae Symbolic Reasoning Recognition

![](/images/x-ray-logic.png){:width="400px" style="display: block; margin: auto"}

![](/images/x-ray-logic-2.png){:width="400px" style="display: block; margin: auto"}

Our method combines visual object detection with first-order logic predicate reasoning, effectively improving the recognition rate of vertebral bodies through logical reasoning. The results obtained are more interpretable compared to those from object detection alone. The logic part can be divided into two sections: facts and inferences. The facts are directly derived from object detection, while inferences are automatically generated by a reasoning engine constructed in the Prolog language. The facts we construct come from the results of object detection, and the conclusions are derived directly from these facts.

- *2023.06* Intelligent Recognition and Retrieval System for Medical Documents

![](/images/yizhigu-1.png){:width="400px" style="display: block; margin: auto"}

The system is based on the Spring Boot and Vue frameworks, incorporating numerous technologies such as WebSocket, Redis caching, RabbitMQ message queuing, and Elasticsearch distributed searching. The purpose is to facilitate document verification, retrieval, automatic archiving, and functions such as Optical Character Recognition (OCR) from images, text classification (BERT), and translation (openNMT). I am primarily responsible for the construction of the front-end and back-end, as well as the deployment of the entire project.

- *2023.03* Intelligent River Digital Twin Practice Based on WISE-PaaS Cloud

![](/images/wise-paas.png){:width="400px" style="display: block; margin: auto"}

The project is based on the Advantech WISE-PaaS Industrial IoT Cloud platform and focuses on the study of digital twins for intelligent rivers. It aims to monitor and assess target rivers in real-time, ultimately establishing a platform for real-time monitoring and assessment of intelligent rivers.

# 🎖 Honors and Awards
- *2024.08* 13th China Software Cup, 3rd Prize.
- *2024.05* 15th LanQiao Cup Jiangsu Province Competition Region, 1rd Prize.
- *2023.09* 2022-2023 Hohai University Scholarship for Academic Progress.
- *2023.07* The 14th China College Student Service Outsourcing Innovation and Entrepreneurship Competition([中国大学生服务外包创新创业大赛](http://www.fwwb.org.cn/)), 3rd Prize.
- *2023.05* The 2023 ICPC Jiangsu Provincial Programming Contest, Bronze Prize. 
- *2022.09* 2021-2022 Hohai University Scholarship for Academic Progress.
- *2022.05* The 22th Hohai University Algorithm Design Creativity Show, 1rd Prize.
- *2021.12* The 10th Hohai University Programming Contest, 1rd Prize. 

# 📖 Educations
- *2021.09 - 2025.06 (now)*, College of Computer Science and Software Engineering, Hohai University. 
- *2018.09 - 2021.06*, Guangdong Overseas Chinese High School, GuangZhou.


# 💻 Internships
- *2024.06 - 2025.04 (now)*, SuZhou Institute of Biomedical Engineering and Technology Chinese Academy of Sciences[(中国科学院苏州生物医学工程技术研究所)](https://sibet.cas.cn/), China.