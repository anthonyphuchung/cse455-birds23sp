---
layout: post
subtitle: Discussion, Problems Encountered, Next Steps
---

Through our experience participating in the Kaggle competition, one of the early problems we encountered was performing hyperparameter tuning during the training process. The process of tweaking learning rate and decay values proved challenging and time consuming as the model took a long time to run. We attempted to resolve this by running the training process with only a few epochs, like 2, and with less training data. When we saw results which we thought were promising, we would revert back to the original number of epochs (5 and 10) and the entire training data but we found that the shortcut we made was not representative of the full training data. Thus, we came to realize that seeing promising results found in the shortcut did not always translate to promising results in the entire dataset.

Moving forward in this project, we would continue to tweak the hyperparameters and try more neural network architectures. There are several more architectures that we were interested in exploring, such as VGG, however we didn’t have the time to try more. 

Our approach differs from others because we looked at different convolutional neural networks and investigated the performance of different networks. An intermediate step we took was exploring the effect of differing epoch times as we tested the neural networks. In the end, this didn’t end up affecting the accuracy of the model positively, but we feel like it was a relevant and important aspect of our learning experience.

![bird-meme](bird-meme.jpg)
