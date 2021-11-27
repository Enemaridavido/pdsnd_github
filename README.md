>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Project: 29th AUG 2021 README.md :17th OCT 2021


### **US Bikeshare Data Analysis Project**

### **description:**
In this project, _Python_ is used to explore data related to bike share systems for three major cities in the United States — _Chicago, New York City,_ and _Washington_.
- The source code takes in raw input from the user to create an interactive experience.
- According to the input the code will import the data and will provide information by computing descriptive statistics.

## **Files used:**
* bikeshare.py

## **Credits:**
* Richard Kalehoff (Udacity mentor)
    - [https://github.com/richardkalehoff](https://github.com/richardkalehoff)
    - [https://twitter.com/richardkalehoff](https://twitter.com/richardkalehoff)

* Juno Lee (Udacity Mentor)
    - [https://github.com/junolee](https://github.com/junolee)
    - [https://www.linkedin.com/in/junoleelj](https://www.linkedin.com/in/junoleelj)

* The data for all 3 cities that is used in this project can be accessed through the link mentioned below :
    - [City Data](https://drive.google.com/file/d/1km4EggJaSvHos_7KKFuHoJxbh-StyM4G/view?usp=sharing)

* The link for commit message style reference for this project is given below :
    - [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/)


    ## **Softwares needed:**
    * _Python 3, NumPy,_ and _Pandas_ installed using _Anaconda_
    * A text editor, like _VS Code_ or _Atom_.
    * A terminal application (_Terminal_ on _Mac_ and _Linux_ or _Cygwin_ on _Windows_).

    ## **Installation links for softwares:**
    * [Git for windows - for terminal application using Git Bash](https://gitforwindows.org/)
    * [Python using Anaconda (latest version for windows)](https://www.anaconda.com/distribution/)
    * [Visual Studio Code Editor (for windows)](https://code.visualstudio.com/docs/setup/windows)

    ## **Links for software tutorials:**
    * [Git - Reference](https://git-scm.com/docs)
    * [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
    * [VS Code Documentation](https://code.visualstudio.com/docs)

    ## **Code explained in Detail:**
    ### **How the program works:**
    The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:

    * Which city would you like to explore? _Chicago_, _New York_, or _Washington_?
    * Would the user like to filter the data by month, day, or all?
    * (If they chose month) Which month - _january_, _february_, _march_, _april_, _may_, _J
    june_ or _all_?
    * (If they chose day) Which day - _monday_, _tuesday_, _wednesday_, _thursday_, _friday_, _saturday_, _sunday_ or _all_?

    The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to restart or exit.
