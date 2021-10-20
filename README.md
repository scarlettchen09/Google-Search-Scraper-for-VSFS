# Google-Search-Scraper-for-VSFS

# Downloading the program
To get this program, click on Code > Download ZIP at the Github page (where you are right now). If you have experience with Git, you can clone it with Git instead.

![Download location of program](https://i.imgur.com/lXbJ5pz.png)

# Setting up the required libraries you need:
## Easiest method: Download Anaconda

Anaconda comes with Python, Jupyter Notebook, as well as many other libraries including the ones that will be needed for this program. You will not have to install any other programs or use the command line, making it very straightforward!

1. Please go to this website and download the approipriate installer for your operating system (Windows, Mac, Linux): https://www.anaconda.com/products/individual

![Download location for Anaconda](https://i.imgur.com/nOYZJQI.png)

2. Run the installer with default settings. After, Anaconda will be installed onto your computer! 

3. For Windows, type Anaconda in the search bar and run Anaconda Navigator. A menu will open where you can select and start Jupyter Notebook. 

![Search bar](https://i.imgur.com/mGggzuf.png)

4. Use the file navigator in the Jupyter Notebook to navigate to the .iypnyb file. Select Run>Run all to run the program. 

![Jupyter Notebook](https://i.imgur.com/4Tv3hP6.png) ![Run all](https://i.imgur.com/HKSKnn7.png)
## Alternative method (pip):

If you already have experience programming, such as already having Python installed and familiarity with installing packages with the command line or `pip`, an alternative method is using `pip` and only installing the libraries needed for this program. 

1) Download the latest Python release on the official website:

https://www.python.org/downloads

Follow the instructions on the download.

**Make sure to check the Add Python to PATH option**

On Windows, you can then open up the command prompt and type in “python” to see if it has
been successfully installed. Python comes automatically installed with pip, which you will use to
install the needed libraries in the next step.

2) Upgrade pip and use pip to install the following libraries:
1. Requests (https://docs.python-requests.org/en/master/user/install/ )
2. BeautifulSoup (https://www.crummy.com/software/BeautifulSoup/bs4/doc/ )
3. Jupyter Notebook (https://jupyter.org/install )


On Windows, you can do this by opening the command prompt, and typing in
1. `python -m pip install --upgrade pip`
2. `python -m pip install requests`
3. `python -m pip install beautifulsoup4`
4. `python -m pip install notebook`
3) Run the Jupyter Notebook file: google_search_scraper.ipynb
On Windows, to run Jupyter Notebook, you can go in the command prompt and type in `jupyter notebook` which should open the notebook and allow you to select the file you want to open.


To open a specific file, you can also navigate to the directory the file is in and type `jupyter notebook google_search_scraper.ipynb` (if you are having trouble navigating to the directory in command prompt, you can also open up the folder the file is located in in File Explorer, and pressing shift + right click > Open Powershell Window here, and type the command in the Powershell Window)
4) Follow the instructions in the notebook.
