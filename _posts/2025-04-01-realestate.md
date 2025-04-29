---
layout: default
categories: project
modal-id: 10
date: 2025-04-01
img: udacity_realestate.png
alt: image-alt
project-date: April 2025
client: N/A
category: Foundation Models, Gen AI
description: Personalized Real Estate Agent
---

<div style="text-align: left;" markdown="1">
### Project Introduction
This is the final project for Udacity's Gen AI nano degree course.  
The project implements a real estate listing application. In an industry where personalization is key to customer satisfaction, the ficticious company wants to revolutionize how clients interact with real estate listings. The goal is to create a personalized experience for each buyer, making the property search process more engaging and tailored to individual preferences.
</div>

<div style="text-align: left;" markdown="1">
### The Challenge
The task is to develop an innovative application named "HomeMatch". This application leverages large language models (LLMs) and vector databases to transform standard real estate listings into personalized narratives that resonate with potential buyers' unique preferences and needs.
</div>

<div style="text-align: left;" markdown="1">

### Core Components"
There are two components, implemented in Google Colab notebooks.  Colab was selected because the solution required GPU for image generation.

In process_Listings.ipynb I first use openAI to get a list of neighborhoods in San Francisco.  Then for each neigborhood I come up with a ficticious listing, and a description that is based on the characteristic of the selected neighborhood.  I also use the description to generate an image of the property.  Below are two samples:

</div>
![](img/portfolio/sf_realestate.png)
<br><br>

<div style="text-align: left;" markdown="1">
The second component if the find_home.ipynb.  Given a list of customer preferences, the code searches for properties that match the user request.  The description of the property is modified to match the user preferences.  Also, the images are vectorized, so the code searches the images for the description.  For example, if the user had indicated that they wanted a property with good views, the code searches the images for that and comes up with the following options:
</div>
![](img/portfolio/views.png)
<br><br>

<div>

<div style="text-align: left;">
  <a href="https://github.com/albertjordan/Personalized_Real_Estate_Agent" target="_blank">View project on GitHub</a>
</div>

