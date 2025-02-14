# Logistic Regression for Handwritten Digit Recognition

This project demonstrates the implementation of a Logistic Regression classifier from scratch to predict handwritten digits using the MNIST dataset. The project is divided into two parts:

1. **Part 1**: Implementing Logistic Regression from scratch using Python and standard libraries such as NumPy, Pandas, and Matplotlib.
2. **Part 2**: Re-implementing the same task using the scikit-learn library and comparing the results.

## Project Structure

- `Logistic_Regression.ipynb`: Jupyter Notebook containing the implementation and documentation.
- `requirements.txt`: List of Python libraries required to run the notebook.
- `data/mnist_dataset.csv`: The MNIST dataset used for training and testing the model.

## Requirements

To run this project, you need to have the following Python libraries installed:

- NumPy
- Pandas
- Matplotlib
- scikit-learn

You can install these libraries using `pip`:

```bash
pip install numpy pandas matplotlib scikit-learn
```
## Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Shahzaib3769/logistic-regression-digit-classifier.git
   ```
2. **Navigate to the project directory:**:
   ```bash
   cd logistic-regression-digit-classifier
   ```
3. **Install the required libraries**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Logistic_Regression.ipynb
   ```
5. **Follow the instructions in the notebook to run the code and see the results.**

## Dataset
  The MNIST dataset is used in this project. It consists of 60,000 training and testing images of handwritten digits. Each image is a 28x28 grayscale image.It is compressed into a `.zip` file (`mnist_dataset.zip`) to reduce file size. Before running the notebook, you need to manually extract the dataset.

### Steps:
### Steps to Extract the Dataset:
1. Navigate to the `data/` directory:
   ```bash
   cd data
   ```
2. Extract the mnist_dataset.zip file:  
   -On Windows: Right-click the file and select Extract All.  
   -On macOS/Linux: Use the unzip command:
   ```bash
   unzip mnist_dataset.zip
   ```
3. After Extraction, Ensure the `mnist_dataset.zip` file is in the `data/` directory.
4. Return to the project root directory:
   ```bash
   cd ..
   ```
5. Now you can run the notebook 

If the dataset is missing, download it from [MNIST Dataset](https://drive.google.com/file/d/1lsK27vY-YyPM6t-Yp9ql3IsiRtbZ5f5g/view?usp=sharing) and place it in the `data/` directory.  

## Results
  The notebook includes detailed explanations and visualizations of the results obtained from both the custom Logistic Regression implementation and the scikit-learn implementation.
