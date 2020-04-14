## Extending Tensorflow ppc64le Image

### Building instructions

```sudo docker build  -t doodeck/tensorflow-ppc64le:latest-pandas-jupyter```

### Running instructions

```sudo docker run -u $(id -u):$(id -g) -it --rm -v $(realpath ~/notebooks):/tf/notebooks -p 8888:8888 <image_id>```
