# Machine Learning with Python

Data Science is the backbone of understanding, analyzing, and making sense of data. Machine Learning, a subset of Data Science, takes it one step further by enabling computers to learn from this data, identify patterns, and make decisions with minimal human intervention.

## <span style="color: #ebce14;">Introduction to Data Science</span>

### <span style="color: #44cecc;">Introduction to Course</span>

- <span style="color: Red;">What is it?</span>

  - <span style="color: #0099dd;">Mathematics</span>: The abstract study of numbers, quantities, and shapes used to model and solve real-world problems (Sum, Division, and etc.)
  - <span style="color: #0099dd;">Statistics</span>: A branch of mathematics that deals with data collection, analysis, interpretation, and presentation (Average, Standard Division, and etc.)
  - <span style="color: #0099dd;">Computer Science</span>: The study of computational systems, algorithms, and the design of software and hardware (Calculator)
  - <span style="color: #0099dd;">Data Science</span>: The interdisciplinary field that `combines` `statistics`, `mathematics`, and `computer science` to extract insights from data (what products will sell best during the holiday season, income)
  - <span style="color: #0099dd;">Data Mining</span>: The process of discovering patterns and relationships in large data sets using algorithms (Social media and positive reviews)
  - <span style="color: #0099dd;">Data Analytics</span>: The process of examining data sets to draw conclusions and make informed decisions (tailor workout recommendations to boost participation)
  - <span style="color: #0099dd;">Artificial Intelligence (AI)</span>: The `simulation of human` intelligence in machines that can perform tasks like decision-making, language processing, and problem-solving (A virtual assistant)
  - <span style="color: #0099dd;">Machine Learning</span>: A subset of AI that enables systems to learn from data and improve over time without explicit programming (suggest new movies they might enjoy, and etc.)
  - <span style="color: #0099dd;">Deep Learning</span>: A specialized subset of machine learning using `neural networks` to model complex patterns and make `high-level decisions` from `large data sets` (face recognition)
  -
  - ![](/assets/data-science-vs-machine-learning.png)
  -

- <span style="color: Red;">The Path(Key Information)</span>

  - <span style="color: #dd9900;">Introduction to Data Science</span>

    - Data Science involves extracting `insights` from data using a mix of `statistical method`s, `data analysis`, and `domain knowledge`
    - Core concepts:
      - `Data Collection`: Sources (structured/unstructured data) and methods
      - `Data Cleaning`: Handling missing values, data transformation, and ensuring quality
      - `Exploratory Data Analysis (EDA)`: Visualizing data, understanding patterns, and initial insights
      - `Feature Engineering`: Preparing raw data for use in Machine Learning algorithms
    - Tools and Technologies:
      - Python libraries like `Pandas`, `NumPy`, and `Matplotlib`

  - <span style="color: #dd9900;">Connecting Data Science with Machine Learning</span>
    - Machine Learning is the next logical step after mastering Data Science. Once you can work with data (collect, clean, and analyze), Machine Learning allows you to build models that can predict future trends or automate decision-making
    - Why Data Science is essential for Machine Learning:
      - <span style="color: #44ddcc;">Understanding and preparing the data are crucial to the success of Machine Learning models</span>
      - <span style="color: #44ddcc;">Data Science provides the skills for transforming raw data into features that Machine Learning algorithms can utilize</span>
  - <span style="color: #dd9900;">Introduction to Machine Learning</span>
    - Machine Learning is the science of teaching computers to perform tasks by learning from data, rather than being explicitly programmed
    - Types of Machine Learning:
      - `Supervised Learning`: Learning from labeled data (e.g., classification and regression tasks)
      - `Unsupervised Learning`: Learning from unlabeled data (e.g., clustering and association)
      - `Reinforcement Learning`: Learning through interactions with an environment (e.g., game playing or robotics)
    - Key Algorithms:
      - `Linear Regression`, `Decision Trees`, `Neural Networks`, and `Support Vector Machines`
    - Python libraries: `Scikit-learn`, `TensorFlow`, `Keras`, `PyTorch`
  - <span style="color: #dd9900;">Why Learn Data Science and Machine Learning?</span>

    - `High Demand in the Job Market`: Data Scientists and Machine Learning Engineers are among the most sought-after professions in technology, finance, healthcare, and many other industries
    - `Diverse Applications`:

      `In healthcare`: Predicting diseases, personalized treatments.
      `In finance`: Fraud detection, stock market predictions.
      `In technology`: Self-driving cars, virtual assistants (e.g., Siri, Alexa)

    - `Problem-Solving and Automation`: You will learn how to automate processes, make predictions, and solve real-world problems by leveraging data

- <span style="color: Red;">Why Python?</span>

  - `First`, it's `easy to learn`: Python is now the language of choice for introducing university students to programming
  - `Second`, it's `full featured`: Python is a very general programming language with a lot of built-in libraries and excels at manipulating data, network programming, and databases
  - `Finally`, Python has a significant set of `data science libraries` one can use: The base of these is called the `SciPy` Ecosystem

- <span style="color: Red;">Part one OutLine</span>

  - Prerequisite Python Knowledge
  - The `Pandas` Toolkit
  - Advanced querying and manipulating with `Pandas`
  - Basics statistical analysis with `numpy` and `scipy`, and project

- <span style="color: Red;">About `Pandas`</span>

  - several important aspects of the Pandas library, which is fundamental for data manipulation in Python. Key points include:

    - `Data Structures`: Introduction to the two main data structures in Pandas: Series and DataFrames

      - <span style="color: #44ddcc;">`Series`: A one-dimensional array that holds data of any type</span>
      - <span style="color: #44ddcc;">`DataFrame`: A two-dimensional table-like structure similar to spreadsheets</span>

    - `Data Manipulation`: How to perform common data manipulation tasks such as:

      - <span style="color: #44ddcc;">Loading data from `CSV` files using `pd.read_csv()`</span>
      - <span style="color: #44ddcc;">`Filtering` and `selecting` data using `conditions` and `indexing`</span>

    - `Data Cleaning`: Techniques for cleaning and preparing data, including:

      - <span style="color: #44ddcc;">`Handling missing` values `(NaN)` using functions like `dropna()` and `fillna()`</span>
      - <span style="color: #44ddcc;">Renaming columns and restructuring DataFrames</span>

    - `Applying Functions`: Introduction to `apply()` method for transforming data. This allows the application of functions over rows or columns efficiently

    - `Group By Operations`: Demonstration of how to use `groupby()` to aggregate data, which is particularly useful for summarizing data by categories

    - `Merging and Joining`: Basics of `merging` and `joining` different DataFrames, which is crucial for combining datasets

- <span style="color: Red;">Brief About Jupyter Notebook System</span>

  - Talk about `Jupyter` NoteBook
  - Install Jupyter NoteBook using `pip` tool
  - Test some Python sample code in Notebook
  - Talk about Jupyter NoteBook tools and ecosystem
  - Talk about Server component and markdown ability
  - Open Jupyter NoteBook inside the terminal and check some codes

- <span style="color: Red;">The Python Programming Language: <span style="color: #00bbcc;">Functions</span></span>

  - Python is a interpretation language and interpreter execute its code line by line
  - Start by writing a simple function in your Jupyter NoteBook (`add_numbers`)
  - Remember, Python is a Dynamically type language
  - Jupyter NoteBook execute your code by sending it to the machine in the cloud
  - Python doesn't need any keyword for declaring a variable
  - Python `None` is equal to `null` in JS (absence of a value)
  - After executing a cell at the end of NoteBook a new cell will be created
  - Changing in one cell doesn't change any result in other cells befor running them again
  - Write add_numbers function in more complex way
  - In python we can assign a function to a variable

- <span style="color: Red;">The Python Programming Language: <span style="color: #00bbcc;">Types and Sequences</span></span>

  - `type` can return data or function as output
  - We have three primitive type in Python
    - Number
    - String
    - Boolean
  - We are going to talk about three sequence or collection (Complex data structure) in Python
    - List
    - Tuple
    - Dictionary
  - Talk about primitive Types
  - Talk about Tuple
  - Talk about List
  - Using `append()` function fo a list
  - Loop over a list using for and while (index)
  - Mathematical operators on lists
  - Use the `in` operator to check if something is inside a list.
  - Use bracket notation to slice a string
  - `list[-1]` return the last element of the string
  - `[:]` slicing is core to the Python Programming Language
  - Slicing is going to be used in regular expression topic in text Mining
  - We can concatenate two string using `+` operator
  - Talk about `split()` method. `split` returns a list of all the words in a string, or a list split on a specific character.
  - Make sure you convert objects to strings before concatenating.
  - Dictionaries are labeled and unordered data structures
  - Retrieve a value by using the indexing operator
  - Assign new item to the Dictionary
  - Iterate over all of the keys
  - Iterate over all of the values / Iterate over all of the items in the list
  - You can unpack a sequence into different variables
  - Make sure the number of values you are unpacking matches the number of variables being assigned.

- <span style="color: Red;">The Python Programming Language: <span style="color: #00bbcc;">More on Strings</span></span>

  - In python 3 strings are `unicode` (`UTF`) based (note limited 0-256 characters)
  - Python 3 use it by default
  - Python has a built in method for convenient string formatting
  - Use format string method in the form of `placeholder` and its normal shape
  - String manipulation is a big part of `data cleaning`

- <span style="color: Red;">Python Demonstration: <span style="color: #00bbcc;">Reading and Writing CSV files</span></span>

  - Iterating through a .CSV file to create a Dictionary
  - Use `precision` to format print
  - `csv.Dictreader` convert our csv file content to a list of dictionaries
  - `len` shows that our list is comprised of 234 dictionaries
  - `keys` gives us the column names of our csv
  - Similarly this is how to find the average hwy fuel economy across all cars
  - All values saved in the format of string inside the dictionary so we need to convert it to float and then we can sum all values together
  - Also we can make a `set` of values of a specific field
  - Do a complex example where we are grouping the cars by number of cylinder, and finding the average cty mpg for each group
  - Use `set` to return the unique values for the class types in our dataset
  - Do above example for highway field
  - We can do all above things with `pandas` library in the easy way
