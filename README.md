
# PassGen by Rayan v0.50

PassGen by Rayan is a free and open-source software using python. In a nutshell, the app is a strong password generator that generates infinite number of customized passwords up to the user's input. Its main goal is to help the users create a hard to crack password by providing various features:

- Customized password length (4-128)
- Enable/Disable alphabets
- Enable/Disable numbers
- Enable/Disable special characters
## User Interface

![App Screenshot](https://i.ibb.co/THtfjyp/App.png)
## Authors

- [@v0x45](https://github.com/v0x45)
## Build it yourself

PassGen by Rayan is a free and open-source software, to compile the app yourself using python:
- install the following libraries:
```bash
  python -m pip install ttkbootstrap
  python -m pip install pyperclip
  python -m pip install Pillow
  python -m pip install nuitka
```

- Afterwards, compile the code with [Nuitka](https://github.com/Nuitka/Nuitka) using the following command (Change ```<>``` to the correct directory path):
```batch
py -m nuitka --mingw64 .\PassGen-by-Rayan-v0.50.py --standalone --onefile --windows-disable-console --windows-icon-from-ico=PassGen_by_Rayan_x96.ico --include-data-dir=<C:/Users/v0x45/Desktop/PassGen-by-Rayan/Icons=Icons> --enable-plugin=tk-inter
```
## Acknowledgements

 - [def get_pos()](https://stackoverflow.com/a/65530528) & [def move_window()](https://stackoverflow.com/a/65530528) were excerpted from [furas](https://stackoverflow.com/users/1832058/furas).
 - The code that positions the application window in the center of the screen was excerpted from [yagisanatode](https://yagisanatode.com/2018/02/24/how-to-center-the-main-window-on-the-screen-in-tkinter-with-python-3/)
 - Great tkinter tutorial playlist [freeCodeCamp.org](https://www.youtube.com/playlist?list=PLCC34OHNcOtoC6GglhF3ncJ5rLwQrLGnV)
## Used Libraries/APIs

 - [1] I. Dryer, 2021. URL: https://github.com/israel-dryer/ttkbootstrap.
 - [2] G. Rossum, 1992. URL: https://github.com/python/cpython/blob/3.10/Lib/os.py.
 - [3] G. Rossum, 1994. URL: https://github.com/python/cpython/blob/3.10/Lib/random.py.
 - [4] G. Brandl, 2008. URL: https://github.com/python/cpython/blob/3.10/Lib/tkinter.py.
 - [5] F. Drake, 2000. URL: https://github.com/python/cpython/blob/3.10/Lib/webbrowser.py.
 - [6] A. Sweigart, 2011. URL: https://github.com/asweigart/pyperclip.
 - [7] F. A. Clark. 2015. URL: https://github.com/python-pillow/Pillow.
