---
layout: page
title: Installation
---

#### Google Colab and GitHub Repository

`1.` If you do not have a Google account, you will need to create one (this can be deleted after the workshop).<br>
`2.` Navigate to Google Drive (<https://drive.google.com/>).<br>
`3.` In the top-left, click New \> More \> Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", search for 'Colaboratory', and install it. Then click New \> More \> Colaboratory.<br>
`4.` Copy the following code snipped into the first cell of the notebook. Run it (`shift + enter` or click ► button) to mount your Google Drive to the Colab environment. A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab (you will have to do this every time you open a new notebook).<br>

```         
from google.colab import drive
drive.mount("/content/drive")
```

`5.` Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive:

```         
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/LLM4BeSciUnibas.git
```

`6.` Go back to your Google Drive and navigate to the folder "LLM4BeSciUnibas". You should see the relevant notebooks (.ipynb files) and data (it may take a couple of minutes for the files to appear).

You have now successfully set up your Google Colab environment and cloned the GitHub repository!

#### Hugging Face and Meta Llama License

`7.` Make sure you have a hugging Face account (<https://huggingface.co/join>).<br>
`8.` Go to the [`meta-llama/Llama-3.2-3B-Instruct` model page](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct) and fill in the 'COMMUNITY LICENSE AGREEMENT' form at the top of the page to get access to the model (this may take a couple of days).<br>
`9.` Once you have been granted access to the model, you can navigate to [your Hugging Face profile settings](https://huggingface.co/settings/tokens) to generate an API token (+Create new token). Set the token type to 'Read' and give it a name.<br>

You are now ready to work through all the exercises in the course!
