# Multi Class Classification of 133 Dog Breeds

In this project we train a model using transfer learning on resnet-50 (using PyTorch) to identify the breed of a dog among 133 breeds.

We first start by downloading the data, and on sample of the data find the best hyperparameters.
Once we have the best hyperparameters available, we create a new model using that information and train it on the entire dataset.

Once the model is trained, we deploy the model to an endpoint and perform some tests to make sure the model is working as desired.

We also deploy hooks to gather data for model debugging and profiling.
