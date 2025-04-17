<!-- hide -->
# Time series - Step by step guide
<!-- endhide -->

- Understanding a new dataset.
- Analyze the time series and study its characteristics.
- Train a model to predict future memory expenditure.

## 🌱 How to start this project

Follow the instructions below:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.

## 🚛 How to deliver this project

Once you have finished solving the exercises, be sure to commit your changes, push them to your repository, and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

### Sales forecasting system

We want to set up our company's warehouse in another location and we need to estimate the rate of sales, which has been increasing since the company's creation, for the next few months in order to provide the space we will need.

#### Step 1: Loading the dataset

The dataset can be found in this project folder under the name `sales.csv`. You can load it into the code directly from the link:

```text
https://raw.githubusercontent.com/4GeeksAcademy/alternative-time-series-project/main/sales.csv
```

Or download it and add it by hand in your repository.

#### Step 2: Construct and analyze the time serie

Construct the valid data structure for the time serie, graph it, and then analyze it and answer the following questions:

- Which is the tensor of the time serie?
- Which is the trend?
- Is it stationary?
- Is there variability or noise?

> Note: A `tensor` in a time serie is the minimum unit of time for which there is data. It can be every second, minute, hour, day, week, month...

#### Step 3: Train an ARIMA

Use the training data to find the best parameterization of your ARIMA model.

#### Step 4: Predict with the test set

Now use the trained model with the test set and compare the points with the real ones. Measure the performance of the time serie.

#### Step 5: Save the model

Store the model in the corresponding folder.

> Note: We also incorporated the solution samples on `./solution.ipynb` that we strongly suggest you only use if you are stuck for more than 30 min or if you have already finished and want to compare it with your approach.
