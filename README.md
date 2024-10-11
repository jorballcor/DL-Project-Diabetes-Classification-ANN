
# 🚀 Diabetes Classification with Artificial Neural Networks (ANN) 🎉

Welcome to the **Diabetes Classification with ANN** project! This repository contains a simple yet powerful neural network model to predict diabetes using real-world health data. Whether you're a data scientist, AI enthusiast, or just here for the fun, you’ll love seeing how neural networks help predict diabetes.

## 🧠 What's Inside?

1. **Notebook**: The `diabetes-classification-ANN.ipynb` file includes the full journey from data loading to building, training, and evaluating the model.
2. **Model Architecture**: A compact feedforward neural network built using Keras and TensorFlow libraries, designed to classify whether a person has diabetes based on health metrics.
3. **Accuracy Fun!**: A cool loop that trains the model across different random seeds and shows how model accuracy fluctuates. Watch the randomness work its magic! 🔮

## 💻 How to Run This?

Follow the steps below to get everything running:

1. **Clone the Repo**: 
   ```bash
   git clone https://github.com/your-repo/diabetes-ann.git
   cd diabetes-ann
   ```

2. **Install Dependencies**:
   Make sure you have Python 3.x installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**: Open the notebook and execute all cells to run the model training and accuracy plots. It's magic time!
   ```bash
   jupyter notebook diabetes-classification-ANN.ipynb
   ```

## 📊 What Does This Project Do?

This neural network takes in a dataset with several health-related inputs like glucose levels, BMI, and more, to predict whether an individual has diabetes.

Key steps:
1. **Data Preprocessing**: Cleaning and preparing the dataset (standard stuff, but important).
2. **Model Design**: A neural network with:
   - Input layer with 8 neurons (one for each feature).
   - One output neuron with sigmoid activation (because this is binary classification, duh!).
3. **Training**: The model is trained over 1,500 epochs using a batch size of 100 (seriously, we made this thing learn!).
4. **Accuracy Evaluation**: After training, we evaluate how well the model performs on test data. The best part? We use different random seeds to see how accuracy varies. Cool, right? 🎲

## 🔥 Features

- **Custom Random Seed Loop**: Ever wondered how training a model with different seeds affects accuracy? Wonder no more! The loop shows the accuracy for 10 different random seeds and plots the results.
- **Interactive Plots**: Check out the accuracy plot and see how the model's performance changes iteration by iteration.
- **Super Fun to Watch**: Machine learning has never been this much fun! 🎢

## 🛠️ Tools & Tech

- **Language**: Python 🐍
- **Libraries**: 
  - TensorFlow/Keras for building and training the neural network
  - Matplotlib for plotting and visualizations
  - Numpy for data handling

## 🏆 Results?

You’ll see how the model performs, with the accuracy bouncing between ~0.74 and ~0.83 depending on the random seed used. You might even get better results if you tweak the parameters—try it out!

## 🤖 Wanna Contribute?

Feel free to fork this project and make your own improvements! Want to try a different architecture? Maybe change the optimizer? Go ahead and send us a pull request!

1. Fork it 🍴
2. Create your feature branch:
   ```bash
   git checkout -b my-new-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin my-new-feature
   ```
5. Submit a pull request 🤟

## 🎉 Conclusion

With this project, we’ve built a simple yet effective model for predicting diabetes using health data and explored how randomness affects training accuracy. It’s the perfect starting point for anyone curious about neural networks or classification tasks. Have fun exploring the code and watching the model learn!
