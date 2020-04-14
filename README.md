## Extending Tensorflow ppc64le Image

### Build instructions

```sudo docker build  -t doodeck/tensorflow-ppc64le:latest-pandas-jupyter```

### RUn instructions

```sudo docker run -u $(id -u):$(id -g) -it --rm -v $(realpath ~/notebooks):/tf/notebooks -p 8888:8888 <image_id>```
