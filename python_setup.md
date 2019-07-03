---
layout: page
title: "Setup"
permalink: /setup/
root: ..
---

## Installing Python Using Anaconda

[Python][python] is a popular language for scientific computing, and great for
general-purpose programming as well. Installing all of its scientific packages
individually can be a bit difficult, however, so we recommend the all-in-one
installer [Anaconda][anaconda].

Regardless of how you choose to install it, please make sure you install Python
version 3.x (e.g., 3.4 is fine). Also, please set up your python environment at 
least a day in advance of the workshop.  If you encounter problems with the 
installation procedure, ask your workshop organizers via e-mail for assistance so
you are ready to go as soon as the workshop begins.

If you chose to use another environment other than Anaconda, make sure to install
the following libraries, which will be required for this workshop:
* [Pandas](http://pandas.pydata.org/)
* [Jupyter notebook](http://jupyter.org/)
* [Numpy](http://www.numpy.org/)
* [Matplotlib](http://matplotlib.org/)

### Windows - [Video tutorial][video-windows]

1. Open [https://www.anaconda.com/download][anaconda-windows]
   with your web browser.

2. Download the Python 3 installer for Windows.

3. Double-click the executable and install Python 3 using _MOST_ of the
   default settings. The only exception is to check the 
   **Make Anaconda the default Python** option.

### Mac OS X - [Video tutorial][video-mac]

1. Open [https://www.anaconda.com/download][anaconda-mac]
   with your web browser.

2. Download the Python 3 installer for OS X.

3. Install Python 3 using all of the defaults for installation.

### Linux

Note that the following installation steps require you to work from the shell. 
If you run into any difficulties, please request help before the workshop begins.

1.  Open [https://www.anaconda.com/download][anaconda-linux] with your web browser.

2.  Download the Python 3 installer for Linux.

3.  Install Python 3 using all of the defaults for installation.

    a.  Open a terminal window.

    b.  Navigate to the folder where you downloaded the installer

    c.  Type

    ~~~
    $ bash Anaconda3-
    ~~~
    {: .bash}

    and press tab.  The name of the file you just downloaded should appear.

    d.  Press enter.

    e.  Follow the text-only prompts.  When the license agreement appears (a colon
        will be present at the bottom of the screen) hold the down arrow until the 
        bottom of the text. Type `yes` and press enter to approve the license. Press 
        enter again to approve the default location for the files. Type `yes` and 
        press enter to prepend Anaconda to your `PATH` (this makes the Anaconda 
        distribution the default Python).

## Getting the Data

Data for this lesson is taken from the [Gapminder Foundation][gapminder-foundation]
and the [SAFI Teaching Database][safi-teaching-database].

1. Download these files to your computer by clicking [this link]({{page.root}}/files/python-data.zip), 
which will give you everything in a single compressed archive. 
2. Create a folder named `swc-python` on your Desktop and move the downloaded 
files into this newly created folder.
3. Unzip the file.

You should now see one folder named `python-data` in your `swc-python` folder on
your Desktop.

## Navigate to the `python-data` folder

If you're using a Unix shell application, such as Terminal app in macOS, Console or Terminal in
Linux, or [Git Bash](https://gitforwindows.org/) on Windows, execute the following command:

~~~
$ cd ~/Desktop/swc-python/python-data
~~~
{: .source}

On Windows, you can also use the native Command Prompt program.  The easiest way to start it up is by
pressing <kbd>Windows Logo Key</kbd>+<kbd>R</kbd>, entering `cmd`, and hitting <kbd>Enter</kbd>. In
the Command Prompt, use the following command to navigate to the `data` folder:
~~~
$ cd /D %userprofile%\Desktop\swc-python\data
~~~
{: .source}

## Launch a Jupyter notebook

Jupyter notebooks provide a browser-based interface for working with Python. After
downloading and decompressing the workshop materials and navigating to the
`python-data` folder, launch a Jupyter notebook by typing this command from the terminal:

~~~
jupyter notebook
~~~
{: .language-bash}

The notebook should open automatically in your browser. If it does not or you
wish to use a different browser, open this link: <http://localhost:8888>.

Finally, create a new notebook by clicking "New" button on the right and 
selecting "Python 3" from the drop-down menu.

[anaconda]: https://www.anaconda.com/
[anaconda-mac]: https://www.anaconda.com/download/#macos
[anaconda-linux]: https://www.anaconda.com/download/#linux
[anaconda-windows]: https://www.anaconda.com/download/#windows
[gapminder]: https://en.wikipedia.org/wiki/Gapminder_Foundation
[jupyter]: http://jupyter.org/
[python]: https://python.org
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA
[gapminder-foundation]: https://en.wikipedia.org/wiki/Gapminder_Foundation
[safi-teaching-database]: https://figshare.com/articles/SAFI_Survey_Results/6262019
