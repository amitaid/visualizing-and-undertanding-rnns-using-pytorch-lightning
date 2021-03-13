# visualizing-and-undertanding-rnns-using-pytorch-lightning
Based on "Visualizing and Understanding Recurrent Networks" by Andrej Karpathy, Justin Johnson, Li Fei-Fei (2016)

Also based on https://github.com/rnbwdsh/visualizing-and-undertanding-rnns-using-pytorch-lightning


## Instructions:
1. Clone the repo
2. Run `pip install -r requirements.txt` (NOTE: If this fails because of *tensorflow*, try [this page](https://stackoverflow.com/questions/38896424/tensorflow-not-found-using-pip) for a solution for your os)
3. Modify config.py for the dataset and output directories you want to use. If running on Colab, I recommend [mounting a Google Drive](https://medium.com/@rushic24/mounting-google-drive-in-google-colab-5ecd1d3b735a) and setting the output dir to the mounted drive.
4. Run `python train.py` to train the models in the currently selected dataset
5. Use *main.ipynb*
