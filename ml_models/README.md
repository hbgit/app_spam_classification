# Docker

$ docker pull tensorflow/serving

$ docker run -it --rm -p 8500:8500 -p 8501:8501 -v "PATH/TO/SAVEDMODEL:/models/spam-detection" -e MODEL_NAME=spam-detection tensorflow/serving
