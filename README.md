# No Poisonous Fungus Amungus?
## A Mushroom Identification System

Belisha Genin, Catherine Merfeld, Yangtian Yan, Yukun Liu


This tool takes images of wild mushrooms and predicts their safety for human consumption. Our tool could be turned into an app for amateur mushroom foragers to use while out hiking to decide whether a mushroom was worth picking and bringing home for further identification.


There are many other mushroom identification tools in existence. Ours has two key differences. The first is that we use a lightweight model that can run without external servers or internet connection, since we assume users may be out in the wilderness where cell service is spotty or non-existent. The second difference is that our algorithm is capable of handling images taken in poor lighting conditions. This is to keep in mind that our users would primarily be hikers who may find themselves in situations with only their device’s lighting or in other poor lighting conditions (dusk, very bright mid-day sun, clouds, etc.).  


The largest challenge of this project was the small size of the dataset. With a training set consisting of about 4,200 images, the dataset was much smaller than what a neural network needs to run well. To deal with this we applied two methods: data augmentation and transfer learning.
