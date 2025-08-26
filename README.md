# Real-Time Recognition and Translation of BISINDO with MediaPipe and LSTM
This thesis presents the development of a real-time recognition and translation system for Bahasa Isyarat Indonesia (BISINDO). The system leverages MediaPipe Holistic to extract multimodal body landmarks and employs a Long Short-Term Memory (LSTM) network to model temporal gesture sequences.

## Setting up venv for ipynb

Set up a Python virtual environment (venv) for use with Jupyter notebooks inside VS Code

Create a Virtual Environment
```sh
python -m venv .venv
```
Activate the Virtual Environment
- Windows PowerShell
```sh
.venv\Scripts\Activate
```
Install Jupyter Inside the venv
- Still inside the venv, install Jupyter:
```sh
pip install jupyter ipykernel
```
Register the venv as a Jupyter Kernel
```sh
python -m ipykernel install --user --name=venv-name --display-name "Python (.venv)"
```
- name is an internal identifier (e.g., venv-name).
- display-name is what you’ll see in VS Code’s Jupyter kernel picker.

Select Kernel in VS Code
- Open your .ipynb notebook in VS Code.
- At the top-right, click on the kernel selector (it might show "Python 3" or something else).
- Select "Python (.venv)" (or the display name you gave above).