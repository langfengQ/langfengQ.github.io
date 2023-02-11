---
permalink: /
title: #"About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

## About Me
I am currently a master student at [Zhejiang University](https://www.zju.edu.cn/english/), advised by [Prof. Gang Pan](https://person.zju.edu.cn/en/gpan). 
My research interest lies in multi-agent reinforcement learning, particularly cooperative tasks and the extension of proximal policy optimization. I also work on the spiking neural network, including combating spike-oriented gradient vanishing and optimizing the network structure. 

I received a B.S. in Information Engineering at [Southeast University](https://www.seu.edu.cn/english/), where I did research on the communication optimization, advised by [Prof. Liang Wu](https://radio.seu.edu.cn/2018/0423/c19938a213594/page.htm).

<!-- My projects have included analyzing brain MRI (stroke, Alzheimer's disease), liver MRI (hepatocellular carcinoma), fetal MRI (placental oxygenation), and colonoscopy videos (inflammatory bowel disease).  -->



## Publications
<style type="text/css">
	.paper_metadata a {
		text-decoration: none!important;
		color: #494e52;
	}
	table, th, td {
		border: 0px solid black;
	}
	table.pub_table {
		width: 100%;
		font-size: 12pt;
	}
	td.pub_td1 {
		width: 33%;
	}
	td.pub_td2 {
		width: 67%;
	}
	span.subbullet {
		font-size: 11pt;
		margin-left: 20px
	}

    /* Style the gallery */
    #gallery {
		/* display: block; */
		display: flex;
		flex-wrap: wrap;
    }

    /* Style the art pieces */
    .gallery-row {
		display: block; /* Display the art pieces in a row */
		width: 100%; /* Set the width of each art piece to 30% of the gallery width */
    }

    .art-piece {
		width: 30%; /* Set the width of each art piece to 30% of the gallery width */
		margin: 1%; /* Add some margin around each art piece */
    }

    /* Style the images */
    .art-piece img {
    	cursor: pointer;
		width: 100%;
    }
	
	/* Style the modals */
	#modal {
		display: none;
		margin: auto;
		position: fixed;
		z-index: 1; /* Sit on top */
		left: 50%;
		top: 50%;
		transform: translate(-50%, -50%);
		--r: 1/1;
		aspect-ratio: var(--r);
		width:min(90%, min(960px, 90vh*(var(--r))));
		justify-content: center;
		align-items: center;
		box-sizing: border-box;
		padding: 10px;
		overflow: auto;
		background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
	}
	
	.button {
		display: none;
		background: white;
		border-radius: 50%;
		box-shadow: 0 4px 12px rgb(0 0 0 / 15%);
		position: fixed;
		cursor: pointer;
		margin-left: 2px;
		margin-right: 2px;
		margin-top: -20px;
  		color: rgb(102, 102, 102);
		opacity: 1;
		transition-duration: .2s;
		transition-property: opacity;
		z-index: 3;
		top: 50%;
		align-items: center;
		border: none;
		justify-content: center;
		padding: 2px 10px 4px;
	}
	#leftarrow {
		left: 5px;
	}
	#rightarrow {
		right: 5px;
	}

</style>
<script src="assets/js/gallery.js"></script>
<script src="https://unpkg.com/vanilla-back-to-top@7.2.1/dist/vanilla-back-to-top.min.js"></script>
<script>addBackToTop({
  diameter: 56,
  backgroundColor: 'rgb(255, 82, 82)',
  textColor: '#fff'
})</script>

You can also find my articles on <a href="https://scholar.google.com/citations?user=lbkkJdoAAAAJ&hl=zh-CN">my Google Scholar profile</a>.

{% include publications %}

## Selected Awards
* Excellent Graduate Student of Zhejiang University, 2022
* Three-Good Student of Zhejiang University, 2022

<!-- ## Selected Awards
* Takeda Fellowship, 2021-2022
* Siebel Foundation Scholar, 2020
* Yale Department of Biomedical Engineering Prize, 2015
* Tau Beta Pi Engineering Honor Society, 2015

## Invited Talks
* Google Brain, Toronto 2022<br>
	<span class="subbullet">
	Deep learning on neural fields
* Boston Medical Imaging Workshop 2022<br>
	<span class="subbullet">
	Robust counterfactual image generation with spatial-intensity transforms
* MIT-Takeda Presentation Series 2022<br>
	<span class="subbullet">
	Identifying radiological biomarkers with generative models -->

<!--
## Teaching
* Teaching Assistant, Advances in Computer Vision (6.819/6.869), MIT, 2021
* Undergraduate Mentor, MIT Undergraduate Research Opportunities Program
* Guest Lecture, Intro to Computer Graphics (6.4400), MIT, 2022

## Academic Service
* Program Committee, Medical Imaging Meets NeurIPS Workshop (MedNeurIPS)
* Reviewer, International Conference on Machine Learning (ICML)
* Reviewer, Medical Image Analysis (MedIA)
* Reviewer, Conference on Neural Information Processing Systems (NeurIPS)
* Reviewer, Medical Image Computing and Computer Assisted Intervention (MICCAI)
-->
