## 1. Get an account, and try browser exercises on GitHub: 

#### Setup 
* consider installing the desktop client https://desktop.github.com/
* make an account on github.com (the desktop client will prompt you on launch, or you can go directly). 
    * Browse the Guides at https://guides.github.com/
        - Perhaps make yourself a simple web page at GitHub Pages
    * This is fun like a game: https://learngitbranching.js.org/ 
        - Remember, git is a **minimum** set of rules needed for peers to collaborate on a thing. It's a fundamental aspect of existence! Well worth your attention. 
    * if you like, dig into deeper “training" https://services.github.com/on-demand/

#### test forking and pull requests (our first collaboration!) 

* From the master copy at https://github.com/MPO624/2018, Fork, edit PARTICIPANTLIST.md, and make a PR. 

-------------------------
## 2. Now, get stuff onto your own machine, like the overall course folder 
#### your "fork" of the _master_ class repo

Let's get your fork of the course (github.com/myname/2018) onto your own computer — but in a way that you can easily sync with your github version (which functions as a backup). To do that, I use the Github desktop app (client). (there is command-line way, but the client helps you see some relationships, at least at first). 

To do this, open the GitHub desktop app (client), and find where it says “Clone an existing project from GitHub to your computer”. You will have to select a directory name on your own computer. Again, above about naming it. 

This folder will be special: it will have some hidden files in there (starting with .git) to keep track of all those versions and branches and forks and stuff (yes, the words are a bit of a blur at first), so you can keep verison control for yourself, and keep it synced with your fork of the course that you and everyone can see on GitHub.com. 

  * So I will use (home)/Jupyter/GitHubForks/MPO624-2018. 

----------------------
## 3. Let's install and launch jupyter-python, from unidata-python-workshop

* Basically, follow the istructions at https://unidata.github.io/unidata-python-workshop/installation.html

   * install miniconda3 (the basic system, easily expanded) or anaconda (the big package with more than we need) from anaconda.com. The 3 refers to Python3. Python2 is deprecated soon.

   * Clone or Download (big green button) https://github.com/Unidata/unidata-python-workshop. Or, the installation page has several other ways to get it. You only need one. Put it in a meaningfully named directory — the thoughfulness with which you organize YOUR computer’s file hierarchy now will pay off in the long future. 

      * One naming suggestion would be (home)/MPO624/unidata-python-workshop. But maybe “624” won’t mean much to you next year or next decade, perhaps you prefer (home)/MPO_data_class/… Or maybe you think you will work with Jupyter for a long time, beyond just this course, and we will download notebooks from lots of places, some static (not forked). It’s good to have all your Jupyter notebooks in one file tree, as you will see.  So I put Jupyter/ as a top level directory. So I am using (myname)/Jupyter/unidata-python-workshop

   * Do this before class: it is fairly slow step that downloads a lot of packages. You will need to open a "Terminal" in Mac or "Command Prompt" in Windows and type these things there. 
   
      * cd (your_directory)/unidata-python-workshop
      * conda env create -f environment.yml
      
   * If all goes well, you can now activate the environment (where all those packages are installed), and launch! 
      * Windows: **activate unidata-workshop**
      * Mac (bash shell): **source activate unidata-workshop**
      * **jupyter notebook**
      
      A browser window should now pop up with Jupyter running in it! 

