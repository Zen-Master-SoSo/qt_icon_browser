# qt_icon_browser

Displays all possible built-in (theme) icons.

### Main window

<img width="640" height="797" alt="window" src="https://github.com/user-attachments/assets/728bcb4d-d8ae-4012-8c2f-0374762a97d5" />

All the icons are shown, grouped into different categories. The last category displays 
pixmaps, instead of icons.

### Copy code

Click any of the icons to copy the python code to create the icon to the clipboard. 

For example, clicking on the first icon shown in the screenshot above copies the following to the clipboard:

```python
QIcon.fromTheme("address-book-new")
```
Clicking on a pixmap from the last category copies this code to the clipboard:

```python
QApplication.style().standardIcon(QStyle.SP_MessageBoxWarning)
```

