---
permalink: /
title: ""
excerpt: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## 👋 About Me
I am Tian Ye, a PhD student at [ROAS Thrust](https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/systems-hub/robotics-and-autonomous-systems/)@HKUST, Guangzhou. I am fortunate to be supervised by [Prof. Lei Zhu](https://sites.google.com/site/indexlzhu/home) and [Prof. Kan, Ge Lin](https://repository.hkust.edu.hk/ir/AuthorProfile/kan-ge-lin). During my undergraduate studies, I had the honor of being supervised by and collaborating with **Prof. Erkang Chen** and **Prof. Yun Liu**. Previously, I worked closely with [Dr. Hongwei Yi](https://xyyhw.top/) (Head of Research@[Hedra](https://www.hedra.com/)) to explore and develop Foundational Video Generation Models (e.g., [Magic 1-For-1](https://magic-141.github.io/Magic-141/), [MagicInfinite](https://magicinfinite.github.io)).

<div id="motto" class="typed-motto"></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  if (typeof Typed !== 'undefined') {
    new Typed('#motto', {
      strings: ["Exploring this world, pursuing research that's fun and meaningful."],
      typeSpeed: 50,
      backSpeed: 30,
      loop: true,
      startDelay: 1000,
      showCursor: true,
      cursorChar: ''
    });
  } else {
    var script = document.createElement('script');
    script.src = 'https://cdn.jsdelivr.net/npm/typed.js@2.0.12';
    script.onload = function() {
      new Typed('#motto', {
        strings: ["Exploring this world, pursuing research that's fun and meaningful."],
        typeSpeed: 50,
        backSpeed: 30,
        loop: true,
        startDelay: 1000,
        showCursor: true,
        cursorChar: ''
      });
    };
    document.head.appendChild(script);
  }
});
</script>

<style>
.typed-motto {
    font-style: italic;
    font-size: 24px;
    margin: 20px 0;
    min-height: 36px;
    background: -webkit-linear-gradient(left, #1772d0, #6c5ce7);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-family: 'Georgia', serif;
    font-weight: 500;
    text-align: center;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
}

.typed-cursor {
    color: #1772d0;
    font-weight: bold;
}
</style>

## 🔬 Research Interests
<div class="research-areas">
    My research focuses on two key areas:

    <div class="research-item" data-tooltip="ICLR'25 Meissonic, IJCAI'24, Magic 1-For-1, MagicInfinite">
        <div class="research-icon">🎨</div>
        <div class="research-content">
            <h3>AIGC Technology</h3>
            <p>Supporting the art creation industry and digital asset generation through advances in AIGC (Artificial Intelligence Generated Content) technology</p>
        </div>
    </div>

    <div class="research-item" data-tooltip="ECCV'22&24,ICCV'23,CVPR'24,AAAI'23&25,IJCV'24,NeurIPS'24">
        <div class="research-icon">📸</div>
        <div class="research-content">
            <h3>Visual Quality</h3>
            <p>Exploring visual challenges in photography to create images with superior quality.</p>
        </div>
    </div>
</div>


# 📰 News
<!-- <div class="news-container"> -->
- [2025-06] 3 Papers are accepted by ICCV 2025.
- [2025-06] We are pleased to announce the release of [PosterCraft](https://ephemeral182.github.io/PosterCraft/)! A Unified Framework for High-Quality Aesthetic Poster Generation.
- [2025-03] We are pleased to announce the release of [MagicInfinite](https://magicinfinite.github.io) (Character-3 Model of Hedra Inc.). Now you can fastly generate infinite talking videos with your words and voice!
- [2025-02] 3 Papers are accepted by CVPR 2025.
- [2025-02] We are pleased to announce the release [Magic 1-For-1](https://magic-141.github.io/Magic-141/), a SOTA, *4-step image-to-video diffusion model*, along with our technical report.
- [2025-01] I am honored to be selected as a speaker at [KAUST Rising Stars in AI Symposium 2025](https://www.kaust.edu.sa/en/news/rising-stars-in-ai-symposium-2025)!! Thank you KAUST for the opportunity!
- [2025-01] Meissonic is accepted by ICLR 2025🎉.
- [2024-12] 4 Papers are accepted by AAAI 2025.
- [2024-11] I am honored to be selected as a Outstanding Reviewer for BMVC 2024！
- [2024-11] We release Meissonic on HuggingFace🎉, Meissonic-1B is the first SDXL level, high-resolution non-AR T2I model!!
- [2024-09] 2 Papers are accepted by ECCV 2024.
- [2024-06] 2 Papers are accepted by MICCAI 2024, and Segmamba is selected as a Spotlight presentation paper.

<!-- </div> -->


# 📝 Selected Papers

<style type="text/css">
    /* Color scheme stolen from Sergey Karayev */
    a {
        color: #1772d0;
        text-decoration:none !important;
    }
    a {
    color: #1772d0;
    text-decoration:none !important;
    }
    a:focus, a:hover {
    color: #f09228;
    text-decoration:none !important;
    }
    table,td,th,tr{
    	border:none !important;
    }
    body,td,th,tr,p,a {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px
    }
    strong {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    }
    heading {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 22px;
    }
    papertitle {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700
    }
    papertitle_just {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700;
    text-align: justify
    }
    name {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 32px;
    }
    .one
    {
    width: 160px;
    height: 160px;
    position: relative;
    }
    .two
    {
    width: 160px;
    height: 160px;
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
    .fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
    span.highlight {
        background-color: #ffffd0;
    }


  .research-areas {
      background: #f8f9fa;
      padding: 25px;
      border-radius: 12px;
      margin: 20px 0;
  }

  .research-item {
      background: white;
      padding: 20px;
      margin: 15px 0;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      display: flex;
      align-items: flex-start;
      transition: all 0.3s ease;
      transform-origin: center;
  }

  /* 鼠标悬停效果 */
  .research-item:hover {
      transform: scale(1.03);
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      background: #fafafa;
  }

  .research-icon {
      font-size: 24px;
      margin-right: 15px;
      transition: transform 0.3s ease;
  }

  /* 图标动画效果 */
  .research-item:hover .research-icon {
      transform: scale(1.2) rotate(5deg);
  }

  .research-content {
      flex: 1;
  }

  .research-content h3 {
      margin: 0 0 10px 0;
      font-size: 1.2em;
      color: #333;
      transition: color 0.3s ease;
  }

  /* 标题颜色变化效果 */
  .research-item:hover .research-content h3 {
      color: #1772d0;
  }

  .research-content p {
      margin: 0;
      color: #666;
      line-height: 1.5;
      transition: color 0.3s ease;
  }

  /* 文字颜色变化效果 */
  .research-item:hover .research-content p {
      color: #333;
  }




  /* 添加tooltip样式 */
  .research-item {
      position: relative;
  }

  .research-item::after {
      content: attr(data-tooltip);
      position: absolute;
      bottom: 100%;
      left: 50%;
      transform: translateX(-50%);
      padding: 8px;
      background-color: rgba(0, 0, 0, 0.8);
      color: white;
      border-radius: 6px;
      font-size: 14px;
      white-space: nowrap;
      opacity: 0;
      visibility: hidden;
      transition: all 0.3s ease;
      z-index: 1000;
  }

  .research-item:hover::after {
    opacity: 1;
    visibility: visible;
    bottom: calc(100% + 10px);
}

  /* 添加箭头 */
  .research-item::before {
      content: '';
      position: absolute;
      bottom: 100%;
      left: 50%;
      transform: translateX(-50%);
      border: 6px solid transparent;
      border-top-color: rgba(0, 0, 0, 0.8);
      opacity: 0;
      visibility: hidden;
      transition: all 0.3s ease;
  }

  .research-item:hover::before {
      opacity: 1;
      visibility: visible;
      bottom: calc(100% + 4px);
  }


</style>


<tbody>




<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://www.hedra.com/">
   [🔥Talking Avatar Model🔥] <papertitle_just>🔥🔥🔥MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice </papertitle_just>     
  </a>
  <br>
Hongwei Yi*, <strong>Tian Ye*</strong>, Shitong Shao*, Xuancheng Yang*, Jiantong Zhao*, Hanzhong Guo*, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou

<br>
<em>Arxiv </em> 2025<br>
<a href="https://arxiv.org/abs/2503.05978">PDF</a>
|
<a href="https://magicinfinite.github.io/">Project</a>
|
<a href=""><em>Character-3 Model of Hedra Inc.</em></a>

<details class="video-demo">
    <summary class="video-button">▶️ Watch Demo</summary>
    <div class="video-container">
      <video controls width="100%">
        <source src="images/magicinfinite_main.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </details>


<p> </p>
</td>


<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://sites.google.com/view/meissonic/home?authuser=0">
   [Foundational Generation Model]<papertitle_just>Meissonic: Revitalizing Masked Generative Transformers for Efficient High-Resolution Text-to-Image Synthesis</papertitle_just>     
  </a>
  <br>
Jinbin Bai*, <strong>Tian Ye*</strong>, Wei Chow, Enxin Song, Qing-Guo Chen, Xiangtai Li, Zhen Dong, Lei Zhu, Shuicheng Yan
<br>
<em>ICLR </em> 2025 <span style="color:red;">The first SDXL Level, High-Resolution Non-AR T2I Model.</span> <br>
<a href="https://arxiv.org/abs/2410.08261">PDF</a>
|
<a href="https://huggingface.co/MeissonFlow/Meissonic">HF Model</a>

<p> </p>
</td>



<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://aglldiff.github.io">
   [Generative Image Enhancement] <papertitle_just> AGLLDiff : Guiding Diffusion Models Towards Unsupervised Training-free Real-world Low-light Image Enhancement </papertitle_just>     
  </a>
  <br>
Yunlong Lin*, <strong>Tian Ye*</strong>, Sixiang Chen*, Zhenqi Fu, Yingying Wang, Wenhao Chai, Zhaohu Xing, Lei Zhu and Xinghao Ding
<br>
<em>AAAI </em> 2025  <br>
<a href="https://arxiv.org/pdf/2407.14900">PDF</a>
|
<a href="https://aglldiff.github.io">Project</a>
<p> </p>
</td>


<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://aglldiff.github.io">
   [Real-world Restoration] <papertitle_just> PromptHaze: Prompting Real-world Dehazing via Depth Anything Model </papertitle_just>     
  </a>
  <br>
<strong>Tian Ye</strong>, Sixiang Chen, Haoyu Chen, Wenhao Chai, Jingjing Ren, Zhaohu Xing, Wenxue Li, Lei Zhu
<br>
<em>AAAI </em> 2025  <br>
<p> </p>
</td>




<!-- <td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://aglldiff.github.io">
   [Generative Image Restoration] <papertitle_just> Residual Diffusion Deblurring Model for Single Image Defocus Deblurring </papertitle_just>     
  </a>
  <br>
  Haoxuan feng, Haohui Zhou, <strong>Tian Ye</strong>, Sixiang Chen, Lei Zhu
<br>
<em>AAAI </em> 2025  <br>
<p> </p>
</td> -->


<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://github.com/Ephemeral182/ECCV24_T3-DiffWeather">
   [Generative Image Restoration] <papertitle_just> Teaching Tailored to Talent: Adverse Weather Restoration via Prompt Pool and Depth-Anything Constraint</papertitle_just>     
  </a>
  <br>
Sixiang Chen, <strong>Tian Ye</strong>, Kai Zhang, Zhaohu Xing, Yunlong Lin, and Lei Zhu
<br>
<em>ECCV </em> 2024  <br>
<a href="https://arxiv.org/pdf/2409.15739">PDF</a>
|
<a href="https://ephemeral182.github.io/T3-DiffWeather/">Project</a>
|
<a href="https://github.com/Ephemeral182/ECCV24_T3-DiffWeather">code</a>
<p> </p>
</td>




<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="">
   [Video Restoration] <papertitle_just> Triplane-Smoothed Video Dehazing with CLIP-Enhanced Generalization</papertitle_just>     
  </a>
  <br>
Jingjing Ren, Haoyu Chen, <strong>Tian Ye</strong>, Hongtao Wu and Lei Zhu
<br>
<em>IJCV </em> 2024  <br>
<a href="https://link.springer.com/article/10.1007/s11263-024-02161-0">PDF</a>
<p> </p>
</td>



<td width="20%">

<script type="text/javascript">

</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/abs/2401.13560">
    [Medical Image Seg] <papertitle_just> SegMamba: Long-range Sequential Modeling Mamba For 3D Medical Image Segmentation</papertitle_just>     
  </a>
  <br>
Zhaohu Xing,  <strong>Tian Ye</strong>, Yijun Yang, Guang Liu and Lei Zhu
<br>
<em>MICCAI </em> 2024 <span style="color:red;"> Selected as a Spotlight presentation paper (about 20 of 2,869 valid submissions) and  Early Accepted by MICCAI. Don't need rebuttal!</span> <br>
<a href="https://arxiv.org/pdf/2401.13560">PDF</a>
|
<a href="https://github.com/ge-xing/SegMamba">code</a>
<p> </p>
</td>


<td width="20%">
<!-- <div class="one"> -->
<!-- <div class="two" id = 'submit23__image'><img src='./files/submit23_after.png'></div>
<img src='./files/submit23_before.png'> -->
<!-- </div> -->
<script type="text/javascript">
// function submit23__start() {
// document.getElementById('submit23__image').style.opacity = "1";
// }
// function submit23__stop() {
// document.getElementById('submit23__image').style.opacity = "0";
// }
// submit23__stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Ye_Learning_Diffusion_Texture_Priors_for_Image_Restoration_CVPR_2024_paper.pdf">
    [Generative Model For IR] <papertitle_just> Learning Diffusion Texture Priors for Image Restoration</papertitle_just>     
  </a>
  <br>
<strong>Tian Ye</strong>, Sixiang Chen, Wenhao Chai, Zhaohu Xing, Jing Qin, Ge Lin, Lei Zhu.
<br>
<em>CVPR Highlight </em> 2024 <span style="color:red;">Selected as a Highlight presentation paper (324 of 11,532 valid submissions).</span><br>

<a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Ye_Learning_Diffusion_Texture_Priors_for_Image_Restoration_CVPR_2024_paper.pdf">PDF</a>
|
<a href="https://owen718.github.io/files/CVPR2024_Poster_DTPM.pdf">CVPR Poster</a>
<p></p>
</td>




<!-- ###################################################################################################-->
<!-- Paper V -->
<!-- <tr onmouseout="submit23__stop()" onmouseover="submit23__start()" > -->
<td width="20%">
<!-- <div class="one"> -->
<!-- <div class="two" id = 'submit23__image'><img src='./files/submit23_after.png'></div>
<img src='./files/submit23_before.png'> -->
<!-- </div> -->
<script type="text/javascript">
// function submit23__start() {
// document.getElementById('submit23__image').style.opacity = "1";
// }
// function submit23__stop() {
// document.getElementById('submit23__image').style.opacity = "0";
// }
// submit23__stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/pdf/2312.08606.pdf">
    [Generative Model For IR]<papertitle_just> VQCNIR: Clearer Night Image Restoration with Vector-Quantized Codebook</papertitle_just>     
  </a>
  <br>
Wenbin Zou, Hongxia Gao, <strong>Tian Ye</strong>, Liang Chen, Weipeng Yang, Shasha Huang, Hongsheng Chen, Sixiang Chen
<br>
<em>AAAI</em> 2024 <br>
<a href="https://arxiv.org/pdf/2312.08606.pdf">PDF</a>
|
<a href="https://github.com/AlexZou14/VQCNIR">Code</a>
<p></p>
</td>




<!-- ###################################################################################################-->
<!-- Paper V -->
<!-- <tr onmouseout="submit23__stop()" onmouseover="submit23__start()" > -->
<td width="20%">

<script type="text/javascript">
// function submit23__start() {
// document.getElementById('submit23__image').style.opacity = "1";
// }
// function submit23__stop() {
// document.getElementById('submit23__image').style.opacity = "0";
// }
// submit23__stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Chen_Sparse_Sampling_Transformer_with_Uncertainty-Driven_Ranking_for_Unified_Removal_of_ICCV_2023_paper.html">
    [Image Restoration]<papertitle_just> Sparse Sampling Transformer with Uncertainty-Driven Ranking for Unified Removal of Raindrops and Rain Streaks </papertitle_just>     
  </a>
  <br>
Sixiang Chen*,<strong>Tian Ye*</strong>, Jinbin Bai, Jun Shi, Erkang Chen, Lei Zhu.
  <br>
<em>ICCV</em> 2023 <br>
<a href="https://openaccess.thecvf.com/content/ICCV2023/html/Chen_Sparse_Sampling_Transformer_with_Uncertainty-Driven_Ranking_for_Unified_Removal_of_ICCV_2023_paper.html">PDF</a>
|
<a href="https://github.com/Owen718/UDR-S2Former_deraining">Code</a>
|
<a href="https://ephemeral182.github.io/UDR_S2Former_deraining/">Project</a>
<p></p>
</td>



<td width="20%">
<script type="text/javascript">
// function submit23__start() {
// document.getElementById('submit23__image').style.opacity = "1";
// }
// function submit23__stop() {
// document.getElementById('submit23__image').style.opacity = "0";
// }
// submit23__stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Ye_Adverse_Weather_Removal_with_Codebook_Priors_ICCV_2023_paper.html">
   [Generative Model For IR]<papertitle_just> Adverse Weather Removal with Codebook Priors </papertitle_just>     
  </a>
  <br>
<strong>Tian Ye*</strong>, Sixiang Chen*, Jinbin Bai*, Shi Jun, Chenghao Xue, Jingjia Jiang, Junjie Yin, Erkang Chen, Yun Liu.
  <br>
<em>ICCV</em> 2023 <br>
<a href="https://openaccess.thecvf.com/content/ICCV2023/html/Ye_Adverse_Weather_Removal_with_Codebook_Priors_ICCV_2023_paper.html">PDF</a>
|
<a href="">Code</a>
<p></p>
</td>

<!-- Paper V  -->
<!-- ###################################################################################################-->
  






<!-- <td width="20%">
<script type="text/javascript">
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/abs/2306.17201">
    <papertitle_just>MPM: A Unified 2D-3D Human Pose Representation via Masked Pose Modeling </papertitle_just>     
  </a>
  <br>
Zhengyu Zhang, Wenhao Chai, Zhongyu Jiang, <strong>Tian Ye</strong>, Mingli Song, Jenq-Neng Hwang, Gaoang Wang 
  <br>
<em>Under Review.</em> 2023 <br>
<a href="https://arxiv.org/abs/2306.17201">PDF</a>
|
<a href="https://github.com/vvirgooo2/MPM">code</a>
<p>Treat 2D and 3D pose as two different modalities and apply three mask modeling based pretext tasks for human pose pre-training to learn spatial and temporal relations.</p>
</td>
 -->

<!-- ###################################################################################################-->
<!-- Paper V -->
<!-- <tr onmouseout="submit23__stop()" onmouseover="submit23__start()" > -->
<td width="20%">

</td>
<td valign="top" width="80%">
  <a href="">
    [Image Restoration]<papertitle_just> Uncertainty-Driven Dynamic Degradation Perceiving and Background Modeling for Efficient Single Image Desnowing</papertitle_just>     
  </a>
  <br>
SiXiang Chen*, <strong>Tian Ye*</strong>, Chenghao Xue, Haoyu Chen, Yun Liu, Erkang Chen, Lei Zhu
  <br>
<em>ACM Multimedia (ACM MM) </em> 2023 <br>
<a href="">PDF</a>
|
<a href="">Code</a>
<p></p>
</td>


<!-- Paper V  -->
<!-- ###################################################################################################-->
  


<!-- ###################################################################################################-->
<!-- Paper V -->
<!-- <tr onmouseout="submit23__stop()" onmouseover="submit23__start()" > -->
<td width="20%">

<script type="text/javascript">
// function submit23__start() {
// document.getElementById('submit23__image').style.opacity = "1";
// 
</script>
</td>
<td valign="top" width="80%">
  <a href="https://link.springer.com/chapter/10.1007/978-3-031-19800-7_8">
    [Image Restoration]<papertitle_just> Perceiving and Modeling Density for Image Dehazing</papertitle_just>     
  </a>
  <br>
  <strong>Tian Ye*</strong>, Yunchen Zhang*, Mingchao Jiang*, Liang Chen, Yun Liu, Erkang Chen. 
  <!-- <strong>Yeying Jin</strong>, Ruoteng Li, Wenhan Yang, Robby T. Tan
   -->
  <br>
<em>ECCV Oral</em>, 2022. <span style="color:red;">Selected as a Oral presentation paper (Top 2.7%, 158 of 5,803 valid submissions).</span><br>
<a href="https://link.springer.com/chapter/10.1007/978-3-031-19800-7_8">PDF</a>
|
<a href="https://github.com/Owen718/ECCV22-Perceiving-and-Modeling-Density-for-Image-Dehazing">Code</a> 
<p></p>
</td>

<!-- Paper IV Reflectance, AAAI'23 -->
<!-- ###################################################################################################-->



</tbody>


# Mentoring
I am very lucky to work with the following talented students:
- [Heming Li], RA@HKUST(GZ), B.S.@CUHK
- [Song Fei], Mphil Student@HKUST(GZ).
- [Haoxuan Feng], Mphil Student@HKUST(GZ).
- [Chenghao Xue], Now MSc Student@UC Davis.
- [Jingxia Jiang], Now PhD Student@NC State.


# 🎖 Competitions & Awards & Presentations
- [ICLR 2025 Notable Reviewer](https://iclr.cc/Conferences/2025/Reviewers), LOL😄.
- [KAUST AI Rising Star, 2025](https://www.kaust.edu.sa/en/news/rising-stars-in-ai-symposium-2025).
- [Outstanding Reviewer](https://bmvc2024.org/people/reviewers/), BMVC 2024.
- PG scholarship of HKUST(GZ), 2024.
- 2022 CVPR NAS Competition Supernet Track: Third Place Solution of Track 1 
- 2022 JMU Student Star Award  (20/19000)


# 💬 Academic Services
- Conference Reviewer: ACCV 2022&2024, WACV 2023&2024, BMVC 2023&2024, AAAI 2022&2023&2024&2025, ICCV 2023, CVPR 2024, ECCV 2024, ACM MM 2024, NeurIPS 2024, ICLR 2025, ICML 2025.

- Workshop Competition Organizer: [LOVEU@CVPR 2024](https://sites.google.com/view/loveucvpr24/track1)
  
- Journal Reviewer: 

  International Journal of Computer Vision
  
  IEEE Transactions on Image Processing

  IEEE Signal Processing Letter

  IEEE Journal of Oceanic Engineering


# 📖 Educations&Experience

- Aug'2024-Present: PhD Student, The Hong Kong University of Science and Technology, Guangzhou.

- Nov'2024-Aug'2025: Research Scientist Intern, Hedra Inc. .

- Jun'2023-Jul'2024: Research Assistant, The Hong Kong University of Science and Technology, Guangzhou.
  
- Sep'2019-Jul'2023: B.Eng (Telecommunication Engineering), Jimei University, Xiamen.

<!-- <div style="font-style: italic; font-family: 'Arial Black', Gadget, sans-serif; font-size: 24px;
    background: -webkit-linear-gradient(left, black, yellow, cyan, blue, violet);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;">Adversity shaped me.</div> -->


<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=KKPhQ-LXT8mek63h4Oa8BltFlbFsTTwZkLrrWb3wFEs&cl=ffffff&w=a"></script> -->

<style>
/* Refined styling to match your existing design */
.research-areas {
    background: #f8f9fa;
    padding: 25px;
    border-radius: 12px;
    margin: 20px 0;
}

.research-item {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    display: flex;
    align-items: flex-start;
}

.research-icon {
    font-size: 24px;
    margin-right: 15px;
}

.research-content h3 {
    margin: 0 0 10px 0;
    font-size: 1.2em;
    color: #333;
}

.research-content p {
    margin: 0;
    color: #666;
    line-height: 1.5;
}

/* 添加页面加载动画 */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* 为主要内容块添加动画 */
.research-areas,
.news-section,
.papers-section,
h1, h2, h3 {
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 0;
}

/* 为不同部分设置不同的动画延迟 */
h1 { animation-delay: 0.2s; }
.research-areas { animation-delay: 0.4s; }
.news-section { animation-delay: 0.6s; }
.papers-section { animation-delay: 0.8s; }

/* 增强研究领域卡片的动画效果 */
.research-item {
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    position: relative;
    overflow: hidden;
}

.research-item::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(120deg, transparent 0%, transparent 50%, rgba(255,255,255,.8) 50%, transparent 51%, transparent 100%);
    transform: translateX(-100%);
    transition: all 0.6s;
}

.research-item:hover::before {
    transform: translateX(100%);
}

.research-item:hover {
    transform: translateY(-5px) scale(1.02);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

/* 为图标添加旋转动画 */
.research-icon {
    transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
}

.research-item:hover .research-icon {
    transform: rotate(360deg) scale(1.2);
}

/* 为标题添加渐变色效果 */
.research-content h3 {
    background: linear-gradient(120deg, #1772d0, #6c5ce7);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: all 0.3s ease;
}

/* 添加鼠标跟随效果 */
.research-item:hover::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: radial-gradient(circle at var(--x) var(--y), 
                               rgba(255,255,255,0.2) 0%,
                               transparent 50%);
    pointer-events: none;
}

/* 添加粒子背景的容器 */
#particles-js {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    background: linear-gradient(45deg, #f3f4f6 0%, #fff 100%);
}

/* 确保内容在粒子之上 */
.wrapper {
    position: relative;
    z-index: 1;
}

/* 为内容添加玻璃态效果 */
.research-areas,
.news-section,
.papers-section {
    background: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 15px;
    padding: 25px;
    margin: 20px 0;
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.1);
}

/* 添加炫酷的渐变边框效果 */
.research-item {
    position: relative;
    background: rgba(255, 255, 255, 0.9);
    border-radius: 10px;
    padding: 20px;
    margin: 15px 0;
    overflow: hidden;
}

.research-item::before {
    content: '';
    position: absolute;
    top: -2px;
    left: -2px;
    right: -2px;
    bottom: -2px;
    background: linear-gradient(45deg, #12c2e9, #c471ed, #f64f59);
    z-index: -1;
    border-radius: 12px;
    animation: borderGradient 4s ease infinite;
    opacity: 0;
    transition: opacity 0.3s ease;
}

.research-item:hover::before {
    opacity: 1;
}

@keyframes borderGradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

/* 添加霓虹光效果 */
.research-icon {
    text-shadow: 0 0 10px rgba(23, 114, 208, 0.5);
    animation: glowing 2s ease-in-out infinite;
}

@keyframes glowing {
    0% { filter: drop-shadow(0 0 2px rgba(23, 114, 208, 0.5)); }
    50% { filter: drop-shadow(0 0 8px rgba(23, 114, 208, 0.8)); }
    100% { filter: drop-shadow(0 0 2px rgba(23, 114, 208, 0.5)); }
}

/* 优化标题动画效果 */
.research-content h3 {
    background: linear-gradient(120deg, #1772d0, #6c5ce7, #1772d0);
    background-size: 200% auto;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientText 3s linear infinite;
}

@keyframes gradientText {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}
</style>

<!-- 添加粒子背景容器 -->
<div id="particles-js"></div>

<!-- 添加粒子效果的脚本 -->
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
document.addEventListener('DOMContentLoaded', () => {
    particlesJS('particles-js', {
        particles: {
            number: {
                value: 80,
                density: {
                    enable: true,
                    value_area: 800
                }
            },
            color: {
                value: '#1772d0'
            },
            shape: {
                type: 'circle'
            },
            opacity: {
                value: 0.5,
                random: false
            },
            size: {
                value: 3,
                random: true
            },
            line_linked: {
                enable: true,
                distance: 150,
                color: '#1772d0',
                opacity: 0.4,
                width: 1
            },
            move: {
                enable: true,
                speed: 2,
                direction: 'none',
                random: false,
                straight: false,
                out_mode: 'out',
                bounce: false
            }
        },
        interactivity: {
            detect_on: 'canvas',
            events: {
                onhover: {
                    enable: true,
                    mode: 'repulse'
                },
                onclick: {
                    enable: true,
                    mode: 'push'
                },
                resize: true
            }
        },
        retina_detect: true
    });
});
</script>



