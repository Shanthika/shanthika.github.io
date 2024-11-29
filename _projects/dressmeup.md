---
layout: page
title: Dress Anyone
description: A Method and Dataset for 3D Garment Retargeting
img: assets/gif/DMU.gif
importance: 1
category: work
---
<hr>


<div class="is-size-2 publication-authors" align="center">
    <span class="author-block">
        <a>Shanthika Naik</a>,</span>
    <span class="author-block">
        <a>Astitva Srivastava</a>,</span>
    <span class="author-block">
        <a>Kunwar Singh</a>,</span>
    <span class="author-block">
        <a>Varun Jampani</a>,</span>
    <span class="author-block">
        <a>Amit Raj</a>,</span>
    <span class="author-block">
        <a>Avinash Sharma</a></span>    

    <br>
    
</div>

<br>
<div align="center">
    <span class="link-block">
        <a href="https://arxiv.org/pdf/2401.03108.pdf"
            class="external-link button is-normal is-rounded is-dark">
            <span class="icon">
                <i class="fas fa-file-pdf"></i>
            </span>
            <span>Paper | </span>
        </a>
    </span>


    <span class="link-block">
        <a href="https://arxiv.org/pdf/2401.03108.pdf"
            class="external-link button is-normal is-rounded is-dark">
            <span class="icon">
                <i class="fas fa-file-pdf"></i>
            </span>
            <span>Supplementary | </span>
        </a>
    </span>


    <span class="link-block">
    <a href="https://shanthika.github.io/projects/dressmeup/"
        class="external-link button is-normal is-rounded is-dark">
        <span class="icon">
            <i class="fab fa-github"></i>
        </span>
        <span>Code</span>
    </a>
    </span>
</div>



<br><br>

 <img src="/assets/dressmeup/teaser.png" style="width:100% ; height:auto">
 <br><br>

 <h3>Abstract</h3>
 <p>
    3D garment retargeting for digital characters \& avatars involves non-rigid deformation of a 3D garment mesh to plausibly fit the target body mesh in a different pose. Existing neural methods for garment simulation/draping make assumption that the 3D garment is initially fitted over the 3D body, and generally require a canonicalized representation of garments, limiting them to parametric settings. In this paper, we present a novel approach to achieve 3D garment retargeting under non-parametric settings. We propose a novel isomap-based representation to first estimate robust correspondences between garment and body mesh to achieve an initial coarse retargeting, followed by a fast and efficient neural optimization, governed by Physics-based constraints. The proposed framework enables a fast inference pipeline and quick optimization for any 3D garment.

    We perform extensive experiments on publicly available datasets \& our new dataset of 3D clothing and report superior quantitative and qualitative results in comparison to SOTA methods, while demonstrating new capabilities.
 </p>


<br>
<h2>Architecture</h2> <br>
 <div align="center">
 <img src="/assets/dressmeup/arch.jpg" style="width:100% ; height:auto">
 </div>

<h4>Embedding Calculations</h4>

<p align="center">
 <img src="/assets/dressmeup/iso.mp4" style="width:100% ; height:auto">
 </p>

<hr>


<hr>
<h2>Results</h2> <br>

<hr>
<h4>Loose Garments</h4>

 <div align="center"> 
<video style="width:100%" src="/assets/dresssmeup/loose_garments.mkv" controls=""></video>
</div>

<hr>

<h4>Human Meshes</h4>

<p align="center">
 <img src="/assets/dressmeup/thuman_cloth3d.mkv" style="width:90% ; height:auto">
 </p>

<hr>

<h4>3D Bicar Charactors</h4>

<p align="center">
 <img src="/assets/dressmeup/rabit.mkv" style="width:90% ; height:auto">
 </p>

<hr>

<h4>Layered Garments</h4>

<p align="center">
<video style="width:100%" src="/assets/dressmeup/layered.mkv" controls=""></video>
</p>

<hr>

<h4>Internet Images</h4>

<p align="center">
<video style="width:100%" src="/assets/dressmeup/internet_yoga.mkv" controls=""></video>
<video style="width:100%" src="/assets/dressmeup/internet_tom.mkv" controls=""></video>
</p>

<hr>




<hr>
<h2>Comparison   </h2> <br>

<hr>
<h4>DIG</h4>

 <div align="center">
 <!-- <iframe width="560" height="315" src="/assets/video/ui.mp4" title="Video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 -->
<video style="width:100%" src="/assets/dressmeup/dig_1.mkv" controls=""></video>
<video style="width:100%" src="/assets/dressmeup/dig_2.mkv" controls=""></video>
</div>

<hr>
<h4>Drapenet</h4>

 <div align="center">
 <!-- <iframe width="560" height="315" src="/assets/video/ui.mp4" title="Video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 -->
<video style="width:100%" src="/assets/dressmeup/drapenet_1.mkv" controls=""></video>
<video style="width:100%" src="/assets/dressmeup/drapenet_2.mkv" controls=""></video>
<2div>

<h2>Our Dataset</h2>

<p align="center">
<video style="width:100%" src="/assets/dressmeup/dataset_topwear.mp4" controls=""></video>
<video style="width:100%" src="/assets/dressmeup/dataset_bottomwear.mp4" controls=""></video>
</p>

<hr>

<h3>BibTex</h3>
<pre><code>
@inproceedings{naik2022deep,
      abbr={IGARSS},
      title={Deep Generative Framework for Interactive 3D Terrain Authoring and Manipulation}, 
      author={Shanthika Naik and Aryamaan Jain and Avinash Sharma and KS Rajan},
      booktitle={IGARSS 2022 - 2022 IEEE International Geoscience and Remote Sensing Symposium},
      year={2022},
      pages={6410-6413},
      doi={10.1109/IGARSS46834.2022.9884954}
}
 </code></pre>

