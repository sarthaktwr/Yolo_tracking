# Yolo_tracking
The repository helps to identifiy and track motion of the desiered objects.
Clone the repositroy using anaconda prompt.
Create a new environment using the conda create -n [env_name] python==3.6.9
Go in the cloned repository.
Install the requirements using pip install -r install requirements.txt
Use the following bash command to generate the output: 
python object_tracker.py --video ./data/video/new.mp4 --output ./outputs/demo1.avi --model yolov4 --count  --info
The output video will be generate in the repository in the folder named output.
