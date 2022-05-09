---
title: Home
---

{::nomarkdown}
<script>
document.onmousemove = function(){
var x = event.offsetX;
var y = event.offsetY;    
document.getElementById("p2").style.backgroundPositionX = -x + "px";
document.getElementById("p2").style.backgroundPositionY = -y + "px";        
}
</script>
<style>
.header {
  background: #ffffff;
  height: 300px;
  filter: blur(0.5rem);
  background-image: url(https://github.com/ShakerLab/shakerlab.github.io/blob/main/images/background.jpg?raw=true);
}
.bg-text {
  color: gray;
  position: absolute;
  top: 35%;
  left: 80%;
  transform: translate(-50%, -150%);
  width: 50%;
  text-align: center;
}
</style>

<div class="header" id="p2"></div>
<div class="bg-text">
<h1 style="font-size:50px">About</h1>
Our lab focuses on delineating the role of epithelial-stromal interactions in regulating injury, repair, inflammation and cancer development in the human esophagus. We use a variety of experimental approaches including traditional cell culture and complementary 3D-organotypic/organoid models to recapitulate esophageal tissue and disease in vitro to understand the pathways involved. We also use databases and pathology samples to learn more about clinical risk factors for disease and to study the human esophagus in different states: healthy, inflamed or damaged, and with cancer.
</div>

{:/nomarkdown}

{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Current Projects

{% capture text %}
We are establishing human esophageal myofibroblasts (HEMFs) from biopsies and full thickness specimens from normal and diseased human esophagus.

{%
  include link.html
  link="hemfs"
  text="Human esophageal myofibroblasts (HEMFs)"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/projects/hemfs/hemf_cultured.jpg"
  link="hemfs"
  title="Human esophageal myofibroblasts (HEMFs)"
  text=text
%}

{% capture text %}

We use established and cutting-edge techniques including high throughput sequencing and complementary organoid/organotypic models to identify the role of human esophageal myofibroblasts in benign and malignant esophageal disorders.

{%
  include link.html
  link="esophageal-disorders"
  text="Benign and malignant esophageal disorders"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/projects/esophageal-disorders/disorders.jpg"
  link="esophageal-disorders"
  title="Benign and malignant esophageal disorders"
  flip=true
  text=text
%}

{% capture text %}

Pharyngeal muscle weakness and dysphagia is common in individuals post-stroke or with Parkinson’s disease and in individuals with head/neck cancer who have undergone surgery and/or radiation therapy. Therapeutic options for these patients are limited. In collaboration with our Speech Pathology colleagues, this pilot study is intended to assess the feasibility, safety, and efficacy of the External Pharyngeal Exerciser (EPE) on patients with pharyngeal dysphagia receiving swallow therapy.

{%
  include link.html
  link="oral-pharyngeal-dysphagia"
  text="Oral-pharyngeal dysphagia therapy"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="oral-pharyngeal-dysphagia"
  title="Oral-pharyngeal dysphagia therapy"
  text=text
%}
