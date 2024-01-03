---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Transaction/Journal Paper
======
* Yonglin Tian, Xianjing Zhang, Xiao Wang, Jintao Xu, Jiangong Wang, Rui Ai, Weihao Gu, Weiping Ding. ACF-Net: Asymmetric Cascade Fusion for 3D Detection With LiDAR Point Clouds and Images[J]. IEEE Transactions on Intelligent Vehicles, 2023.
* Yonglin Tian, Xuan Li, Hui Zhang, Chen Zhao, Bai Li, Xiao Wang, Fei-Yue Wang. Vistagpt: Generative parallel transformers for vehicles with intelligent systems for transport automation[J]. IEEE Transactions on Intelligent Vehicles, 2023.
* Yonglin Tian, Jiangong Wang, Yutong Wang, Chen Zhao, Fei Yao and Xiao Wang, "Federated Vehicular Transformers and Their Federations: Privacy-Preserving Computing and Cooperation for Autonomous Driving," in IEEE Transactions on Intelligent Vehicles, 2022, 7(3), 456-465.
* Yonglin Tian, Yu Shen, Xiao Wang, Jiangong Wang, Kunfeng Wang, Weiping Ding, Zilei Wang, and Fei-Yue Wang. Learning Lightweight Dynamic Kernels With Attention Inside via Local–Global Context Fusion[J]. IEEE Transactions on Neural Networks and Learning Systems, 2022.
* Yonglin Tian, Xiao Wang, Yu Shen, Zhongzheng Guo, Zilei Wang, and Fei-Yue Wang. Parallel Point Clouds: Hybrid Point Cloud Generation and 3D Model Enhancement via Virtual–Real Integration[J]. Remote Sensing, 2021, 13(15): 2868.
* Yonglin Tian, Lichao Huang, Hui Yu, Xiangbin Wu, Xuesong Li, Kunfeng Wang, Zilei Wang, and Fei-Yue Wang. Context-Aware Dynamic Feature Extraction for 3D Object Detection in Point Clouds[J].  IEEE Transactions on Intelligent Transportation Systems, 2021, 23(8): 10773-10785.
* Yonglin Tian, Kunfeng Wang, Yuang Wang, Yulin Tian, Zilei Wang, and Fei-Yue Wang. Adaptive and azimuth-aware fusion network of multimodal local features for 3D object detection[J]. Neurocomputing, 2020, 411: 32-44.
* Yonglin Tian, Xuan Li, Kunfeng Wang, and Fei-Yue Wang. Training and testing object detectors with virtual images[J]. IEEE/CAA Journal of Automatica Sinica, 2018, 5(2): 539-546.


Conference Paper
======
* Yonglin Tian, Xiao Wang, Yu Shen, Yuhang Liu, Zilei Wang, Fei-Yue Wang. Semantic-enhanced Graph Voxelization for Pillar-based 3D Detection from Point Clouds[C]//2022 IEEE 25th International Conference on Intelligent Transportation Systems (ITSC). IEEE, 2022: 310-315.





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
