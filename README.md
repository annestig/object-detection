# object-detection

source: https://github.com/samk3211/MLPlaybooks


Object Detection Tutorial
Part 1: Preliminary Steps
1. Create an Anaconda environment with python version 3.6.
conda create -n retinanet python=3.6 anaconda

2. Activate the environment and install the necessary packages.
source activate retinanet 
conda install tensorflow numpy scipy opencv pillow matplotlib h5py keras

3. Then install the ImageAI library.
pip install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.1/imageai-2.0.1-py3-none-any.whl

4. Now download the pretrained model required to generate predictions. This model is based on RetinaNet. Click on the link to download – RetinaNet Pretrained model
5. Copy the downloaded file to your current working folder, e.g., "Documents/MLWorkshop"
6. Download the example image from here. Name the image as "testImage.png" and save it under "Documents/MLWorkshop".
7. Open jupyter notebook: type "jupyter notebook" in your terminal (from the current working folder)
