# few-shot-learning-PneumoniaMNIST
COMP691 Deep Learning - Project Implementation

The project involved two Kaggle-style problems and a competition. The first challenge required us to create a model from scratch to produce the best results possible using a limited and arbitrary sample from the PneumoniaMNIST dataset, without any external help, such as pre-trained models or external datasets beyond the given sample. Each team was required to submit their results to a leaderboard to determine who had the best model. 

The second challenge was structured similarly to the first, but this time, external resources were allowed, and there was no leaderboard to track each team’s progress. Our team attempted three different approaches for Challenge 1 and two different approaches for Challenge 2 to find the best methods, each with varying results. 

For the first challenge, we experimented with data augmentation techniques, attention modules and a Siamese network. For the second challenge, we tried transfer learning, a faithful reproduction of a ResNet50 model with focal loss, and another Siamese network. 

After analyzing the results, we found that data augmentation was the most effective approach for the first challenge, while transfer learning worked best for the second challenge. However, each approach had its own advantages and drawbacks.

## Results:

### Challenge 1:
![image](https://github.com/rucha97/few-shot-learning-PneumoniaMNIST/assets/22785512/79fd0f99-bcb1-40e6-a7ca-7cdebd8decb4)

### Challenge 2:
![image](https://github.com/rucha97/few-shot-learning-PneumoniaMNIST/assets/22785512/114d0e84-8e8c-4232-9beb-2d4146d89f77)




