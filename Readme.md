# Anuket Documentation

Welcome to the Anuket Project Documentation repository. This repository contains the source files for https://docs.anuket.io/

## Installation

To get started with the Anuket documentation locally, clone this repository:

```bash
git clone https://github.com/anuket-project/Anuket-documentation.git
cd Anuket-documentation
```

## Install the required dependencies:

### Verify Python and Pip Installation

Ensure Python and pip are installed and accessible in your environment.

```bash
python --version
pip --version
```

### Install Tox

Ensure Python and pip are installed and accessible in your environment.

```bash
pip install tox
```

### Verify Tox Installation

After installing tox, you should verify that it was installed correctly:

```bash
tox --version
```

If tox --version does not work, you may need to add the installation directory to your system's PATH. For example:

- On Windows, you might need to add the Scripts directory to your PATH. Usually, it's located at C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python<version>\Scripts\.

- On Linux/macOS, it might be in a directory like ~/.local/bin.

To add it to your PATH temporarily in the current session, you can use:

```bash
export PATH=$PATH:~/.local/bin  # Linux/macOS
```

For Windows, you can modify the PATH environment variable via the System Properties -> Environment Variables dialog.



## Building the Documentation

To build the documentation locally, you can use the following commands.

```bash
tox -e docs
```

## Open the Generated HTML

```bash
open _build/html/index.html  # macOS
xdg-open _build/html/index.html  # Linux
start _build/html/index.html  # Windows
```
