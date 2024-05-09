Hello,

We have 2 main codes: training.ipynb, and inference.ipynb

If you want to try the code, please place the 'eece490proj' folder in your C: folder.

We made use of a GPU for training; if you want to use a GPU you can do:

pip3 install torch==2.2.0+cu121 torchvision==0.17.0+cu121 torchaudio===2.2.0+cu121 --index-url https://download.pytorch.org/whl/cu121

If you wish to train the model, you need to have the 'xView\train\images' folder, which contains the respective images corresponding to the labels in the 'xView\train\labels' folder.

If you wish to download the dataset from the place we downloaded it: https://challenge.xviewdataset.org/data-download   (recommended link)

Another possible link to get the dataset (I didn't try it): https://datasetninja.com/xview

Thank you.
