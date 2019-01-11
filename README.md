# labelImg

Label image list by make a class label.

## BUG!!!
1. Maybe there have some unfound bugs

## Python3 + Qt5

```
sudo apt-get install pyqt5-dev-tools
sudo pip3 install -r requirements/requirements-python3.txt
```

### Compile

```
make py3qt5
```
### Run
```
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

## Reference from github.com/spark001/labelimg
