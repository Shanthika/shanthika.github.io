---
layout: page
permalink: /terrain_authoring/
title: Deep Generative Framework for Interactive 3D Terrain Authoring and Manipulation
description: IGARSS 2022
---

<hr>


<div class="is-size-2 publication-authors" align="center">
    <span class="author-block">
        <a href="https://shanthika.github.io">Shanthika Naik</a><sup>1</sup>,</span>
    <span class="author-block">
        <a href="https://github.com/aryamaanjain">Aryamaan Jain</a><sup>1</sup>,</span>
    <span class="author-block">
        <a href="https://3dcomputervision.github.io/about/">Avinash Sharma</a><sup>1</sup>,
    </span>
    <span class="author-block">
        <a href="https://www.iiit.ac.in/faculty/k-s-rajan/"> K S Rajan</a><sup>1</sup>,
    </span>
    <br>
    <span class="author-block"><sup>1</sup>International Institute of Information Technology Hyderabad, India</span>
</div>

<br>
<div align="center">
    <span class="link-block">
        <a href="https://arxiv.org/pdf/2201.02369.pdf"
            class="external-link button is-normal is-rounded is-dark">
            <span class="icon">
                <i class="fas fa-file-pdf"></i>
            </span>
            <span>Paper | </span>
        </a>
    </span>


    <span class="link-block">
        <a href="https://3dcomputervision.github.io/assets/pdfs/terrain_auth_supp.pdf"
            class="external-link button is-normal is-rounded is-dark">
            <span class="icon">
                <i class="fas fa-file-pdf"></i>
            </span>
            <span>Supplementary | </span>
        </a>
    </span>


    <span class="link-block">
    <a href="https://github.com/Shanthika/TerrainAuthoring-Pytorch"
        class="external-link button is-normal is-rounded is-dark">
        <span class="icon">
            <i class="fab fa-github"></i>
        </span>
        <span>Code</span>
    </a>
    </span>
</div>



<br><br>

 <img src="/assets/img/terrain_authoring.png" style="width:100% ; height:auto">
 <br><br>

 <h3>Abstract</h3>
 <p>
Automated generation and (user) authoring of realistic virtual terrain is most sought for by the multimedia applications like VR models and gaming. The most common representation adopted for terrain is Digital Elevation Model (DEM).
In this paper, we propose a novel realistic terrain authoring framework powered by a combination of VAE and generative conditional GAN model. Our framework is an example-based method that attempts to overcome the limitations of existing methods by learning a latent space from a real-world terrain
dataset. This latent space allows us to generate multiple variants of terrain from a single input as well as interpolate between terrains while keeping the generated terrains close to real-world data distribution. We also developed an interactive tool that lets the user generate diverse terrains with minimal
inputs. We perform a thorough qualitative and quantitative analysis and provide a comparison with other SOTA methods.

 </p>

<br>
 <div align="center">
 <img src="/assets/img/auth_arch.png" style="width:100% ; height:auto">
 </div>

<hr>
<h2>Applications   </h2> <br>

<hr>
<h4>Terrain Generation via Interactive UI</h4>

 <div align="center">
 <iframe width="560" height="315" src="/assets/vid/ui.mp4" title="Video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 </div>

<hr>

<h4>Terrain Variants</h4>

<p align="center">
 <img src="/assets/gif/variants.gif" style="width:90% ; height:auto">
 </p>

<hr>

<h4>Terrain Interpolation</h4>

<p align="center">
 <img src="/assets/gif/inter2.gif" style="width:90% ; height:auto">
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

