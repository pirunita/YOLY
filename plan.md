# YOLY: Detection people and Removal #

You only look yourself(YOLY) is a system for detecting people and removing them when you take a selfie in beautiful landscape.
<br><br>
Figure)
<p align="center">
<img src="./src/1.png" width="70%" height="70%"></p>

## Plan ##
* Aug ~ Sep
    - Reading <a href="#a">reference</a> and train important paper and test.
    
    - Multiple-Human Parsing
        + Multiple-Human Parsing in the wild
        + ~~R-CNN~~ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://pirunita.dev/2019/08/23/Paperreview-R-CNN/">[review]</a> 
        + ~~Fast R-CNN~~ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://pirunita.dev/2019/08/23/Paperreview-Fast_R-CNN/">[review]</a> 
        + Faster R-CNN
        + YOLO
        + Mask R-CNN
        + Understanding Humans in Crowded Scenes: Deep Nested Adversarial Learning and A New Benchmark for Multi-Human Parsing
    
    - Image generative model based GAN
        + EdgeConnect
        + Image De-raining
        + WGAN
        + Deep-Object-Removal

* Sep ~ Nov
    - Get Dataset
    - Building 2 models(Image generative model, Multi-Human parsing)
    - Implement proposed model & prototype

* Dec
    - Model optimization
    - Serving

    
## Reference ##
<p id="a"></p>

### Image generative model ###
[1] EdgeConnect: Generative Image Inpainting with Adversarial Edge Learning <a href="https://arxiv.org/abs/1901.00212">[paper]</a> <a href="https://github.com/knazeri/edge-connect">[github]</a>

[2] Image De-raining Using a Conditional Generative Adversarial Network <a href="https://arxiv.org/abs/1701.05957">[paper]</a> <a href="https://github.com/hezhangsprinter/ID-CGAN">[github]</a>

[3] Wasserstein GAN <a href="https://arxiv.org/abs/1701.07875">[paper]</a> <a href="https://github.com/martinarjovsky/WassersteinGAN">[github]</a>

[4] Deep-Object-Removal <a href="https://github.com/VPanjeta/Deep-Object-Removal">[github]</a>

### Multi-Human Parsing ###
[1] Understanding Humans in Crowded Scenes: Deep Nested Adversarial Learning and A New Benchmark for Multi-Human Parsing <a href="https://arxiv.org/abs/1804.03287">[paper]</a>

[2] Multiple-Human Parsing in the Wild <a href="https://arxiv.org/abs/1705.07206">[paper]</a> <a href="https://github.com/ZhaoJ9014/Multi-Human-Parsing">[github]</a>
