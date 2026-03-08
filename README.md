# Homework1- Mariana Sisniegas Hinojosa
## Critical Reflection
Answer the following:
What does it mean for a model to “generalize” in this toy setting? What factors could
make a result appear good but actually be meaningless (e.g., data leakage, very small
test set, unstable metric, overfitting to noise)?

"Generalize" means that a model has the ability to learn patterns from the training data and apply them correctly to new, unseen data. I
Some factors that could make a result appear good are: 
Data Leakage: This happens if the model accidentally "peeks" at the test data during training.
Overfitting to Noise: This occurs when a model becomes too complex. If we let the tree grow too deep, it starts memorizing unimportant details in our images rather than the real patterns of a tumor.
Tiny Test Sets: If you only test your model on a very small group . It’s not a reliable measure of how the model will perform in the real world.
Imbalanced Data: In the second data, you often have way more healthy samples than sick ones. If a model predicts Healthy 100% of the time, it might look 90% accurate, but it is completely useless because it fails to catch the actual disease.
