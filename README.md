## PyTorch Flower Classifier  
I put this together as a way to break out of the 'tutorial infinite loop' and get my hands dirty with PyTorch. Evantually the goal is to create a general purpose plant classifier, able to identify the plant(s) in a provided picture, but I wanted to start with something manageable and build up from there. [This](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition) great kaggle dataset provided the training and testing data I've used so far for training the model to classify flowers.  

### Features  
Currently, I am training the model to identify flowers from five categories: sunflowers, dandelions, tulips, roses, and daisys. The network I'm using is the ResNet18 model.  