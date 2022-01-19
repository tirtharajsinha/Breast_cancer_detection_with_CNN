# breast_cancer_detection_app
> breast_cancer_detection_app using flask and deep learning

### Domain of the project : Biomedical Image Processing (14)

## project code requirement
1. core Backend Language : python3
2. core Backend frameworks/packages : Tensorflow, Keras, scikit-learn , numpy, pandas, matplotlib, seaborn, opencv, pillow etc.
3. Tools | IDE - data science : Jupyter Notebook , Other : Pycharm | Text Editor : VS Code | online : kaggle, google colab
4. Frontend Language : web Tecknoledgies(HTML,CSS,Js)
5. Application Framework : flask
6. version control system : git | remote-repository-platform : github.com


## notes
1. use of python 3.8 is reccomended(as 3.9 not tested)
2. use of virtual environment reccomended.
3. install requirements.txt using ```pip install -r requirements.txt``` before using the app
4. paste model.json & model.h5 in ``` static/model/```
5. run ```python manage.py runserver ``` or ```python app.py``` to run app



## How to get trained model? (Error : model/model.h5 and model/model.json file not found)
> If you get some error like model.h5 not found or model.json not found that means you have not put the files in /model folder.
### now question is how do you get that files?
1. You have to run all the cells of  ```/Project III core/breast_cancer_detection_with_CNN.ipynb``` file.
2. It will generate the model.h5 and model.json files.
3. Now copy the two files and paste it in Project III app/static/model folder.
Now you are clear of that shit error.