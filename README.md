# Tkinter-GUI
A simple GUI using  Python with Tkinter and sqlite3. Parts Manager  full CRUD operations


### Install dependencies
pipenv install

### Run script
python part_manager.py


### Compile with Pyinstaller

### Windows
pyinstaller --onefile --windowed part_manager.py

### Mac
pyinstaller --onefile --add-binary='/System/Library/Frameworks/Tk.framework/Tk':'tk' --add-binary='/System/Library/Frameworks/Tcl.framework/Tcl':'tcl' part_manager.py
