# labelImg

Label image list by make a class label.

## BUG!!!
1. Maybe there have some unfound bugs

# linux
```
git clone git@github.com:zsmatlab/labelimg.git
```

## Python2 + Qt4
```
sudo apt-get install pyqt4-dev-tools
sudo pip install lxml
cd ROOT/labelimg/
make qt4py2
python2 labelImg.py
```

## Python3 + Qt5

```
sudo apt-get install pyqt5-dev-tools
cd ROOT/labelimg/
sudo pip3 install -r requirements/requirements-python3.txt
make qt5py3
python3 labelImg.py
```

### Steps

1. Click 'Change default saved annotation folder' in Menu/File
2. Click 'Open Dir'
3. Click 'Create RectBox'

The annotation will be saved to the folder you specify.

### Hotkeys

|    Keys  |                 Function                 |
|----------|------------------------------------------|
| Ctrl + r | Change the default annotation target dir |
| Ctrl + s | Save                                     |
| Ctrl + u | open dir                                 |
| Ctrl + s | Save                                     |
| Ctrl + d | Copy a bounding box                      |
| w        | Create a bounding box                    |
| d        | Next image                               |
| a        | Previous image                           |
| Space    | After choosing one label, quick add it   |


## Note： 
1. 文件路径不要包含中文字符

## 引用自
```
github.com/spark001/labelimg
 ```
