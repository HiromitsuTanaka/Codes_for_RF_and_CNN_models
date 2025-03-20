Cell-type-Nucleus
===========
### Title
*journal name*

[Read Link]() 

<!--todo : summary-->

## Preparation

### Environment
1. Clone the repository
   ```cmd
   git clone https://github.com/HiromitsuTanaka/Cell-type-Nucleus.git
   ```
- model
  - python 3.10.11
  - NVIDIA RTX A6000

  The library names and versions are shown in [requirements.txt](https://github.com/HiromitsuTanaka/Cell-type-Nucleus/blob/main/requirements.txt)
  
  Operations are run in Jupyter environment
  
  ```cmd
   cd Cell-type-Nucleus
   ```
   ```cmd
   python -m venv env
   ```
   Next
  ```cmd
   absolute path/env/scripts/activate
   ```
   If necessary
   ```cmd
   python -m pip install --upgrade pip
   ```
   Finally
   ```cmd
   python.exe -m pip install -r requirements.txt
   ```

    Launch jupyter in the activated environment

### Data preparation
If sample data are necessary, download the nucleus data from Zenodo <!--todo : Zenodoのリンクを貼る？我々のデータが必要なら-->.  

1. Activate the environment
   ```cmd
   absolute path/env/scripts/activate
   ```

2. Transfer the data to a directory that you want to performe.

    [Paper-CreateTrainImage](https://github.com/HiromitsuTanaka/Cell-type-Nucleus/blob/main/model/Paper-CreateTrainImages.ipynb)

To generate data for training, we used [ImageDataGenerator](https://keras.io/ja/preprocessing/image/)


 ### Saliency
- Execute the following code in the comand prompt environment

    [Paper-TrainModel](https://github.com/HiromitsuTanaka/Cell-type-Nucleus/blob/main/py/Paper-IG_tissue.py)

We referred to [PAIR-code/saliency](https://github.com/PAIR-code/saliency)


 
## License
This code is under the GPLv3 License

