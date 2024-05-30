# AI4Life Workshop Prerequisites and Setup Guide

## 1. Google Account

### Requirements:
- Google account with access to Google Drive and Google Colab

### Instructions:
1. **Create a Google Account (if you don't have one):**
   - Go to [Google Account Creation](https://accounts.google.com/signup).
   - Follow the on-screen instructions to create your account.

2. **Access Google Drive:**
   - Go to [Google Drive](https://drive.google.com).
   - Ensure you can log in with your Google account and have access to create and manage files.

3. **Access Google Colab:**
   - Go to [Google Colab](https://colab.research.google.com).
   - Ensure you can log in and create new notebooks.

### Workshops Using Google Colab:
- **Introduction to DL Libraries** by Craig Russel and Daniel Franco-Barranco
- **bioImage.IO Cloud Service Demo** by Wei Ouyang and Estibaliz Gómez-de-Mariscal
- **Build your own BioImage Analysis Workflow with BiaPy** by Daniel Franco-Barranco

## 2. Fiji Installation

### Requirements:
- Fiji software installed with additional plugins such as SAMJ

### Instructions:
1. **Download and Install Fiji:**
   - Go to the [Fiji download page](https://imagej.net/Fiji/Downloads).
   - Download the appropriate version for your operating system.
   - Follow the installation instructions provided on the website.

2. **Install Additional Plugins:**
   - Open Fiji.
   - Go to `Help -> Update...` and update Fiji to the latest version if necessary. 
   - Before applying changes, go to "Manage Update Sties", look for "SAMJ", check it, and click "Apply Changes". Click again to "Apply Changes" in the main window.
   - Restart Fiji.
   - Ensure you have the necessary plugins installed through `Plugins -> SAMJ`

### Workshops Using Fiji:
- **Transformers (SAMJ)** by Carlos García López de Haro, Daniel Sage, and Caterina Fúster-Barceló

## 3. PyTorch Workshop for Basic Tooling in Deep Learning

### Requirements:
- Google Colab account or Python environment

### Instructions:
1. **Google Colab:**
   - Ensure you have access to [Google Colab](https://colab.research.google.com).

2. **Alternative Setup:** *(not mandatory if you have access to Google Colab)*
   - Install [Python](https://www.python.org/downloads/).
   - Download and install [Visual Studio Code (VSCode)](https://code.visualstudio.com/).
   - Install [Jupyter](https://jupyter.org/install).

3. **Configuration Instructions:**
   - Option 1: Use Google Colab.
   - Option 2: Clone and install the repository:
     ```bash
     git clone https://github.com/BioImage-Archive/pytorch_tutorial
     cd pytorch_tutorial
     pip install -r requirements.txt
     ```
4. **Testing Setup:**
   - Follow the instructions on [PyTorch Vision](https://pytorch.org/vision/stable/index.html) to verify your setup.

5. **Workshop Files:**
   - Available at [pytorch_tutorial repository](https://github.com/BioImage-Archive/pytorch_tutorial).

## Additional Information

Please ensure all installations and setups are completed before the workshop begins. If you encounter any issues or have any questions, feel free to reach out to the workshop coordinators for assistance.

We look forward to your active participation in the AI4Life Workshop!
