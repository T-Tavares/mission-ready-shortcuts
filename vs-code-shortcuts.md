# VS Code - Shortcuts

For the sake of simplicity, on the VS Code section the difference between MacOS and Windows shortcut will be determined by the colours.

$\textcolor{greenYellow}{\textsf{greenYellow for MacOS shortcuts}}$

$\textcolor{lightSkyBlue}{\textsf{lightSkyBlue for Windows shortcuts}}$

## Text Selection and Manipulation

Comment / Uncomment code by line

$\textcolor{greenYellow}{\textsf{CMD + /}}$ --- $\textcolor{lightSkyBlue}{\textsf{Ctrl + /}}$

Comment / Uncomment code by selection block

$\textcolor{greenYellow}{\textsf{Option + Shift + A}}$ --- $\textcolor{lightSkyBlue}{\textsf{Alt + Shift + A}}$

Adds next or previous line to selection

$\textcolor{greenYellow}{\textsf{Shift + Arrow Up (or) Arrow Down}}$ --- $\textcolor{lightSkyBlue}{\textsf{Shift + Arrow Up (or) Arrow Down}}$

Moves focused line up or down

$\textcolor{greenYellow}{\textsf{Option + Arrow Up (or) Arrow Down}}$ --- $\textcolor{lightSkyBlue}{\textsf{Alt + Arrow Up (or) Arrow Down}}$

Multiple cursors on each click

$\textcolor{greenYellow}{\textsf{Option + Left Click}}$ --- $\textcolor{lightSkyBlue}{\textsf{Alt + Left Click}}$

Multiple cursors on same column up or down

$\textcolor{greenYellow}{\textsf{CMD + Optn + ArrowUp (or) Arrow Down}}$ --- $\textcolor{lightSkyBlue}{\textsf{ Ctrl + Alt + ArrowUp (or) Arrow Down}}$

Duplicates line of code into the next line

$\textcolor{greenYellow}{\textsf{Shift + Option + Arrow Down}}$ --- $\textcolor{lightSkyBlue}{\textsf{Shift + Alt + Arrow Down}}$

Opens Emoji/Character Viewer

$\textcolor{greenYellow}{\textsf{Fn Key (by default)}}$ --- $\textcolor{lightSkyBlue}{\textsf{Windows Key + .}}$

Add to selection the next ocurrence of current selection.

$\textcolor{greenYellow}{\textsf{CMD + D}}$ --- $\textcolor{lightSkyBlue}{\textsf{Ctrl + D}}$

Add to selection all ocurrences of current selection.

$\textcolor{greenYellow}{\textsf{CMD + Shift + L}}$ --- $\textcolor{lightSkyBlue}{\textsf{Ctrl + Shift + L}}$

## UI Utilities

Opens Command Pallet in VS Code

$\textcolor{greenYellow}{\textsf{CMD + Shift + P}}$ --- $\textcolor{lightSkyBlue}{\textsf{Ctrl + Shift + P}}$

# Command Line / Terminal

Within VS Code you'll often use the Command Line / Terminal. So I thought it'd be a good idea to drop some of it's shortcuts here. Before we talk about the shortcuts and commands here I will show a basic folder structure that we'll consider for the examples.

For those shortcuts the green tags are for MacOS, the blue tags for Windows and the yellow tags are for both Windows and Mac,

```
.
├── assets
│   ├── icons
│   ├── images
│   └── music
├── public
└── src
    ├── config
    └── helpers
```

Show contents (folders and files) of the folder you are currently at

$\textcolor{greenYellow}{\textsf{ls}}$ --- $\textcolor{lightSkyBlue}{\textsf{dir}}$

Navigates to the folder specified

$\textcolor{yellow}{\textsf{cd folderName}}$

```
cd src

// Will navigate to the src folder
```

If you know your folders you can navigate directly to a few levels down. By adding "/" in between the folder names on your command.

$\textcolor{yellow}{\textsf{cd folderName/subFolderName/}}$

```
cd assets/images

// Will navigate straight to the images folder
```

Navigates to one level up to the folder you are currently in

$\textcolor{yellow}{\textsf{cd ..}}$

The same way you can navigate on the other direction for several levels. By adding .. and / to keep going other levels up.

$\textcolor{yellow}{\textsf{cd ../../}}$

Consider you are currently on the images folder and you want to go back to the main folder ( go two levels up).

```
cd ../..

// Will bring you up to the main folder.
```

When navigating or accessing files you can also use Tab to autocomplete or show a list of possibilities. That way you don't necessarily need to memorize the whole path.

```
cd assets/im

// If you hit Tab at this point, the command line is smart enought to understand where you are going and will autocomplete your code to

cd assets/images

// If you have mutiple folders that start with "im", you'll see a list of possibilities where you can reference to.
```

Creates a new file on the folder you are currently at. (ext is the extension of your file.)

$\textcolor{greenYellow}{\textsf{touch fileName.ext}}$ --- $\textcolor{lightSkyBlue}{\textsf{copy NUL fileName.ext}}$

Creates a new folder on the folder you are currently at

$\textcolor{yellow}{\textsf{mkdir folderName}}$

Deletes targeted files

$\textcolor{greenYellow}{\textsf{rm fileName}}$ --- $\textcolor{lightSkyBlue}{\textsf{del fileName}}$

Deletes targeted folders. On MacOS is the same command for file deletion but you need to add the -r flag.

$\textcolor{greenYellow}{\textsf{rm -r folderName}}$ --- $\textcolor{lightSkyBlue}{\textsf{rmdir folderName}}$

<!--
$\textcolor{greenYellow}{\textsf{}}$
 -
