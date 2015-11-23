This is an experiment at uploading a screenshot of the currently selected Jupyter cell (and output) to Imgur. It should run on Jupyter notebooks 4.0 and greater.

Open jupyter-shot.ipynb and run the cells. You should then be able to select any cell and press `r` to see a screenshot of the cell appear in a new window with an Imgur url.

If you have conda installed, you can run the notebook with:

```
conda env create
source activate jupyter-shot
ipython notebook
```