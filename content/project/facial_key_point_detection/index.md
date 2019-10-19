---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Facial Key Point Detection"
summary: "Developed a Facial keypoint detection system by training a convolutional neural network on Youtube Faces dataset. "
authors: []
tags: ["Deep Learning", "Computer Vision", "Facial Key Point Detection"]
categories: []
date: 2019-10-18T19:15:55-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/abojja9/Facial_keypoints_detection"
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=alUEBv8RlMA"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Description:

1. Developed a Facial keypoint detection system by training a convolutional neural network on Youtube Faces dataset.
2. The system detects the face and identifies 68 facial keypoints.
3. Facial keypoints are the small green dots shown on each of the faces in the image above. These keypoints mark essential areas of the face: the eyes, corners of the mouth, the nose, etc. These key points are relevant for a variety of tasks, such as face filters, emotion recognition, pose recognition, and so on. 
4. Once we identify the key points, we can quickly get the pixel coordinate information, which is very useful to add objects over the face. 
  
    As an example, we first identify the key points using the deep learning model developed and the image with key points is here:
    ![Alt text](c-3.png "Keypoints")  

    Then we add sunglasses using the coordinates of eyes, and the resultant image obtained is below:
    ![Alt text](c-2.png "Keypoints") 

5. A small demo for this project is available at this [link](https://www.youtube.com/watch?v=alUEBv8RlMA) on youtube.


