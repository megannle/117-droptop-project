<a name="readme-top"></a>
# Droptop Interface with Yolo V8 CVS 



<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Description">About The Project</a>
    </li>
    <li>
      <a href="#Features">Features</a>
    </li>
    <li><a href="#Getting Started">Getting Started</a></li>
  </ol>
</details>

# Description 
  Proposed improvement of the original Droptop computer vision system. Adds functionality of the current computer vision system with droplet labeling for droplet reacquisition after loss. Includes basic interface for bounding box manipulation, saving, and loading.   


# Features
  ## Interface 
  * GUI provides users the ability to load videos and create bounding boxes for the computer vision system. Includes: video loading, bounding box saving/loading, bounding box processing, setting attributes bounding box type (curve or straight) and direction, clearing of bounding boxes, and undo. Provides a section to display all bounding boxes. 
  
  ## Computer vision system 
  * CVS uses YOLO v8 for droplet detection and uses models trained with Roboflow (best.pt) 

  <p align="right">(<a href="#readme-top">back to top</a>)</p>

  
# Getting Started 
Instructions to get the code to start working :) 

## Prerequisites
* using npm to install the requirements.txt for the project. Need a basic concept of git and python to use. 
```sh
  npm install npm@latest -g
```
## Installation
1. Clone the repo
   ```sh
   git clone https://github.com/ElysonEva/117-droptop-project.git
   ```
2. Install NPM packages (requirements.txt) 
   ```sh
   npm install
   ```
   <p align="right">(<a href="#readme-top">back to top</a>)</p>
## Usage 
* This section notes the steps on how to open a video for bounding box creation and processing.

  FIXXXXXXXXXXXXXXXXXXXXXX LATTTTTTTTTER
1. Set video
2. Run python .\bounding_box_interface_to_use.py
3. Select Open Video file
4. adding bounding boxes, note rules for bounding boxes
5. add straight
6. add curve
7. process video
8. done and dusted 

<p align="right">(<a href="#readme-top">back to top</a>)</p>




  
