# triple-bubbles

Code for solving the 1D triple bubble problem with log-convex density.

## Animation
The animation for density f_1 is [triple.mp4](https://github.com/natso26/triple-bubbles/raw/master/triple.mp4). The animation for density f_2 is [triple2.mp4](https://github.com/natso26/triple-bubbles/raw/master/triple2.mp4).

## Code
The files [Triple Bubble.ipynb](Triple%20Bubble.ipynb) and [Triple Bubble 2.ipynb](Triple%20Bubble%202.ipynb), respectively, generate these animations.
These are written in Julia. To run them, you can follow these instructions.

1. Download the files [Triple Bubble.ipynb](https://github.com/natso26/triple-bubbles/raw/master/Triple%20Bubble.ipynb) and [Triple Bubble 2.ipynb](https://github.com/natso26/triple-bubbles/raw/master/Triple%20Bubble%202.ipynb) to your computer. (These links point to the files; you can right click and download on most browsers.)

   Note: the downloaded files should have the extension `.ipynb`. If for some reason they are downloaded as `.ipynb.txt` (which happens in Safari), delete the extra `.txt` in the file name to make the extension just `.ipynb`. You can do the renaming on your computer after downloading or on JuliaBox after Step 3.

2. Log in to https://www.juliabox.com using either GitHub, Google, or LinkedIn.

3. Upload the code files to JuliaBox. To do this, click the `Upload` button on the topright corner.
The files will then appear in your JuliaBox.

4. You can now run the files. To do so, click on the file. You will be directed to a Jupyter Notebook environment.

   The file consists of many cells. (Each box with a label like `In [1]` is a cell.) You can click on any cell to select it, and clicking `Run` on the toolbar above will run the current cell. The label `In [*]` indicates that a cell is being run. To run the whole file, you can keep pressing run and go through the cells in order. Alternatively, run all cells automatically one after another by clicking the fast forward icon. (Keep in mind that these interfaces may change in the future.)

   The cell that creates the animation is the last one. However, most cells depend on previous cells, so it is best to run the cells in order. All cells except the last should take only seconds to run, and the last one takes 20-30 minutes to run. When the last cell finishes running, an animation will appear below it, which can then be viewed. If the animation cannot be viewed (which happens sometimes), the file `triple.mp4` or `triple2.mp4` (depending on which code file is run) will be created in JuliaBox, and the animation can be viewed from there. These files are the same as the ones stored here on GitHub.
