---
title: "Freeway Traffic Incident Detection from Cameras: A Semi-Supervised Learning Approach"
excerpt: "We used semi-supervised techniques to detect traffic incident trajectories from the cameras. Our proposed approach for trajectory classification is based on semi-supervised parameter estimation using maximum-likelihood (ML) estimation. Results show that approximately 14% improvement in trajectory classification can be achieved using the proposed approach compared to baseline algorithms.
<br/><img src='/images/cple-image.jpg'>"
collection: portfolio
---

**Pranamesh Chakraborty**, Anuj Sharma, Chinmay Hegde

To appear in [IEEE Intelligent Systems Conference, 2018](https://www.ieee-itsc2018.org/)

![GitHub Logo](/images/cple-image.jpg)

**Abstract:** Early detection of incidents is a key step to reduce incident related congestion. State Department of Transportation (DoTs) usually install a large number of Close Circuit Television (CCTV) cameras in freeways for traffic surveillance.  In this study, we used semi-supervised techniques to detect traffic incident trajectories from the cameras. Vehicle trajectories are identified from the cameras using state-of-the-art deep learning based You Look Only Once (YOLOv3) classifier and Simple Online Realtime Tracking (SORT) is used for vehicle tracking. Our proposed approach for trajectory classification is based on semi-supervised parameter estimation using maximum-likelihood (ML) estimation. The ML based Contrastive Pessimistic Likelihood Estimation (CPLE) attempts to identify incident trajectories from the normal trajectories. We compared the performance of CPLE algorithm to traditional semi-supervised techniques Self Learning and Label Spreading, and also to the classification based on the corresponding supervised algorithm. Results show that approximately 14% improvement in trajectory classification can be achieved using the proposed approach. 

# Methodology

## Vehicle Detection and Tracking
We used YOLOv3 for vehicle detection and SORT for tracking purpose. 

<img src="/images/cple-track.png" alt="drawing" align="middle" width="400"/>

## Incident Trajectory Classification

Trajectory classification is based on semi-supervised CPLE and its accuracy is compared with baseline algorithms.

<img src="/images/cple-acc-comp.png" alt="drawing" width="400"/>


**Citation**: P. Chakraborty, A. Sharma, and C. Hegde. Freeway Traffic Incident Detection from Cameras: A Semi-Supervised Learning Approach, IEEE Conference on Intelligent Transportation Systems (ITSC), November 2018.

[Pdf](https://pranamesh.github.io/files/2018-IEEE-ITSC-draft.pdf), [Video](https://youtu.be/KhcdOXa29bo)

