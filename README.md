# YouTube Recommendation Analysis

What rabbit hole YouTube can bring you down to? A quick project to log YouTube recommendations, starting from one "seed". 

## How to run 

After cloning the directory, run 

```
conda env create -f environment.yml
conda activate youtubeAudit
```

Then, install chrome webdriver. Download the zip corresponding to your OS from [here](https://chromedriver.storage.googleapis.com/index.html?path=88.0.4324.96/). If you're on windows, copy the unzipped .exe file to C:\Windows or anywhere that is included in PATH. For MacOS, follow [this guide](https://www.kenst.com/2015/03/installing-chromedriver-on-mac-osx/). 

Now you can run `jupyter lab` and open `get_youtube_recs.ipynb`. Run all the code in "Setup Code", paste the seed video link in the cell below "Start Here", and run rest of the code before "Clean up data".