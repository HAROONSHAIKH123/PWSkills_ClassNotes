# Git ID
```
git config --global user.email "hrrnshaikh@gmail.com"
git config --global user.name "HAROONSHAIKH123"
git push origin main

```
# or create a new repository on the command line:
```
echo "# asdf" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/HAROONSHAIKH123/PWSkills_ClassNotes.git
git push -u origin main
```

# or push an existing repository from the command line:
```
git remote add origin https://github.com/HAROONSHAIKH123/asdf.git
git branch -M main
git push -u origin main
```

# Data file:
```
wine quality data red
'https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv'

algerian forest
'https://archive.ics.uci.edu/ml/machine-learning-databases/00547/Algerian_forest_fires_dataset_UPDATE.csv'

play store 
'https://raw.githubusercontent.com/jasonchang0/kaggle-google-apps/master/google-play-store-apps/googleplaystore.csv'

employee data
'https://gist.githubusercontent.com/kevin336/acbb2271e66c10a5b73aacf82ca82784/raw/e38afe62e088394d61ed30884dd50a6826eee0a8/employees.csv'

titanic
"https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
```

# Basic library:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

df = sns.load_dataset('titanic')
df.head(2)
```

# To remove hidden file:
```
ls -a
rm -rf ".fileName"
```
