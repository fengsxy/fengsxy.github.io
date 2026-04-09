---
layout: homepage
---

## About Me

Hi! I am Longxuan (Ted) Yu, a Ph.D. student (2025.09 -- ) in the <a href="https://www.cs.ucr.edu/">Department of Computer Science and Engineering</a> at the <a href="https://www.ucr.edu/">University of California, Riverside (UCR)</a>. My advisor is <a href="https://www.cs.ucr.edu/~gverstee/">Prof. Greg Ver Steeg</a>.  


Before joining UCR, I received my M.S. in Data Science from the <a href="https://ucsd.edu/">University of California, San Diego (UCSD)</a>, where I worked with <a href="https://www.haojianj.in/home.html">Prof. Haojian Jin</a> on trustworthy AI and generative models. I obtained my B.Eng. in Computer Science from <a href="https://en.hdu.edu.cn/">Hangzhou Dianzi University (HDU)</a>.


My current research interests lie in **Diffusion Models**, **Representation Learning**, and **Information-theoretic Methods**. I am particularly interested in the theoretical foundations of generative modeling, mutual information estimation, and how representation learning can support generalization across modalities and domains.  

If you want to know more about my research or potential collaborations, feel free to email me at **ylong030@ucr.edu**.  

---

{% include_relative _includes/projects.md %}

## Academic Experience
- 2025.09 – present, Ph.D. Student, <a href="https://www.cs.ucr.edu/">Department of Computer Science and Engineering</a>, UCR  
  Advisor: <a href="https://www.cs.ucr.edu/~gverstee/">Prof. Greg Ver Steeg</a>
  Research Area: Diffusion models, Representation learning, Information-theoretic methods  
  

- 2023.09 – 2025.06, Research Assistant, <a href="https://datascience.ucsd.edu/">Halıcıoğlu Data Science Institute (HDSI)</a>, UCSD  
  Advisor: <a href="https://hao-jian.com/">Prof. Haojian Jin</a>  
  Project: *Moderator: Moderating Text-to-Image Diffusion Models through Fine-grained Context-based Policies*  
  Research Area: Diffusion-based generative modeling, Human-centered trustworthy AI  

## Education Experience
- 2025.09 – present, Ph.D., Computer Science, UCR, USA  
- 2023.09 – 2025.06, M.S., Data Science, UCSD, USA  
- 2019.09 – 2023.06, B.Eng., Computer Science, <a href="https://en.hdu.edu.cn/">Hangzhou Dianzi University (HDU)</a>, China  

## Honors and Awards
- 2024, **ACM CCS Distinguished Paper Award** (*Moderator: Moderating Text-to-Image Diffusion Models through Fine-grained Context-based Policies*)  
- 2023, Outstanding Graduate, Hangzhou Dianzi University  
- 2022, National Scholarship 







<style>
  .vibe-products {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    padding: 10px 0;
  }
  .vibe-card {
    border: 1px solid #e5e5e5;
    border-radius: 10px;
    overflow: hidden;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .vibe-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
  }
  .vibe-card a {
    text-decoration: none;
    color: inherit;
    display: block;
  }
  .vibe-card img {
    width: 100%;
    height: 170px;
    object-fit: cover;
    border-bottom: 1px solid #e5e5e5;
  }
  .vibe-card-body {
    padding: 12px 15px;
  }
  .vibe-card-body h4 {
    margin: 0 0 6px;
    font-size: 1.05rem;
    font-weight: 600;
    color: #222;
  }
  .vibe-card-body p {
    margin: 0;
    font-size: 0.85rem;
    color: #666;
    line-height: 1.4;
  }
  @media (prefers-color-scheme: dark) {
    .vibe-card {
      border-color: #555;
      background: #4a4a4a;
    }
    .vibe-card img {
      border-bottom-color: #555;
    }
    .vibe-card-body h4 { color: #eee; }
    .vibe-card-body p { color: #bbb; }
    .vibe-card:hover {
      box-shadow: 0 6px 20px rgba(0,0,0,0.3);
    }
  }
</style>

## Vibe Coding Products

Small tools I built with vibe coding. More to come!

<div class="vibe-products">
  <div class="vibe-card">
    <a href="https://paste.lightsoul.xyz/" target="_blank">
      <img src="assets/img/vibe/pair_paste.png" alt="Pair Paste">
      <div class="vibe-card-body">
        <h4>Pair Paste</h4>
        <p>Cross-device clipboard sharing via 6-digit codes. No login needed.</p>
      </div>
    </a>
  </div>
  <div class="vibe-card">
    <a href="https://lightsoul.xyz/" target="_blank">
      <img src="assets/img/vibe/lightsoul.png" alt="LightSoul">
      <div class="vibe-card-body">
        <h4>LightSoul</h4>
        <p>Calorie tracking and diet logging app with daily nutrition breakdown.</p>
      </div>
    </a>
  </div>
  <div class="vibe-card">
    <a href="https://fengsxy.github.io/openclaw-tracing/" target="_blank">
      <img src="assets/img/vibe/openclaw_tracing.png" alt="OpenClaw Tracing">
      <div class="vibe-card-body">
        <h4>OpenClaw Tracing</h4>
        <p>Full-stack observability for AI agents — call tree, entity graph, and SQL analytics.</p>
      </div>
    </a>
  </div>
</div>

## Essay Blog

I keep a bilingual essay blog where I jot down research reflections and life notes.
- [Chinese version](https://fengsxy.github.io/essay/)
- [English version](https://fengsxy.github.io/essay/tag/en/)


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Adapts number of columns based on screen size */
            grid-gap: 10px; /* Spacing between items */
            padding: 10px; /* Padding around the gallery */
        }

        .gallery .item {
            display: flex;
            flex-direction: column; /* Stack image and text vertically */
            align-items: center; /* Center-align items */
        }

        .gallery img {
            width: 100%; /* Images take full width of their container */
            height: 85px; /* Fixed height for all images */
            object-fit: cover; /* Crop to cover the container, preserving aspect ratio */
            border-radius: 8px; /* Rounded corners (optional) */
        }

        .description {
            text-align: center; /* Center-align text */
            padding-top: 5px; /* Space between image and text */
            color: #666; /* Light grey text color, adjust as needed */
            font-size: 0.8em; /* Smaller font size for descriptions */
        }
    </style>


    
    <!-- <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Adapts number of columns based on screen size */
            grid-gap: 10px; /* Spacing between items */
            padding: 10px; /* Padding around the gallery */
        }

        .gallery .item {
            display: flex;
            flex-direction: column; /* Stack image and text vertically */
            align-items: center; /* Center-align items */
        }

        .gallery img {
            width: 100%; /* Images take full width of their container */
            height: auto; /* Maintain aspect ratio */
            border-radius: 8px; /* Rounded corners (optional) */
        }

        .description {
            text-align: center; /* Center-align text */
            padding-top: 5px; /* Space between image and text */
            color: #666; /* Light grey text color, adjust as needed */
            font-size: 0.8em; /* Smaller font size for descriptions */
        }
    </style> -->



</head>
<body>
    <h2>Life Moments</h2>
    <div class="gallery">
        <!-- Each item in the gallery includes an image and a description -->
        <div class="item">
            <img src="assets/img/moments/Coronado.jpg" alt="Coronado Beach">
            <div class="description">Coronado Beach</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/Potato_Chip_Rock.jpg" alt="Potato Chip Rock">
            <div class="description">Potato Chip Rock</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/Shanghai.jpg" alt="Shanghai Skyline">
            <div class="description">Shanghai Skyline</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/gf's fired rice.jpg" alt="GF's Fried Rice">
            <div class="description">GF's Fried Rice</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/hiking_1.jpg" alt="Hiking Trail">
            <div class="description">Hiking Trail</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/hiking_2.jpg" alt="Hiking Trail">
            <div class="description">Hiking Trail</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/hiking_4.jpg" alt="Hiking Overlook">
            <div class="description">Hiking Overlook</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/paino.jpg" alt="Piano Practice">
            <div class="description">Piano Practice</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/random_flower.jpg" alt="Blooming Flowers">
            <div class="description">Blooming Flowers</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/stars.jpg" alt="Starry Night">
            <div class="description">Starry Night</div>
        </div>
        <div class="item">
            <img src="assets/img/moments/whiteMountain.jpg" alt="White Mountain">
            <div class="description">White Mountain</div>
        </div>
         <div class="item">
            <img src="assets/img/moments/sunset.jpg" alt="SD Sunset">
            <div class="description">La Jolla Sunset</div>
        </div>
    </div>
</body>




<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=1OL4KYXswQB7_QtL579x0AO8vPCLmYogJvHv2DawZg8&cl=ffffff&w=a"></script>
