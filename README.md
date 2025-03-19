# Setting Up Python and Jupyter Notebooks
CREDIT: A good portion of the content of this workshop is adapted from the previous work of [@Indiiigo](https://github.com/Indiiigo). All credits should be given to her, as she has done a great job of putting this together. I only condensed the material into a single source.

## What are Jupyter Notebooks?

Jupyter Notebooks are interactive documents that combine live code, visualizations, narrative text, equations, and other rich media in a single document. They're named after the programming languages they originally supported: **Ju**lia, **Py**thon, and **R**.

### Why Use Jupyter Notebooks?

Jupyter Notebooks offer several advantages that make them ideal for learning Python:

1. **Interactive Execution** - Run code blocks (cells) one at a time and see the results immediately
2. **Combination of Text and Code** - Mix explanations with executable code in a single document
3. **Visual Output** - Display charts, graphs, tables, and other visual outputs directly in the notebook
4. **Incremental Development** - Test and refine your code in small chunks
5. **Documentation** - Create self-documenting code with explanations and results together
6. **Shareable Format** - Easily share your work with others, including code, explanations, and outputs

For this tutorial series, Jupyter Notebooks allow you to read the explanations, see example code, run it yourself, and experiment with modifications all in one place.

## Installing Python

1. **Install Anaconda** (includes Python, Jupyter, and many scientific packages):
   - Recommended for beginners and data science work
   - Go to [anaconda.com/products/distribution](https://anaconda.com/products/distribution)
   - Download and install Anaconda for your operating system
   - This includes Python and Jupyter Notebooks in one complete package

2. **Alternative: Direct Python Installation:**
   - Go to [python.org/downloads](https://python.org/downloads)
   - Click the "Download Python" button for the latest version
   - Important: Check the box "Add Python to PATH" during installation

3. **Verify Installation:**
   - Open Command Prompt (Windows) or Terminal (Mac/Linux)
   - Type `python --version` and press Enter
   - You should see the Python version number if installation was successful

## Installing Jupyter Notebooks

1. **If you installed Anaconda:**
   - Jupyter is already installed and ready to use
   - You can launch it from the Anaconda Navigator or command line

2. **If you installed Python directly, install Jupyter using pip** (Python's package manager):
   - Open Command Prompt (Windows) or Terminal (Mac/Linux)
   - Type the following command and press Enter:
     ```
     pip install notebook
     ```
   - Wait for the installation to complete

## Understanding the Jupyter Interface

Once you've launched Jupyter Notebook, you'll see a web interface with a file browser. Here's what you need to know:

1. **Notebook Dashboard** - This is the main page showing files and folders
2. **Toolbar** - Contains actions like save, add cell, run cell, etc.
3. **Cell Types**:
   - **Code cells** - Contain Python code that can be executed
   - **Markdown cells** - Contain formatted text for explanations
   - **Raw cells** - Contain content that's not processed by Jupyter

### Working with Jupyter Notebooks

1. **Creating a New Notebook**:
   - Click the "New" button in the top right
   - Select "Python 3" (or the version you installed)

2. **Cell Execution**:
   - Run a cell with Shift+Enter
   - Run a cell and create a new one with Alt+Enter
   - Run a cell and stay on it with Ctrl+Enter

3. **Saving Your Work**:
   - Use Ctrl+S or click the disk icon
   - Notebooks are saved with a .ipynb extension

4. **Keyboard Shortcuts** (press H in command mode to see all shortcuts):
   - Enter: Switch to edit mode
   - Esc: Switch to command mode
   - A: Insert cell above current cell
   - B: Insert cell below current cell
   - DD: Delete current cell
   - M: Convert cell to Markdown
   - Y: Convert cell to Code

## Running Jupyter and Opening the Tutorial Files

1. **Starting Jupyter Notebook:**
   - Open Command Prompt (Windows) or Terminal (Mac/Linux)
   - Navigate to your project folder:
     ```
     cd path/to/Python_Refresher_Workshop
     ```
   - Start Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - This will open a new tab in your web browser with the Jupyter interface

2. **Opening the Tutorial Files:**
   - In the Jupyter browser tab, navigate to the "notebooks" folder
   - Click on "01_Variables_Strings_Numbers.ipynb" to open the first tutorial
   - You can now read and run the notebook cells

3. **Running Code Cells:**
   - Click on a code cell (the ones with the gray background)
   - Press Shift+Enter to execute the code and move to the next cell
   - The output will appear below the cell

## Tips for Learning with Jupyter Notebooks

1. **Experiment Freely** - Change code in the tutorial and run it to see what happens
2. **Take Notes** - Add your own markdown cells with notes to reinforce your learning
3. **Save Checkpoints** - Create checkpoints of your work using File > Save and Checkpoint
4. **Use Help** - Type `help(function_name)` in a code cell to get documentation

## Troubleshooting

- **If Python installation fails:** Try downloading the installer again or use Anaconda instead
- **If "python" is not recognized:** You may need to restart your computer after installation
- **If Jupyter won't start:** Make sure you installed it with `pip install notebook` or through Anaconda

Happy learning! If you have any issues, Python has a friendly community at [python.org/community](https://www.python.org/community/) where you can find help. 