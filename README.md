#  Library Management System (GUI-based)

This project is a simple **Library Management System** implemented in **Python**, featuring two GUI versions:

-  **PyQt5 GUI**
-  **Tkinter GUI**

It allows users to:
- Add physical and eBooks
- Lend and return books
- Remove books
- View books by author
- See a list of available books

---

##  Features

###  Common Features
- Add books with Title, Author, and ISBN
- eBook support with size input (MB)
- Display all available books
- Search for books by author

###  PyQt5 Version
- Clean, modern interface using PyQt5
- Dynamic eBook size input toggle
- List of added books with display

###  Tkinter Version
- Interactive interface using Tkinter
- Lend, return, and remove book functions
- Error handling using message boxes
- Search books by author's name

---

##  Project Structure

.
├── pyqt_library_gui.py # PyQt5 version of the app
├── tkinter_library_gui.py # Tkinter version of the app
├── README.md 


. **Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/LibraryTkinter.git
cd LibraryTkinter

Create a virtual environment
python3 -m venv venv_tkinter
source venv_tkinter/bin/activate  # On macOS/Linux

##  Getting Started

###  Requirements

Install required dependencies:

```bash
pip install pyqt5
Tkinter is included with standard Python installations, no need to install it separately.

▶️ Run PyQt5 App

python pyqt_library_gui.py

▶️ Run Tkinter App

python tkinter_library_gui.py
