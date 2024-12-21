---
layout: page
title: Installation
---

Please complete the following steps before participating in the training. 

0. If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
1. Navigate to Google Drive (https://drive.google.com/).
2. In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", 
search for 'Colaboratory', and install it. Then click New > More > Colaboratory.
3. Copy the following code snipped into the first cell of the notebook. Run it (```shift + enter``` or click &#9658; button) to mount your Google Drive to the Colab environment.
A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab (you will have to do this
every time you open a new notebook).
```
from google.colab import drive
drive.mount("/content/drive")
```
4. Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive :
```
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/LLM4BeSci_GSERM2024.git
```
5. Go back to your Google Drive and navigate to the folder "LLM4SocBeSci". You should see the directories `day_1`, `day_2`,`day_3`, `day_4`, and `day_5` containing the relevant notebooks (.ipynb files) and data (it may take  a couple of minutes for the files to appear) for the exercises of each day.
6. Open the folder `day_1` and then the `day_1.ipynb` notebook. A new Colab window will open.
7. Run the first cell of the notebook to install the required packages. This may take a few minutes and ask for you to give permission to access your Google Drive. 

You are now ready to start the exercises!