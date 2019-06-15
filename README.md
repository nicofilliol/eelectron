# Eelectron

This is a starter project that uses [Eel](https://github.com/ChrisKnott/Eel) and [Electron](https://electronjs.org/) in order to create a desktop application which uses HTML/CSS/JavaScript as frontend and Python as backend.

## Getting Started

These instructions will get you a copy of the starter project up and running on your local machine for development and testing purposes.

### Prerequisites

In order for the starter project to work properly, you need to install Eel and Electron on your local machine.

Install Eel from pypi with `pip`:

```
pip install eel
```

In order to install Electron, first install `node.js` and `npm` using homebrew (alternatively use the installer from [here](https://nodejs.org/en/download/)):
```
brew install node
```

Next, we can install Electron globally using the following command:

```
npm install electron -g
```


### Installing

You can install this starter project simply by cloning the repository to your local machine:

```
git clone https://github.com/nicofilliol/eelectron.git
```

Check if everything works by running the following commands:

```
cd eelectron
python main.py
```

If everything was installed properly, the starter app should open with Electron and a window saying `Hello, World!`. Furthermore, check the Python console to make sure that the communication between Python and JavaScript through Eel works properly. If the output is similar to the following, everything is alright:

```
Hello from Python World!
Hello from JavaScript World!
```

## Where to go from here

This repository serves as a starter project for Eelectron apps. Go ahead and start coding your GUI with HTML/CSS and JavaScript and use Python to compute things in the backend.

## Built With

* [Eel](https://github.com/ChrisKnott/Eel) - Module used for starting and communicating with Electron
* [Electron](https://electronjs.org/) - Dependency Management
