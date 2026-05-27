# Touchless

***AI Workshop***  
***Université du Québec à Chicoutimi (UQAC) – Winter 2026***

## 📖 Project description

### Touchless is an AI project aimed at providing contactless gesture control for general PC functions. 

The idea addresses an everyday problem: wanting to interact with a screen (such as rewinding a recipe video) when your hands are dirty. This solution is also aimed at the B2B sector, for example for industrial workers who use specialist software where touching a keyboard is impossible.

## 🚀 Features

* **Basic gestures**: Recognition of Grab, Screen, Move, Click, Swipe and Close actions.
* **System control**: Mouse movement and single click. Gesture predictions are translated into keyboard/mouse actions via Pyautogui.
* **Customisation**: The user can change the gesture or mapping, and a script detects and records the user’s symbol.
* **Custom training**: The user can click a training button to retrain the model using their own data.

## 🛠️ Setup
* You will need to set up a Python 3.12.7 environment to run the project. The requirements.txt file is located in py_scripts.
* You will also need the Rust framework.
* Once these are installed, we have provided launch.sh (Linux) and launch.ps1 (Windows) files to run the application and the API.


## 🛠️ Technological Tools

* **Languages**: Python and Rust.
* **Vision and AI**: OpenCV, MediaPipe, Scikit-learn and PyTorch.
* **Interoperability and System Control**: PyO3 and PyAutoGui.

## 👥 The Team and Task Allocation

- BOEHM Marin: Dynamic model
- HABIÉ Yann: Dynamic model
- MONARQUE Vincent: Static model
- SITHIDEJ Clara: UI and API
- TOURAINE Florian: UI and API
