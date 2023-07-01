# Numpy_Case_Study
## CASE STUDY - Setting up a Jupiter Notebook with NumPy

Jupyter Notebook is a web-based interactive computing environment that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. It is a popular tool used by data scientists, machine learning engineers, and researchers to prototype and experiment with code. NumPy is a popular library for scientific computing in Python. It provides support for arrays and matrices, as well as a range of mathematical functions that can be performed on these arrays. In this case study, we will walk through the process of setting up a Jupyter Notebook with NumPy, and provide examples of how to use the library for scientific computing.

### Step 1: Installing Anaconda

Anaconda is a distribution of Python that comes with many scientific computing libraries pre- installed, including NumPy. It also includes the Jupyter Notebook app, which allows you to createand run Jupyter notebooks.

To install Anaconda, follow these steps:

Go to the Anaconda website (https://www.anaconda.com/products/individual) and download the appropriate installer for your operating system.

Run the installer and follow the instructions to install Anaconda.

### Step 2: Launching Jupyter Notebook

Once Anaconda is installed, you can launch the Jupyter Notebook app by following these steps:

Open a terminal or command prompt.

Type the following command and press Enter:

jupyter notebook

This will launch the Jupyter Notebook app in your default web browser.

### Step 3: Creating a new Jupyter Notebook

To create a now Jupyter Notebook, follow these steps:

Click on the "New" button in the top right corner of the Jupyter Notebook app.

Select "Python 3" from the dropdown menu.

This will create a new Jupyter Notebook with a single cell.

### Step 4: Importing NumPy

To import NumPy in your Jupyter Notebook, you can simply type the following code in a cell:

import numpy as np

This will import the NumPy library and give it the alias 'np", which is a commonly used abbreviation for NumPy.

### Step 5: Creating NumPy arrays

One of the main features of NumPy is the ability to create arrays, which are similar to lists but can be multi-dimensional and have additional mathematical functions. Here are some examples of how to create NumPy arrays:

#create a 1-dimensional array
a=np.array([1,2,3,4,5])
print(a)
#create a 2-dimensional array
b=np.array([[1,2,3],[4,5,6]])
print(b)
#create an array of zeros
c=np.zeros((3,4))
print(c)
#create an array of ones
d=np.ones((2,2))
print(d)

In the first example, we create a 1-dimensional array with the values 1 through 5. In the second example, we create a 2-dimensional array with two rows and three columns. In the third example, we create an array of zeros with three rows and four columns. In the fourth example, we create an array of ones with two rows and two columns.

### Step 6: Performing mathematical operations on NumPy arrays

NumPy provides a range of mathematical functions that can be performed on arrays. Here are some examples

#add two arrays
a=np.array([1,2,3])
b=np.array([4, 5,6])
c=a+b
print(c)
#multiply two arrays
d=np.array([[1,2],[3,4]])
e=np.array([[5,6],[7,8]])
f=d*e
print(f)
#perform matrix multipication
g=np.array([[1,2],[3,4]])
h=np.array([[5,6],[7,8]])
i=np.dot(g,h)
print(i)

In the first example, we add two 1-dimensional arrays and store the result in a new array. In the second example, we multiply two 2-dimensional arrays element-wise and store the result in a new array. In the third example, we perform matrix multiplication on two 2-dimensional arrays and store the result in a new array.

### Step 7: Saving and sharing Jupyter Notebooks

Once you have created a Jupyter Notebook, you can save it by clicking on "File" in the top left corner of the Jupyter Notebook app and selecting "Save" or "Save As". You can also download the notebook as a .ipynb file or a .html file by selecting "Download as" in the "File" menu.

To share a Jupyter Notebook, you can upload it to a file-sharing service such as GitHub, Dropbox, or Google Drive. You can also use a cloud-based service such as Microsoft Azure or Google Colab to run your Jupyter Notebook in the cloud and share it with others.

### Conclusion
In this case study, we have walked through the process of setting up a Jupyter Notebook with NumPy and provided examples of how to use the library for scientific computing. Jupyter Notebook is a powerful tool that allows you to prototype and experiment with code in a flexible and interactive environment. Numry is a popular library for scientific computing in Python that provides support for arrays and matrices, as well as a range of mathematical functions that can be performed on these arrays. With these tools, you can easily analyze data, build machine learning models, and perform scientific calculations in Python.

