### 🔢 [NumPy](./numpy/)
Welcome to my structured learning repository for numpy in Data Analysis. This repository tracks my progress through hands-on sessions, focusing on Python libraries, mathematical foundations, and data manipulation techniques.

📊 Roadmap & Curriculum

#### 🎓  Each session is documented in a dedicated Jupyter Notebook (.ipynb) within the repository.
🟢 Session 1: Environment Setup & Fundamentals of N-Dimensional Arrays

The beginning of the journey: understanding the core concepts of data structures and setting up a professional workspace.

Introduction to Arrays: Understanding the concept of data containers.
Dimensionality: Exploring 1D (Vectors), 2D (Matrices), and Multi-dimensional arrays.
Environment Management:
Setting up Virtual Environments.
Installing essential libraries and managing dependencies.

In this session, we explored the hierarchy of data structures and essential array manipulation techniques:

    1. Dimensionality & Structure:
         Scalar (0D): A single numerical value.
         Vector (1D): A sequence of numbers.
         Matrix (2D): A collection of vectors (rows and columns).
         Tensor (3D+): Multi-dimensional arrays used in advanced computations.
         Understanding `ndim`: Analyzing the number of axes in an array.

    2. Array Manipulation & Reshaping:
         reshape(): Changing the shape of an array without changing its data.
         flatten() vs ravel(): Methods for converting multi-dimensional arrays into 1D arrays (understanding memory layout).
         concatenate(): Joining multiple arrays along a specified axis.
        
    3. Advanced Indexing & Operations:
         Masking (Boolean Indexing): Filtering data using conditional logic.
         Slicing & Indexing: Accessing specific elements and sub-arrays.
         Broadcasting Rules: How NumPy handles operations between arrays of different shapes.

🔵 Session 2: NumPy Core - Manipulation & Shaping

Moving beyond simple arrays to mastering how to transform and slice data efficiently.

    Data Types & Conversion:
    dtype: Controlling memory and precision.
    astype(): Seamlessly converting between types (e.g., float to int).
    Array Transformation:
    reshape(): Changing dimensions without losing data integrity.
    flatten(): Collapsing multi-dimensional arrays into 1D.
    concatenate(): Joining multiple arrays into a single structure.
    Advanced Indexing:
    Slicing: Precision extraction in 1D and 2D spaces.
    Masking: Boolean indexing for filtering data based on conditions.
    Randomness: Generating synthetic data using np.random.

🟡 Session 3: NumPy Advanced - Math & Statistics

Leveraging NumPy for complex mathematical operations and data insights.

    Mathematical Operations:
    Arithmetic: Element-wise operations (Addition, Subtraction, etc.).
    Rounding: Precision control using np.round(), np.ceil(), and np.floor().
    Set Operations:
    Finding unique elements with np.unique().
    Mathematical sets: union1d() and intersect1d().
    Statistical Analysis:
    Measures of Central Tendency: mean(), median().
    Measures of Dispersion: std() (Standard Deviation), var() (Variance).
    Advanced Functions:
    Logical Masks: Complex boolean filtering and logic.
    Polynomials: Creating and manipulating polynomial functions using the numpy.polynomial package.

🛠️ Tech Stack

Python

NumPy

Jupyter

Matplotlib



**📂 Files in this folder:**
   `lesson_1_basics.ipynb`: Detailed implementation of the topics mentioned above.

   `lesson_2.ipynb`: Detailed about reshape and concatnate the arrays and ...
   
   `lesson_3.ipynb`: 
   

