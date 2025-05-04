# Domain Adaptation of BERT to SuperCollider Code with an Ablation on Dataset Preprocessing

### Dependencies and External Libraries:

Transformers 4.51.3 <br/>
Tensorflow 2.18.0 <br/>
Datasets 3.5.1 <br/>

Keras >= 3.5.0 (3.8.0) <br/>
Numpy < 2.1.0, >= 1.26.0 (2.0.2) <br/>
Pandas 2.2.2 <br/>
Tqdm >= 4.66.3 (4.67.1) <br/>
Sklearn 1.6.1 <br/>
Torch 2.6.0+cu124 <br/>
Json 2.0.9 <br/>
Matplotlib 3.10.0 <br/>


### Environment Set-Up:
First make sure you have the required libraries installed: <br/>
```bash
pip install transformers
pip install tensorflow
pip install datasets
````

The project was run on a single T4 GPU on Colab, but it can also work on a local system as long as system requirements are met. <br/>

The datasets can be found in [this Dropbox link](https://www.dropbox.com/scl/fo/6zq5jduzv9yoqpu0sk8p9/AM9vwTk5aqHl2rAmKfmAg48?rlkey=xxo8vb55784igy4qkaxdtd7ad&st=yuui0fyh&dl=0) since they are too large for Github upload.
The code for the benchmarking is in the files as well.
