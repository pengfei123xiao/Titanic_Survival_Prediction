# Titanic_Survival_Prediction
Predict survivals in titanic

### Requirements
**Python 2.7** and following python packages

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

[Jupyter Notebook] is needed.
(http://jupyter.readthedocs.io/en/latest/install.html#optional-for-experienced-python-developers-installing-jupyter-with-pip)

For macOS users，install [homebrew](http://brew.sh/)，and python(brew).

```bash
$ brew install python
```

Use following commands to install required python packsges:

```bash
$ pip install numpy pandas matplotlib scikit-learn scipy jupyter
```


### Codes
Example codes are in file `titanic_survival_exploration_cn.ipynb` ,
assist codes are in file `titanic_visualizations.py` ,
some extra codes are needed to accomplish this project.


### Run
If run in command line，make sure the current directory is `titanic_survival_exploration/`,
then input:
```bash
$ jupyter notebook titanic_survival_exploration.ipynb
```
Then, Jupyter Notebook is launched, showing the files in the browser.

If not familiar with jupyter, see these two links:
- [Jupyter使用视频教程](http://cn-static.udacity.com/mlnd/how_to_use_jupyter.mp4)
- [为什么使用jupyter？](https://www.zhihu.com/question/37490497)


### Data
The data is in file `titanic_data.csv` .
Characteristics:
- **Survived**：是否存活（0代表否，1代表是）
- **Pclass**：社会阶级（1代表上层阶级，2代表中层阶级，3代表底层阶级）
- **Name**：船上乘客的名字
- **Sex**：船上乘客的性别
- **Age**：船上乘客的年龄（可能存在 `NaN`）
- **SibSp**：乘客在船上的兄弟姐妹和配偶的数量
- **Parch**：乘客在船上的父母以及小孩的数量
- **Ticket**：乘客船票的编号
- **Fare**：乘客为船票支付的费用
- **Cabin**：乘客所在船舱的编号（可能存在 `NaN`）
- **Embarked**：乘客上船的港口（C 代表从 Cherbourg 登船，Q 代表从 Queenstown 登船，S 代表从 Southampton 登船）
