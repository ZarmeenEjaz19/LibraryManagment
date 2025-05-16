#  Library Management System (Tkinter GUI)

This is a simple **Library Management System** built using **Python's Tkinter library**. The app allows you to manage physical 
and digital (eBook) books through a graphical user interface.

---

## Features

- Add books with Title, Author, and ISBN
- Mark books as eBooks and specify file size in MB
- Lend and return books
- Remove books from the collection
- View books by a specific author
- Easy-to-use GUI built with Tkinter

---

##  Project Structure


LibraryTkinter/
│
├── library_gui_tkinter.py # Main application file
├── requirements.txt # Python packages (auto-generated)
├── .gitignore # Ignore virtual environment folder
├── README.md # Project documentation
└── venv_tkinter/ # Virtual environment (excluded from GitHub)

---

##  Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)

---

## ▶ How to Run

1. **Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/LibraryTkinter.git
cd LibraryTkinter

Create a virtual environment
python3 -m venv venv_tkinter
source venv_tkinter/bin/activate  # On macOS/Linux


Install dependencies

pip install -r requirements.txt

Run the app
python library_gui_tkinter.py



