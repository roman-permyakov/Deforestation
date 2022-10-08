###### PlanetScope. Deforestation

# **Understanding the Amazon from Space** <img src="https://eospatial.kz/images/para/1.png" height="50">
##  <p align="justify"> [Detect deforestation of the Amazon in Planet satellite image chips](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data)</p> 
 
###  Introduction
<p align="justify">Every minute, the world loses an area of forest the size of 48 football fields. And deforestation in the Amazon Basin
accounts for the largest share, contributing to reduced biodiversity, habitat loss, climate change, and other devastating effects.
But better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders 
respond more quickly and effectively.

Planet, designer and builder of the world’s largest constellation of Earth-imaging satellites, will soon be collecting daily imagery
of the entire land surface of the earth at 3-5 meter resolution. While considerable research has been devoted to tracking changes in forests,
it typically depends on coarse-resolution imagery from Landsat (30 meter pixels) or MODIS (250 meter pixels). This limits its effectiveness
in areas where small-scale deforestation or forest degradation dominate.

Furthermore, these existing methods generally cannot differentiate between human causes of forest loss and natural causes.
Higher resolution imagery has already been shown to be exceptionally good at this, but robust methods have not yet been developed for Planet imagery.</p>


Dataset is available from here: https://www.kaggle.com/datasets/rhammell/planesnet?resource=download </p>

### Content
<p align="justify">This Notebook is used to train a ResNet-50 model on Amazon Planet Dataset (MultiLabel Classification Problem)
Used Fast AI for eaiser training and inference rather than PyTorch or Tensorflow.

Inspired by https://medium.com/@andrecnf


