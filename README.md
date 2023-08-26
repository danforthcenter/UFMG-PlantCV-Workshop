# UFMG PlantCV Workshop
Here you will find resources to participate in our interactive workshop focused on using PlantCV to develop pythonic workflows to analyze your plant phenomic data. In this workshop, you will engage in instructor- and self-guided Jupyter notebook activities to obtain training in the following directories:

1. Single-Plant-Image-Analysis: Learn the fundamentals of image analysis and how to develop a workflow of a single plant image of *Arabidopsis thaliana* using PlantCV. You will learn the elements that make up an image and how PlantCV using image data to extract plant features and data.
2. Multiple-Plant-Image-Analysis: In this module, you will develop a workflow on a tray of *Arabidopsis thaliana*. Discover how to segment and identify individual plants amongst the tray and extract relevant trait data for each plant.
3. Seed-Image-Analysis: Here you will see how PlantCV detects, counts, and extract seed characteristics on an image of *Chenopodium quinoa* seeds.
4. Dry-Beans-Machine-Learning-Lab: In this exercise, participants will work in groups of 2-3 to capture quality images of various dried legumes and import them into a PlantCV workflow. You will develop training sets for several different dried beans to train a machine learning model capable of identifying specific legumes in a heterogenous mixture.

By accessing this repository, you will have access to the necessary image datasets and Jupyter notebooks for each activity. These resources will empower you to learn and apply the image analysis techniques using PlantCV. This workshop utilizes Google Colaboratory to function, this means that you will need a **Google account** and have [Google Colaboratory](https://workspace.google.com/u/1/marketplace/app/colaboratory/1014160490159?pann=ogb) installed and added to your Google Workspace. 
***
## Cloning this repository to your Google Drive
1. Install and add [Google Colaboratory](https://workspace.google.com/u/1/marketplace/app/colaboratory/1014160490159?pann=ogb) to your Google Workspace.
2. Open [Google Drive](drive.google.com) in your web browser.
3. Open a new Google Colaboratory notebook (.ipynb):
   * +New (Found above menu on the left side of the screen).
   * In the menu, select **More**.
   * Select *Google Colaboratory* in the second menu.
   * NOTE: If you do not see *Google Colaboratory* in the second menu, you may need to refresh the web page.
5. Add the following code in the first cell:
```
# Mount your Google Drive to Google Colaboratory
from google.colab import drive
drive.mount('/content/gdrive')
# Change your working directory to the mounted drive
%cd gdrive/MyDrive/
# Print the contents of your drive to confirm it worked
!ls
# Clone the workshop's repository to your Google Drive
!git clone https://github.com/danforthcenter/UFMG-PlantCV-Workshop.git
```
5. Run the cell either by hitting the **Play** button or by pressing *Shift + Enter*
6. You may get a dialog box warning you that the notebook isn't authored by Google, select **Run Anyway**.
7. You will be prompted by another dialog box asking for permission to access your Google Drive within the notebook, select **Connect to Google Drive**.
8. You should see the contents of your Google Drive printed below.
9. Check your Google Drive to see if you have a new directory named UFMG-PlantCV-Workshop and that all of the contents from this repo should be within.
