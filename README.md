# Automated_Vehicule

Onboard computer vision systems for autonomous cars embed several programs, combining vision - that is, perception of the environment, but also calculation of distances.

4 components of the **Vision** part of the embedded system:
1. real-time image acquisition;
2. image processing;
3. image segmentation; 
4. decision system.

Goal: Our mission will focus on the embedded system part 3: **design, train and deploy an image segmentation model**, which will easily integrate into the complete chain.

## Installation
  ### Prerequisites
  Python 3.8\
    
  ### Virtual environment
      
      conda create -n auto python=3.8 -y
      conda activate auto
      
  ### Dependencies    
      pip install -r requirements.txt
 
 ## Usage
  ### Data
  Download and extract the files from [Cityscapes](https://www.cityscapes-dataset.com/dataset-overview/).

  ### Exploratory Data Analysis
  The notebook named P8_data_structure presents the results of the Exploratory Data analysis.
  
  ### Models
  The notebook named P8_models_EN has all the models tested and the metrics. 
  
## Run flask app  
  Within the correct folder, type: 
  pyhton flask_api.py
  
  ## Author
 
 **Ezequiel Saraceno**
 
 ## Show your support

Give a ⭐️ if this project helped you!
