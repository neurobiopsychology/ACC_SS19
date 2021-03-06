# Practice sessions

Only those of you that worked on the Basic-Python-Test are allowed to take part in the programming exercises, which is necessary to pass this course.
Since this course requires basic programming skills in python to solve the weekly exercises, the aim of this first exercise is for us to assess your skills, and also for you to test if you need to do a basic python course yourself.

### Programming exercises

One sheet per week:
- work in groups of 3-4 people
- **properly commented** solutions should be submitted as Python notebooks via Github classroom

Feedback meeting on Thursday (with tutors) to:
- explain the solution of the last exercise to you
- go over the next exercise sheet
- answer your questions

Requirement to pass this lecture:
- work on more than 70% of the programming exercises
- (there will be no exam at the end of term)


# Setup your homework environment

### a) Install Python via Conda

To be able to run Jupyter Notebooks you will need Python. Follow this instruction to get everything up and running.

We recommend to use Anaconda:

Download and install Anaconda from https://www.anaconda.com/distribution/ that contains all important Python packages.

If you have limited diskspace install Miniconda https://conda.io/miniconda.html instead, which contains only conda and Python. Follow the installation instructions on the website.

Make sure to adapt your PATH variable!

### b) Setup the cv environment

Download acc.yml. Then in a terminal navigate to the directory (cd PATH) where you saved acc.yml and run
```sh
conda env create -f acc.yml
```

### c) Activate the environment

Always activate the environment when you work on the homework.

Linux/Mac OS:
```sh
source activate acc
```

For Windows:
```sh
activate acc
```

### d) Deactivate the environment

After you are finished using the environment, you have to deactivate the environment. To deactivate the environment again run

Linux/Mac OS:
```sh
source deactivate
```

For Windows:
```sh
deactivate
```

### e) Run Jupyter Notebooks

After you installed Python and the environment verify you are able to run the notebook server by opening your command line. Navigate to the directory where you downloaded the notebook-files and run jupyter in that directory:

```sh
jupyter notebook
```

Usually a browser window should open up. If not, open your favorite web browser and navigate to localhost:8888/tree. You will be presented with a list of files, choose Python_exercise_final.ipynb: You are good to go now and can start working on the initial exercise right away!

After you are done with the exercise, change the filename to [yourlastname_yourfirstname_pretest.ipynb] and upload it on the STUDIP folder called Pre_Test_Submission.

If you have any problems with installing the environment do not hesitate to write an email to the tutors:
Anne Lang: anlang@uni-osnabrueck.de
Franca Boße: frbosse@uni-osnabrueck.de
Minseok Kang: mikang@uni-osnabrueck.de

# Short Introduction to Notebooks

### a) Notebook User Interface

There are two (important for you) kinds of cells: Markdown and Code. You can change the cell type with the drop-down menu in the toolbar.
There are two different modes: edit mode and command mode. To enter command mode hit Esc, for edit mode hit Enter. If you are in command mode hit B to insert a new cell.
To evaluate a cell hit Ctrl+Enter. An overview of all shortcuts can be found in Help → Keyboard Shortcuts.

For more information go to: Help → User Interface Tour

### b) Markdown cells

In a Markdown cell you can format your text in an intuitive way. Hit Enter or double click to edit a cell.

You can write e.g.:
- italic text (Markdown format: * text *)
- bold text (Markdown format: ** text **)
- even Latex formulas (Markdown format: $ formula $)

### c) Code cells

In a Code cell you can add code and run the cell using Ctrl+Enter. Since Jupyter Notebook is associated with the IPython kernel it only runs Python code.

### d) Change a filename

You can easily change the name of a file under file → rename
