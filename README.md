# datium-data-science-test
***
### Section A
For this section, all the codes, explainations, and reports are in Jupyter Notebook format. Running on Python >= 3.7 

- Clone this repo.

```
$ git clone https://github.com/faizmisman/datium-data-science-test
```
- Setup environment and installing required packages.

  - If you use conda, you can install environment via ```environment.yml```
    ```
    $ conda env create -f environment.yml
    ```

  - Using pip 
    ```
    $ pip install -r requirements.txt
    ```
- Before running the notebook, you need to initiate the mlflow server
```
$ mlflow server --backend-store-uri sqlite:///mlflow.db --default-artifact-root ./artifacts --host localhost
```
- Open another terminal run notebook and choose ```Datium_DataScience_test-A.ipynb```
