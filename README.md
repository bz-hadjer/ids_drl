To run the code included in this repo:

1. Clone or download the repository.

2. Download the [Anaconda](https://www.anaconda.com/products/individual) version suitable for your OS.

3. Create a virtual environment with the same libraries we used by running:
```bash
$ conda env create -f conda_env.yml
$ conda activate ids_drl
```

4. Launch `jupyter notebbok` and follow the notebooks in this order:
   1. Data Preprocessing
   2. Defining the environment
   3. Training and Results

5. The final model that we found is in `ids_drl_model.zip`, you  can skip training and load it directly.