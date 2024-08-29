# YOLO-ESOD Project

This repository contains a YOLO-ESOD model for object detection tasks. Follow the instructions below to set up and run the model on your local machine.

## Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Zouyuhao-lab/YOLO-ESOD.git
   cd YOLO-ESOD 
2. **Install the required packages: Ensure you have Python installed, then run:**
   ```bash
   pip install -r requirements.txt
4. **Dataset and Weights:**
   ```bash
   cat data.txt
   our best weights also in there
5. **Running the Model:**
   ```bash
   dior:python detect.py --weights dior_best.pt --img 640 --conf 0.5 --source ./data
   custom:python detect.py --weights dior_best.pt --img 640 --conf 0.5 --source ./data
6. **training the Model:**
   ```bash
   use yolo-esod.yaml
   
   
