# Custom datasets and transfer learning in PyTorch

I've developed this project to practice my new skills using PyTorch, which include creating custom datasets and models, using data loaders, and implementing transfer learning. I've created a model class that includes a pre-trained VGG19 without the last layer as well as a sequential model. Since I'm using the relatively simple MNIST dataset, the sequential model contains only the new final layer (with 10 outputs instead of 10000). However, for other applications, additional layers can be easily added to the sequential container.
