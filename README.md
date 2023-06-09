The style of UZH.

There are two ways of using it:

1. Using matplotlib
please upload the Font to your homefolder.
 Online via github - use the following command in your script:
   ```
   import matplotlib.pyplot as plt 
   plt.style.use('https://raw.githubusercontent.com/benckj/mpl_style/main/uzh.mplstyle')
   from matplotlib import font_manager
   font_dirs = ['/home/user/username/Fonts']
   font_files = font_manager.findSystemFonts(fontpaths=font_dirs)
   for font_file in font_files:
      font_manager.fontManager.addfont(font_file)
   ```
  
   Download the repository and install it on your computer by executing the installation.py file:
   
   After the installation you can use the style in the following way:
   ```
   import matplotlib.pyplot as plt 
   plt.style.use('uzh')
   ```
2. For using plotly uzh template, download the plotly_uzh_template.py to your working folder, and import the file to your python file or jupyter file as follows:
 ```
   import plotly_uzh_template
   ```
useful resource:https://plotly.com/python/templates/#creating-themes
