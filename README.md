# Device State Classification with Images and Dynamometer Data

## Description
This is the repository for the ECE228 - Final Project by Team 24 (SP24).\
It involves data classification with Mudestreda Multimodal Device State Recognition Dataset of Real Industrial Milling Device data containing Time Series and Image data.


## Installation
To use this project, follow these steps:

1. Clone the repository to your local machine:
    ```
    git clone https://github.com/your-username/ECE228-Final-Project.git
    ```

2. Navigate to the project directory:
    ```
    cd ECE228-Final-Project
    ```

3. Run the ipynb files in following order:
    ```
    spec.ipynb (uncomment the first code block for downloading the dataset)
    tool.ipynb
    multi_recurrent.ipynb
    ```

---
## Code Structure

### Project Jupyter Notebooks:
- [spec.ipynb](./spec.ipynb) has the model definitions and training code for the time series modality pathway
- [tool.ipynb](./tool.ipynb) has the model definitions and training code for the image modality pathway
- [multi_recurrent.ipynb](./multi_recurrent.ipynb) has the final tempmixer block with GRU for the multimodal architecture along with it's training code
---

## File Structure
1. [output](./output/):
     - Contains the generated model checkpoints along with loss and accuracy across epochs.

---

## Required Packages
> torch

> pandas

> numpy

> matplotlib

> cv2

> time

---

## Team Members
- Eric Bressinger
- Nikhil Gandudi Suresh
- Sharvari Satish Deshmukh
