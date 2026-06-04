---
title: Set Up Instructions for Intro to Bash
---
<p>
  Estimated time: 30 mins,
  Updated July 2022
</p>

### Overview and Prerequisites

The Intro to Bash module guides you through the basics of file systems and the shell. If you have stored files on a computer, recognize the word “file”, and recognize either the word “directory” or “folder” (two common words for the same thing), then you are ready for this module.<br>
<br>
This page contains the set of instructions to be completed before beginning the module. By the end of these setup steps, you will have:


The sample data files saved to your desktop<br>
A Bash shell installed and accessible on your computer<br>
A text editor installed<br>
Verified that everything is working<br>
{: .checklist}

### 1. Download the Data Files

<strong>⚠ Warning:</strong> If your computer is logged into a cloud drive (OneDrive, Dropbox, etc.), log out before continuing. This ensures that Bash will be configured to access files on your local computer, not a cloud drive.
{: .callout}


You will be using sample data throughout this module. The sample data files are stored in this module's GitHub repository, github.com/apandas/bash-workshop.<br> 

<br> 
<strong>1a.</strong> Click this link, [download data files](https://downgit.github.io/#/home?url=https://github.com/apandas/bash-workshop/tree/gh-pages/data/shell-lesson-data){:target="_blank"}, to download the ZIP file shell-lesson-data.zip. The download will begin automatically. <br>  

<strong>1b.</strong> Unzip the downloaded file `shell-lesson-data.zip`. A folder named `shell-lesson-data` will appear in your Downloads folder. <br>

> ## How do I unzip a file? 
>
> [Unzip files on Windows](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-8d28fa72-f2f9-712f-67df-f80cf89fd4e5){:target="_blank"}: Microsoft Support<br>
> [Unzip files on macOS](https://support.apple.com/guide/mac-help/zip-and-unzip-files-and-folders-on-mac-mchlp2528/mac){:target="_blank"}: Apple Support<br>
> Unzip files on Linux: `shell-lesson-data` > <strong>Right-click</strong> > <strong>Extract</strong>
{: .solution}

<strong>1c.</strong> Move the folder `shell-lesson-data` onto your desktop. <br>

<strong>1d.</strong> Go to your desktop and open the folder `shell-lesson-data`. Verify that it contains two folders: `ex-data` and `ex-files`. If you see both folders, then you have successfully completed downloading the data files. <br>

### 2. Installing software: The Bash Shell

{% include install_instructions/shell.html %}
<br>
To close a Bash shell window, type in `exit`. Then press <strong>Enter</strong> or <strong>Return</strong> to run this command.
{: .callout}

### 3. Open a new Shell

In the module, you will learn how to use the Bash shell and it’s essential commands. Bash helps users automate repetitive tasks and easily combine smaller tasks into larger, more powerful workflows. Use of the shell is fundamental to a wide range of advanced computing tasks. This module will introduce you to this powerful tool.
<br>
<br>
<strong>3a.</strong> Open a new shell.<br>

> ## Windows
>
> You can open a new shell by running the program Git Bash from the Windows start menu.
{: .solution}

> ## macOS
>
> Since the Bash shell is set to your default shell, you can use your terminal app to open a new shell. Your terminal can be found at `/Applications/Utilities`, or by searching for “terminal” using <strong>Spotlight</strong> (<strong>⌘ Space</strong>).
{: .solution}

> ## Linux
>
> Your default shell should be set to Bash. 
>You can start a new shell by running the <strong>Gnome Terminal</strong> or <strong>KDE Konsole</strong> or <strong>xterm</strong>, which can be found via the applications menu or the search bar.
{: .solution}

<strong>3b.</strong>  In your terminal type `cd`, then press <strong>Enter</strong> or <strong>Return</strong> key.<br>
<br>
Doing this step ensures that you start with your home folder as your current folder (aka working directory), and is recommended whenever you start a new shell. In the module, you will learn more about file system navigation and how to access the data files in your home folder. Continue onto the [module](https://apandas.github.io/bash-workshop/01-intro/) or close the shell.

{% include links.md %}
