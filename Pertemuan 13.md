# Deep Belief Networks

case example Python
requirement:
1. git
2. docker


### 1. clone and cd directory
```
git clone https://github.com/albertbup/deep-belief-network
cd deep-belief-network
```
### 2. create image
```
docker build -t dbn .
```
### 3. run the container and exec
```
# linux/mac
docker run --rm -it -v ${PWD}:/code dbn:latest bash

# windows
docker run --rm -it -v "%cd%":/code dbn:latest bash
```
### 4. evaluate model
```
python example_classification.py
python example_regression.py
python example_unsupervised.py
```
