# Dataset_import_to_Colab_from_Google_Drive
This describes the procedure to import a dataset from Google Drive to google colab

step 1: Copy and paste this code and run
from google.colab import drive
drive.mount('/content/drive')

Step2:
When it prompts, connect with your google account
and authorize by clicking "yes" or "okay"

Output: It shows "Mounted at /content/drive" as the output

Step 3: 
Now paste the dataset into your google drive

Step 4: 
In the google colab, click the folder symbol in left side pane.
Now,  click on google drive symbol, then lick refresh symbol in the left side pane of google colab

Step 5:
Navigate to your datasest folder 
right click then copy path and ge the path
now paste the below code:

import pandas as pd
df = pd.read_csv('/content/drive/MyDrive/Datasets/dlmulti.csv')
df.head()

it will import 

