# Traplink

Traplink is a simple desktop app that lets you anonymously post links with optional descriptions to a shared Firestore database.  
**Note:** Currently, Traplink is locked for use in Europe only.

---

## Features

- Post links anonymously with a title and optional description.  
- View all posts from other users in real-time.  
- Simple and clean Tkinter GUI with dark theme.

---

## Requirements

To run Traplink, you need:

- **Python 3.7 or higher**  
- **Tkinter GUI toolkit** (usually bundled with Python)  
- **Firebase Admin SDK for Python**  
- **Firebase project with Firestore enabled** and a service account JSON key file  

---

## Installation and Running Guide

### 1. Install Python

- Download and install Python 3.7 or higher from [python.org](https://www.python.org/downloads/).  
- Ensure Python and `pip` are added to your system PATH during installation.

### 2. Verify Tkinter is installed

- Tkinter is usually included by default with Python on Windows and macOS.  
- On Linux, you may need to install it manually (see below).

### 3. Install Firebase Admin SDK

Open your terminal or command prompt and run:

```bash
pip install firebase-admin
```

---

## Platform-specific Instructions

### Windows

1. Download Python 3.7+ from [python.org](https://www.python.org/downloads/windows/).  
   During installation, check “Add Python to PATH”.

2. Tkinter is included by default on Windows.

3. Open Command Prompt and run:

```bash
pip install firebase-admin
```

4. Place your Firebase service account JSON file (e.g., `traplink-d7e7a-firebase-adminsdk-fbsvc-fb0edc5d34.json`) in the same folder as `traplink.py`.

5. Run the app:

```bash
cd path\to\your\folder
python traplink.py
```

---

### macOS

1. Install Python 3.7+ via Homebrew or download from [python.org](https://www.python.org/downloads/mac-osx/):

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install python
```

2. Verify Tkinter is installed. If missing, install via Homebrew:

```bash
brew install python-tk
```

3. Install Firebase Admin SDK:

```bash
pip3 install firebase-admin
```

4. Place your Firebase service account JSON file in the same folder as `traplink.py`.

5. Run the app:

```bash
cd /path/to/your/folder
python3 traplink.py
```

---

### Linux (Ubuntu/Debian)

1. Install Python 3, Tkinter, and pip:

```bash
sudo apt update
sudo apt install python3 python3-tk python3-pip
```

2. Install Firebase Admin SDK:

```bash
pip3 install firebase-admin
```

3. Place your Firebase service account JSON file in the same folder as `traplink.py`.

4. Run the app:

```bash
cd /path/to/your/folder
python3 traplink.py
```

---

### Fedora / Red Hat

1. Install Python 3, Tkinter, and pip:

```bash
sudo dnf install python3 python3-tkinter python3-pip
```

2. Install Firebase Admin SDK:

```bash
pip3 install firebase-admin
```

3. Place your Firebase service account JSON file in the same folder as `traplink.py`.

4. Run the app:

```bash
cd /path/to/your/folder
python3 traplink.py
```

---

### Arch Linux

1. Install Python 3, Tkinter, and pip:

```bash
sudo pacman -S python python-tkinter python-pip
```

2. Install Firebase Admin SDK:

```bash
pip install firebase-admin
```

3. Place your Firebase service account JSON file in the same folder as `traplink.py`.

4. Run the app:

```bash
cd /path/to/your/folder
python traplink.py
```

---

## How to use

- Click **Post Anonymously** to add a new link post.  
- Enter the link, a post name, and optionally a description.  
- Click **Refresh Page** to reload all posts.  
- Posts show anonymously with link, name, and optional description.

---

## License

This project is private and intended for use only in Europe.

---

## Contact

For any issues or questions, please contact the developer.
