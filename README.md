Dependencies and External Libraries:

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


Environment Set-Up: <br/>
First make sure you have the required libraries installed: <br/>
!pip install transformers <br/>
!pip install tensorflow <br/>
!pip install datasets <br/>

The project was run on a single T4 GPU on Colab, but it can also work on a local system as long as system requirements are met. <br/>

There are two files, nontagged and tagged, which are the code for running the nontagged data and the tagged data, respectively. The code for the benchmarking is in the files as well.
