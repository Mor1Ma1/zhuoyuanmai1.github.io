---
layout: page
title: Soft Machine
description: 
img: assets/img/softmachine/4x/1.webp
importance: 2
year: 2021
---

As Technology develops by leaps and bounds, artificial intelligence is beginning to show the same way of thinking as a human being, with a process based on big data. I can't help wondering if AI perceives clothing in the same way as humans do.

The aim of this project is to create a perceptual match scoring system for clothing,which calculates from subjective perception to objective evaluation. Another point is to create a textile-specific neural networks database to streamline the pattern collection and generation process.

<div class="row">
    <div class="col-12">
        <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/3_ddmO2WKLU?si=hsbRwVSwM7Uh0dgu" allowfullscreen></iframe>
        </div>
    </div>
</div>

---

### Gallery

---

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/2.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

### Research

---

<h4>
    <br>
    Inspiration
</h4>

<p>
    <br>
    Relying on a huge database, artificial intelligence has gradually built up the perception of fabric style. So when matching face information with clothing information on a one-to-one basis, can AI analyze the degree of matching between them, and are the results the same as human analysis?
</p>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/3.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>
    <br>
    <a href="https://en.wikipedia.org/wiki/Kansei_engineering" target="_blank">Kansei Engineering</a>
</h4>

<p>
    <br>
    Kansei engineering (emotional or affective engineering) aims at the development or improvement of products and services by translating the customer's psychological feelings and needs into the domain of product design (i.e. parameters). 
</p>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/4.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/5.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>
    It was founded by Mitsuo Nagamachi, Professor Emeritus of Hiroshima University Kansei engineering parametrically links the customer's emotional responses (i.e. physical and psychological) to the properties and characteristics of a product or service. <br><br>
    In consequence, products can be designed to bring forward the intended feeling.
</p>

<h4>
    <br>
    <a href="https://en.wikipedia.org/wiki/Generative_adversarial_network" target="_blank">GANS</a>
</h4>

<p>
    <br>
    The Generative Adversarial Neural Network (GAN) architecture, introduced by Goodfellow et al., is a machine learning model that can be used to generate images of fabric with specific styles and patterns. <br><br>
    This architecture allows researchers in the field of textiles to use self-defined datasets to predict and generate images of various fabrics, making it a useful tool for research and development in multiple areas. <br><br>
    GANs can be trained on a wide range of datasets, allowing for the creation of highly realistic images that can be used for various purposes, such as design, analysis, and evaluation.
</p>

<!-- 一行一张图,5/6大小,水平居中 -->
<div class="row justify-content-center">
    <div class="col-10">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/6.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p>
    <br>
    The Frict GAN architecture, proposed by Cai et al., is a neural network-based approach for recognizing fabric texture images and simulating haptic signals associated with the surface of fabric materials. The neural network processes information about fabric smoothness and generates displacement data and amplitude spectra of fabric friction coefficients. These generated haptic signals can be used in haptic feedback studies to better understand the tactile properties of fabric materials.<br><br>
    In the context of fabric materials, haptic feedback can be used to study the way that fabrics feel to the touch and how they respond to different forces and stimuli. By simulating haptic signals with the Frict GAN architecture, researchers can gain a better understanding of the tactile properties of different fabrics and potentially use this information to design materials with desired haptic properties.
</p>

<!-- 一行一张图,5/6大小,水平居中 -->
<div class="row justify-content-center">
    <div class="col-10">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/7.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>
    <br>
    Sketch
</h4>

<p>
    <br>
    As for the medium to realize the project, I decide to make use of multi-screens and design a viusal panel which can turn data into visual language and depict different properties on the screens.
</p>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/8.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

### Physical Experiment

---

<h4>
    <br>
    Sample Selection
</h4>

<p>
    <br>
    With cooperation of the FDC Fabric Centre (affiliated to BIFT), I selected 25 types of fabric as original samples.<br><br>Samples are selected according to the following seven properties: 
    color, material, thickness, fluffiness, softness, roughness and texture.
</p>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/9.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>
    <br>
    Questionnaire
</h4>

<!-- 一行分割为两栏,左边为垂直居中对齐的文本,右边为图像 -->
<div class="row">
    <div class="col-sm-4" style="display: flex; align-items: center;">
        <div style="text-align: left;">
            <p>
                <br>
                Based on the listed properties, I conducted a questionare survey entitled Are These Good Fabrics to analyze the subjective fabric style. <br><br>
                20 experimenters involved, 
                including 10 males and 10 females.<br><br>
                After arithmetic meaning the results, 
                the diagram is on the right side.<br><br>
                The results of the collection would be used in the subsequent search for potential factors and to complete the correlation between subjective perception and objective fabric attributes.
            </p>
        </div>
    </div>
    <div class="col-sm-8">
    {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/10.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/11.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- 小字,可以往里写描述 -->
<div class="caption">
    Cross Analysis
</div>

<h4>
    <br>
    Physics Analysis
</h4>

<p>
    <br>
    Apart from subjective survey, objective measurement is also important. Seven analytical methods were applied to measure the listed properties.
</p>

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/12.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>
    <br>
    Conclusion
</h4>

<p>
    <br>
    Above all the experiments, the best fit is for the subjective and objective thickness and roughness tests, indicating a strong correlation between the subjective perception of thickness and roughness and the actual nominal thickness and roughness of the fabric samples.<br><br>
    The subjective and objective data of the fluffiness, stiffness and texture analyses are more discrete than for the thickness and roughness experiments, indicating a discrepancy between the testing and statistical methods and the subjective style perceptions.<br><br>
    The correlation between the subjective factors of samples means that people's evaluation on fabric styles is the result of the interaction of different factors.<br><br>
    The subjective factors of the fabric samples correlate to some extent with the trend of the objective attributes with the change in sample number, especially the good fit between the subjective perception of thinness and roughness and the actual nominal thickness and roughness, indicating that the sample attributes influence people's subjective style perception of the fabric.
</p>

---

### Computational Experiment

---

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/13.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

### Visual Development

---

<!-- 一行一张图 -->
<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/softmachine/4x/14.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>