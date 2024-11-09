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
  - Use iPython magic command `precision` to format floating point number for print
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

- <span style="color: Red;">The Python Programming Language: <span style="color: #00bbcc;">Dates and Times</span></span>

  - Lots of analysis you do relate to dates and times
  - Dates and times can be saved in many different ways
  - `time` returns the current time in seconds since the Epoch. (`January 1st, 1970`)
  - Convert the timestamp to datetime using `.fromtimestamp` method
  - Talk about Handy datetime attributes
  - `timedelta` is a duration expressing the difference between two dates

- <span style="color: Red;">The Python Programming Language: <span style="color: #00bbcc;">Objects and map()</span></span>

  - Talk about classes in Python and Object Oriented Programming (OOP)
  - Add a constructor is not necessary
  - An example of a class in python
  - The map function is one of the basis for functional programming in python
  - `Functional programming` in Python is a paradigm that treats computation as the evaluation of mathematical functions. It focuses on avoiding changing states and mutable data, relying instead on pure functions that return new data `without modifying the input`
    - `Pure Functions`: Functions that give the same output for the same input without side effects
    - `Higher-Order Functions`: Functions that can take other functions as arguments or return them, such as `map()`, `filter()`, and `reduce()`
    - The `map()` function in Python is used to apply a given `function` to all items in an `iterable` (like a list or tuple) and return a `map object` (which is an iterator) containing the results
    - `map(function, iterable)`
    - Example of mapping two lists (It returns object which is useful in dealing with big data) (`lazy evaluation`)

- <span style="color: Red;">The Python Programming Language: <span style="color: #00bbcc;"> Lambda and List Comprehensions</span></span>

  - A lambda function is a one-line anonymous function that we can pass to other functions
  - Lambda function structure: `lambda parameter: expression`
  - Lambdas are really much more limited than full function definition
  - The return of a lambda is a function reference
  - They are very useful for simple little data cleaning tasks
  - Talk about list Comprehensions

### <span style="color: #44cecc;">Numerical Python Library (NumPy)</span>

- <span style="color: Red; font-weight:bold;">NumPy</span>

  - `Numpy` is the fundamental package for numeric computing with Python
  - We will talk about creating array with certain data types, manipulating array, selecting elements from arrays, and loading dataset into array
  - `pandas` is a part of `Numpy` and it has a `high-performance data-centric` package
  - In this part we talk about creating, manipulating, selecting, and loading a data set into an array
  - Actually `array` is a list of objects
  - To creating a array using pandas library we can use `array()` method
  - `ndim` attribute return the dimension of our array
  - Passing a list of list, create a `multi-dimension` array
  - We can print out the length of each dimension by calling the `shape` attribute, which returns a tuple
  - We can also check the type of items in the array by using `dtype` attribute
  - `Array` method accepts all kind of valid data type as input
  - Note that numpy automatically converts integers, like 5, up to floats, since there is no loss of precision
  - Numpy will try and give you the best data type format possible to keep your data types `homogeneous`, which means all the same, in the array
  - Sometimes we know the shape of an array that we want to create, but not what we want to be in it. `numpy` offers several functions to create arrays with initial placeholders, such as `zero's` or `one's`
  - We can also generate an array with random numbers
  - You'll see zeros, ones, and rand used quite often to create example arrays, especially in `stack-overflow` posts and other forums
  - We can also create a sequence of `numbers` in an array with the `arrange()` function
  - If we want to generate a sequence of `floats`, we can use the `linspace()` function
  - the third argument is the total number of items you want to generate
  - We can do many things on arrays, such as `mathematical manipulation` (addition, subtraction, square, exponents)
  - We can also do `matrix manipulation` such as `product`, `transpose`, `inverse`, and so forth
  - We can apply an operator on an array, and a `boolean array` will be returned for any element in the original, with True being emitted if it meets the condition and False otherwise
  - Do it for checking items in the case of being even or odd
  - If we want to do `elementwise product`, we use the `"*"` sign
  - If we want to do `matrix product`, we use the `"@"` sign or use the `dot` function
  - When manipulating arrays of different types, the type of the resulting array will correspond to the more general of the two types. This is called `upcasting`
  - `Numpy` arrays have many interesting `aggregation functions` on them, such as `sum()`, `max()`, `min()`, and `mean()`
  - or two dimensional arrays, we can do the same thing for each row or column
  - By using `reshape()` method we can make multidimensional array
  - We can load an image as matrix in notebook using numpy and manipulate it
  - If we just wanted to invert this image we could use the numpy array to do so
  - We can create a large shape image using `full` method which its items all to be the same

- <span style="color: Red; font-weight:bold;">Indexing, Slicing and Iterating</span>

  - `Indexing`, `slicing` and `iterating` are extremely important for data manipulation and analysis because these techinques allow us to select data based on conditions, and copy or update data
  - A one-dimensional array, works in similar ways as a list.To get an element in a one-dimensional array, we simply use the offset index
  - For multidimensional array, we need to use integer array indexing
  - Boolean indexing allows us to select arbitrary elements based on conditions
  - We can then place this array of booleans like a mask over the original array to return a one-dimensional array relating to the true values
  - Slicing is a way to create a sub-array based on the original array
  - For slicing we use `:`
  - Slicing in one dimensional array and list are completely the same
  - Slicing in two dimensional array is different and first argument is for rows and the second argument is for columns
  - Modifying the sub array will consequently modify the original array

- <span style="color: Red; font-weight:bold;">Trying Numpy with Datasets</span>

  - To load a dataset in Numpy, we can use the `genfromtxt()` function
  - We can specify data file name, delimiter (which is optional but often used), and number of rows
  - The genfromtxt() function has a parameter called `dtype` for specifying data types of each column
  - Without specifying the types, all types will be casted the same to the more general/precise type
  - Also remember that for multidimensional arrays, the first argument refers to the row, and the second argument refers to the column, and if we just give one argument then we'll get a single dimensional list
  - But if we wanted the same values but wanted to preserve that they sit in their own rows we would write `wines[:, 0:1]`
  - We can then call the aggregation functions on this data

- <span style="color: Red; font-weight:bold;">Manipulating Text with Regular Expression/span>
- Actually regular expression is a pattern which you give to a regex processor with some source data. The processor then parses that source data using that pattern, and returns chunks of text back to the a data scientist or programmer for further manipulation
- There's really three main reasons you would want to do this:
  - to check whether a pattern exists within some source data
  - to get all instances of a complex pattern from some source data
  - to clean your source data using a pattern generally through string splitting.
- Regexes are not trivial, but they are a foundational technique for data cleaning in data science applications, and a solid understanding of regexs will help you quickly and efficiently manipulate text data for further data science application
- First we'll import the `re` module
- To checking for conditionals, we can segment a string by tokenizing
- The regex specification standard defines a markup language to describe patterns in text:
- Lets start with anchors.
- Anchors specify the start and/or the end of the string that you are trying to match
- The caret character `^` means start
- The dollar sign character `$` means end

- <span style="color: Red; font-weight:bold;">Patterns and Character Classes</span>
- Talk more about patterns and start with character classes
- You can also include a `range of characters`, which are ordered alphanumerically
- You can write this pattern by using the `pipe` operator, which means `OR`
- We can use the `caret` with the set operator to negate our results

- <span style="color: Red; font-weight:bold;">Quantifiers</span>
- `Quantifiers` are the number of times you want a pattern to be matched in order to match
- quantifier is expressed as `e{m,n}`, where e is the expression or character we are matching, `m` is the `minimum number` of times you want it to matched, and `n` is the `maximum number` of times the item could be matched
- It's important to note that the regex quantifier syntax does not allow you to deviate from the {m,n} pattern
- we can use `\w` to match any letter, including digits and numbers
- We can use an asterisk `*` to match 0 or more times

- <span style="color: Red; font-weight:bold;">Groups</span>
- you can actually match different patterns, called groups, at the same time, and then refer to the groups you want
- we've seen that `findall()` returns strings, and `search()` and `match()` return individual Match objects
- We use the function `finditer()` if we want a list of Match objects
- We can get an individual group using `group(number)`
- we can print out the whole dictionary for the item too, and see that the `[edit]` string is still in there
- For that we use the syntax `(?P<name>)`, where the parenthesis starts the group, the `?P` indicates that this is an extension to basic regexes, and `<name>` is the dictionary key we want to use wrapped in `<>`
- We can get the dictionary returned for the item with `.groupdict()`

- <span style="color: Red; font-weight:bold;">Look-ahead and Look-behind</span>
- We can isolate text which comes before the `[edit]` rendering, but we actually don't care about the `[edit]` text itself

- <span style="color: Red; font-weight:bold;">Example: Wikipedia Data</span>
- The `verbose` mode allows you to write multi-line regexes and increases readability
- This means we can write our regex a bit more like code, and can even include comments with
- Now when we call `finditer()` we just pass the `re.VERBOSE` flag as the last parameter

- <span style="color: Red; font-weight:bold;">Example: New York Times and Hashtags</span>
- So lets create a pattern. We want to include the hash sign first, then any number of alphanumeric characters. And we end when we see some whitespace

- <span style="color: Red; font-weight:bold;">Part Two Reading Assignments (Optional)</span>
- <span style="color: Blue; font-weight:bold;">Python for Data Analysis</span> by Wes McKinney (O’Reilly). Copyright 2017 Wes McKinney, 978-1-491-95766-0.

  - Chapter Five: Getting started with pandas

  - Chapter Seven: Data Cleaning and Preparation

### <span style="color: #44cecc;">Pandas</span>

- <span style="color: Red; font-weight:bold;">Introduction to Pandas</span>

  - The pandas library is a powerful, open-source tool in Python designed for data manipulation and analysis
  - It provides data structures, mainly the DataFrame and Series, to handle large datasets and perform operations such as cleaning, transforming, and analyzing data efficiently
  - Pandas was created by `Wes McKinney` in 2008, and is an open source project under a very permissive license
  - I want to take a moment here to introduce the question answersing site Stack Overflow. Stack Overflow is used broadly within the software development community to post questions about programming, programming languages, and programming toolkits
  - In 2012 Wes McKinney wrote the definitive Pandas reference book called `Python for Data Analysis` and published by `O'Reilly`, and it's recently been update to a second edition. I consider this the go to book for understanding how Pandas works

- <span style="color: Red; font-weight:bold;">The Series Data Structure</span>

  - The series is one of the core data structures in pandas
  - You think of it a cross between a list and a dictionary
  - The items are all stored in an order and there's labels with which you can retrieve them
  - As you might expect, you can create a series by passing in a list of values. When you do this, Pandas automatically assigns an index starting with zero and sets the name of the series to None. Let's work on an example of this
  - Now we just call the `Series` function in pandas and pass in the students
  - We see here that the pandas has automatically identified the type of data in this Series as "object" and set the `dytpe` parameter as appropriate
  - The most important is how Numpy and thus pandas handle missing data
  - pandas does some type `conversion`. If we create a list of strings and we have one element, a None type, pandas inserts it as a None and uses the type object for the underlying array
  - if we create a list of numbers, integers or floats, and put in the None type, pandas automatically converts this to a special floating point value designated as `NaN`, which stands for `"Not a Number"`
  - `NaN` is `*NOT* equivalent` to `None` and when we try the equality test, the result is False
