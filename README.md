# Imbalanced Classification SMOTE

## Goal

For fraud detection, the raw dataset is often imbalanced. Often, recall is quite low and the model is unusable. The goal of this project is to use to SMOTE solve this specific problem by oversampling underrepresented samples.

### Recall rate without SMOTE

- Accuracy = 0.98
- Recall = 0.09

This model is unusable as it cannot correctly identify fraud cases.

![download](https://user-images.githubusercontent.com/44503223/125883251-91982b1a-3561-4012-a63b-bf4600b4f25c.png)


### Recall rate with SMOTE

- Accuracy = 0.99
- Recall = 0.99

SMOTE resolved the previous problem. 

![download](https://user-images.githubusercontent.com/44503223/125883368-a0556fab-d522-4ba3-b9d9-ed1aa1e99b04.png)


## Reference:

The notebook is based on a [blog post](https://towardsdatascience.com/how-to-effortlessly-handle-class-imbalance-with-python-and-smote-9b715ca8e5a7).

## Learn More

You can learn more in [Tingting Duan's Project Portfolio](https://tingting0618.github.io).

