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
        <a href="https://shanthika.github.io">Shanthika Naik</a><sup>1</sup>,</span>
    <span class="author-block">
        <a href="https://github.com/aryamaanjain">Astitva Srivastava</a><sup>2</sup>,</span>
    <span class="author-block">
        <a href="https://github.com/aryamaanjain">Kunwar Singh</a><sup>2</sup>,</span>
    <span class="author-block">
        <a href="https://3dcomputervision.github.io/about/">Varun Jampani</a><sup>3</sup>,</span>
    <span class="author-block">
        <a href="https://github.com/aryamaanjain">Amit Raj</a><sup>4</sup>,</span>
    <span class="author-block">
        <a href="https://www.iiit.ac.in/faculty/k-s-rajan/">Avinash Sharma</a><sup>1</sup></span>
    <br>
    <span class="author-block"><sup>1</sup>IITJ, India,</span>
    <span class="author-block"><sup>2</sup>IIITH, India,</span>
    <span class="author-block"><sup>3</sup>Stability AI,</span>
    <span class="author-block"><sup>4</sup>Google Research</span>
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

<hr>
<br>
<h3><b>Abstract</b></h3>
<hr>
<p>
3D garment retargeting for digital characters and avatars involves non-rigid deformation of a 3D garment mesh to plausibly fit the target body mesh in a different pose. Existing neural methods for garment simulation/draping make assumption that the 3D garment is initially fitted over the 3D body, and generally require a canonicalized representation of garments, limiting them to parametric settings. In this paper, we present a novel approach to achieve 3D garment retargeting under non-parametric settings. We propose a novel isomap-based representation to first estimate robust correspondences between garment and body mesh to achieve an initial coarse retargeting, followed by a fast and efficient neural optimization, governed by Physics-based constraints. The proposed framework enables a fast inference pipeline and quick optimization for any 3D garment.

We perform extensive experiments on publicly available datasets and our new dataset of 3D clothing and report superior quantitative and qualitative results in comparison to SOTA methods, while demonstrating new capabilities.
</p>
<hr>    

<br><br>
<h2><b>Methodology</b></h2>
<hr><br>

<h4><b>Architecture</b></h4>
<hr><br>
<div align="center">
<img src="/assets/dressmeup/arch.jpg" style="width:90% ; height:auto">
</div>
<hr>

<br><br>
<h4><b>Embedding Calculations</b></h4>
<hr><br>
<p align="center"> 
<video style="width:90%" src="/assets/dressmeup/iso_speed3.mkv" controls=""></video>
</p>
<hr>

<br><br>

<h2><b>Results</b> </h2>

<hr><br>
<h4><b>Loose Garments</b></h4>
<hr><br>
<p align="center"> 
<video style="width:90%" src="/assets/dressmeup/loose_garments.mkv" controls=""></video>
</p>
<hr>
<br><br>


<h4><b>Human Meshes</b></h4>
<hr><br>
<p align="center">
<video style="width:90%" src="/assets/dressmeup/thuman_cloth3d.mkv" controls=""></video>
</p>
<hr>

<br><br>
<h4><b>3D Bicar Charactors</b></h4>
<hr><br>
<p align="center">
<video style="width:90%" src="/assets/dressmeup/rabit.mkv" controls=""></video>

</p>
<hr>

<br><br>

<h4><b>Layered Garments</b></h4> 
<hr><br>
<p align="center">
<video style="width:90%" src="/assets/dressmeup/layered.mkv" controls=""></video>

</p>
<hr>

<br><br>

<h4><b>Internet Images</b></h4>
<hr><br>
<p align="center">
<video style="width:90%" src="/assets/dressmeup/internet_yoga.mkv" controls=""></video>
<video style="width:90%" src="/assets/dressmeup/internet_tom.mkv" controls=""></video>
</p>
<hr>

<br><br>
<h2><b>Comparison   </b></h2> 
<hr><br>

<h4><b>DIG</b></h4>
<hr>
<div align="center">
<video style="width:90%" src="/assets/dressmeup/dig_1.mkv" controls=""></video>
<video style="width:90%" src="/assets/dressmeup/dig_2.mkv" controls=""></video>
</div>
<hr>

<br><br>

<h4><b>Drapenet</b></h4>
<hr>
<div align="center">
<video style="width:90%" src="/assets/dressmeup/drapenet_1.mkv" controls=""></video>
<video style="width:90%" src="/assets/dressmeup/drapenet_2.mkv" controls=""></video>
</div>
<hr>

<br><br>

<h2><b>Our Dataset</b></h2>
<hr><br>
<p align="center">
<video style="width:90%" src="/assets/dressmeup/dataset_topwear.mp4" controls=""></video>
<video style="width:90%" src="/assets/dressmeup/dataset_bottomwear.mp4" controls=""></video>
</p>


<hr>
<br><br>

<h3>BibTex</h3>
<pre><code>
@inproceedings{naik2024dressmeupdatasetmethod,
      title={Dress-Me-Up: A Dataset & Method for Self-Supervised 3D Garment Retargeting}, 
      author={Shanthika Naik and Astitva Srivastava and Kunwar Singh and Amit Raj and Varun Jampani and Avinash Sharma},
      year={2024},
      eprint={2401.03108},
      archivePrefix={arXiv},
      primaryClass={cs.CV} 
}
 </code></pre>

