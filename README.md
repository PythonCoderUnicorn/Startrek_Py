
# Starfleet Academy Python 

### Welcome to Starfleet Academy Python! 

This Python respository will show you all the essentials that every Starfleet Officer requires. As you may already know, the vast majority of Federation officers use Python in their daily job duties. The United Federation of Planets has made Python the standard for writing it's applications and software. 

Knowing Python allows you to create, modify, repair and problem solve various issues that arise when on a Starship or on a Starbase. The lastest Federation News poll shows that 87% of Captains look for Python skills on Officer's profile. The best way to learn is to practice, so for each Notebook, you should practice running the code then make changes that you want.


### Getting Started

#### Installation of Python 
<br>
<h4> For Mac and Linux users </h4> Python is already installed. Find 'Terminal' on your computer. Once it opens, type <code> python3 </code> and hit enter. 
You should see :
<code>
Python 3.7.3 (default, Dec 13 2019, 19:58:14) 
[Clang 11.0.0 (clang-1100.0.33.17)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
</code> 
Now type <code> exit() </code> and hit enter to exit out of the Python shell
<br>
<br>
<h4> Using a text editor to write Python </h4>
Using a text editor is needed to write and run Python, some options are: VScode, Atom and Sublime (there are many). The 3 listed are free and are easy to install. Once installed, open new file, enter: 
<code> print(" Hello Starfleet Academy!") </code>

then save the file as <code> Hello.py </code> 
Save the file on desktop for starting out example.
- notice where in your computer's directory it is saved, you need to know where this file is to run it in the terminal.

run the program from Terminal: 
In the terminal enter <code> pwd </code> to see where you are in directory. If you see <code> /Users/<"your_name"> </code> then enter <code> cd Desktop </code>, this takes you to the Desktop. 
If you saved the file on your desktop, then you should see the Hello.py file when you enter <code> ls </code> , if you see it then you are good to go on running this program. Now enter in the terminal  <code> python3 Hello.py </code> and hit enter.

<br>
<br>
<h4> You just created your first app ! </h4>
<br>


<br>

- Note: Running python on your computer using the terminal and text editor works offline incase there is a power outage and the wifi goes out.

- How to install Python for everyone's OS (Windows, Mac, Linux), [Python 3 Installation](https://realpython.com/installing-python/) 

- It is important to learn basic Linux commands when using the terminal, especially when you are deployed on a Starbase and need to know where files and folders exist. Learn more [Linux Commands](https://www.hostinger.com/tutorials/linux-commands)

#### Installation of Jupyter Notebook 

<h4> Installion of Anaconda </h4>

What is Anaconda? It is a software package that makes coding in Python easier and simpler. It is free and most importantly it comes with software such as Jupyter Notebook, Jupyter Lab, RStudio (for statistics) and more.

Why install it? This option is recommended regardless if you use just the terminal method to run Python. Running Python in Jupyter Notebooks is very easy and commonly used by Starfleet. Jupyter Notebooks allow you to write python and run it all in one place, no terminal use needed. Jupyter Notebook files have an ending ".ipynb" meaning Interactive Python Notebook. Another reason to install it is the themes available to make Jupyter to your liking. 
<br>
- Note: Jupyter Notebook does require internet connection to run and save files. 
<br>
- Installing Anaconda package in the terminal for Mac users: [Anaconda Installation](https://mas-dse.github.io/startup/anaconda-macosx-install/)

- After installing Jupyter Notebook, you can edit theme, font size, etc that interests you [Jupyter Themes](https://github.com/dunovank/jupyter-themes)

<h4> Running Python in Jupyter Notebook </h4>
<br>
Open the Anaconda application, either by:
<br>
<br>
- Opening the Terminal and moving to the directory where you want Notebook files to be saved. If you want files saved in Documents folder, go to Documents in the Terminal, type <code> jupyter notebook </code> then hit enter. This causes the Jupyter Notebook to open a web browser window tab, from there you can create a new Python3 file, look for drop down menu on top right corner. 
<br>
<br>
- Click on Anaconda application to open main menu, click on "Launch" Jupyter Notebook, this opens up the Notebook in web browser window tab, from there you can create a new Python3 file, look for drop down menu on top right corner. 
<br>
<br>
Now in the Notebook, enter:  <code>print(" Hello Starfleet Academy!")</code> then Shift + Enter to run the python script or you can press button 'Run". To give the Notebook a name, go to File > Rename... > type: Hello > hit enter. Now your Notebook is saved as "Hello.ipynb" in your folder.
<br>
<br>
To shutdown the running Notebook in the terminal: <code> Ctrl + C </code>, then when asked if you want to shutdown the kernel, enter <code> y </code>, this shutsdown the notebook 

### Google Collab Notebook

You can run Jupyter Notebook files in Google Collab Notebook, you need a Google account and there is dark mode available. 

- Pros of Collab: you don't need to download Python libraries onto your computer (such as Pandas, Seaborn, etc, these libraries will be used later). It works like Jupyter Notebook, so it is easy to run python. Your files get saved, can be stored and viewed in Google Drive.
- Cons of Collab: inputing a dataset like CSV is not simple and easy like Jupyter. Collab needs to know permissions for accessing a file if from the file is in the Drive, where the file is. This is a minor thing, but when comparing reading in a CSV or Excel data it is a little more code to make it work. 
[Loading CSV into Collab Notebook](https://towardsdatascience.com/3-ways-to-load-csv-files-into-colab-7c14fcbdcb92?gi=71d62d1e9ff5)


```python

```
