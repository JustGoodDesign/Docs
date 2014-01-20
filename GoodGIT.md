Good GIT
===

[Good GIT](http://www.justgooddesign.com/products/unity3d/good-git/) is a product of [Good Products](README.md) available in the [Unity Asset Store](https://www.assetstore.unity3d.com/#/content/7242).


#Authors#

[Jesse Graupmann](https://plus.google.com/113634720692058569075) | [Just Good Design](http://www.justgooddesign.com/)

<a target=_blank href="https://github.com/tgraupmann/TAGENIGMA-Docs">[Tim Graupmann]</a>


#Audience#

Package contents are targeted towards artists and programmers that want cross-platform-native GIT support.


#Compatibility#

This project is targeted for Unity 3.5.7 or better.


#Contents#

This package contains full source for the Good GIT package.


#Menu Items#

```
Window->Just Good Design->Open Good GIT - The Good GIT Panel can be accessed via the menu.

Window->Just Good Design->Links->Good GIT - Opens the Good GIT Product Page

Window->Just Good Design->Links->Tools->CrossOver - CrossOver allows you to run Windows Apps on MacOS

Window->Just Good Design->Links->Tools->Putty - Putty has pageant to store your GIT SSH keys

Window->Just Good Design->Links->Tools->TortoiseGIT - Opens the <a target=_blank href="https://code.google.com/p/tortoisegit/">[TortoiseGIT]</a> version control product page

Window->Just Good Design->Links->Tools->Winmerge - Is great and free version comparison tool
```


#Mac Platform#

Good GIT has a hook available using <a target=_blank href="https://code.google.com/p/tortoisegit/">[TortoiseGIT]</a> on Mac which requires CrossOver office.

Launch the CrosssOver application, and select "Manage Bottles".

Create a new 'WinXP' bottle named 'TortoiseGIT' by clicking the plus button.

This same bottle will hold several installs, which is not the default option when

installing new software with crossover.

Close the "Manage Bottles" dialog and in the Configure menu select "Install Software".

Near the top of the installer, if given the choice, choose "Always Update".

Enter "Putty" into the Selectan application to install.

Expand "Commuity Supported Applications" where you'll find "Putty".

In the "Will install into a new winxp bottle 'Putty', change that to the existing 'TortoiseGIT'.

Install "TortoiseGIT" and "WinMerge" in the same way to that same 'TortoiseGIT' bottle.

After installing 'TortoiseGIT', upgrade the GIT client with '<a target=_blank href="https://code.google.com/p/msysgit/">[msysgit]</a>'.

You can access the preferences in the standard preferences with the Unity->Preferences menu item.


#Windows#

On Windows, you need to install the <a target=_blank href="https://code.google.com/p/tortoisegit/">[TortoiseGIT]</a> installer with the command-line tools.

After installing 'TortoiseGIT', upgrade the GIT client with '<a target=_blank href="https://code.google.com/p/msysgit/">[msysgit]</a>'.

You can access the preferences in the standard preferences with the Edit->Preferences menu item.


#Preferences#

You'll find 'G|GIT' in the standard preferences.

If the GIT Type is set to TortoiseGIT, additional options appear.

On Windows, you can set the path to TortoiseGitProc.exe which is a command-line tool within the

TortoiseGIT. It requires that the command-line tools for TortoiseGIT were installed.

On Mac, you need to enter the Bottle Name which TortoiseGIT is installed. The preferences

default to "TortoiseGIT".


#Good GIT Panel#

Good GIT has areas divided out into "Assets", "Project Settings", "Files, and "Commands".

"Assets" has common functions:

```
> Pull - Runs GIT Pull in the Assets folder

> Commit - Runs GIT Commit in the Assets folder

> Add - Runs GIT Add in the Assets folder

> Push - Runs GIT Push in the Assets folder
```

"Project Settings" has common functions:

```
> Pull - Runs GIT Pull in the ProjectSettings folder

> Commit - Runs GIT Commit in the ProjectSettings folder

> Add - Runs GIT Add in the ProjectSettings folder

> Push - Runs GIT Push in the ProjectSettings folder
```

"File" does operations to folders and files selected in the project view:

```
> Pull - Runs GIT Pull on the selected file(s)

> Commit - Runs GIT Commit on the selected file(s)

> Add - Runs GIT Add on the selected file(s)

> Remove - Runs GIT Remove on the selected file(s)

> Push - Runs GIT Push on the selected file(s)

> Diff - Runs GIT diff on the selected file(s)

> Rename - Renames on the selected file(s) including a meta file popup

> Edit Conflicts - Opens edit conflicts on the selected file(s)
```

"Commands" common functions:

```
> Revert - Runs GIT revert on the selected file(s)

> Status - Runs GIT status on the selected file(s)

> Log - Runs GIT log on the selected file(s)

> Browser - Opens the repro browser on the selected file(s)

> CleanUp - Runs an GIT cleanup at the root level

> Clone - Runs an GIT clone at the specified path
```


#Support#

You can send comments/questions to unity@justgooddesign.com and please post in the forums to share

how you like this product or to make feature requests.

http://forum.unity3d.com/threads/169759-Good-SVN-Native-SVN-Support-in-Unity-on-Mac-Windows


#Change Log#

1.0 Initial launch of product
