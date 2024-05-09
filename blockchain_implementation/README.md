# ibm-project-submission-2020-batch-2171001
# This is a guide for setting up a new project environment using Anaconda.
## 1. Install Anaconda
Follow the link to download and install Anaconda: (**https://www.anaconda.com/products/individual** "*Anaconda Individual Edition*")
___
## 2. Open Anaconda Navigator
Launch the Anaconda Navigator application.
___
## 3. Create New Environment
Click on "**Environments**" in the left-hand menu.

Click the "**Create**" button in the bottom left corner.

Enter the project name in the "**Name**" field and click on **Create**.

Click on the **drop-down** list at the top and select "**Not installed**" option.

And, on the right-hand side *Search Bar* search for "**jupyter**". Check the "**jupyter**" metapackage and click on "**Apply**".

Now, select the created Environment and let it load the packages. Once loaded, click on the *Play* button and select **Open Terminal**.
___
## 4. Install Required Packages
Open the command prompt or terminal in the new environment.
Run the following commands one by one to install the necessary packages:
```
pip install tensorflow
conda install -c conda-forge keras
conda install -c anaconda scikit-learn
conda install -c conda-forge opencv
conda install -c anaconda scikit-image
conda install -c anaconda flask
pip install pandas
pip install werkzeug==2.3.7
```
___
## 5. Run the Project
After the installation of all the packages, change the directory to where the project files are located.

That's it! You're now ready to start your project in this environment.

```python main.py```
