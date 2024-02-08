# Unit 01 Command Line

1. On your Desktop, search for Terminal (Mac) or Command Line (Windows), and open the application. You should see your username & your laptop:
```
# mac
lisanguyen@lisan-macbook-pro-us ~ %

# windows
C:\Users\lisanguyen06>
```
The tilda sign, ```~```, means you are in the ```root``` directory of your OS. The root directory is the first or top-most directory in a hierarchy.

## Which directory am I in?

To see your current directory, type the following command into your terminal and hit enter:

```bash
# mac/linux
pwd

# Windows
cd
```
This will print the path of the directory (or folder) that you're in.

```/Users/lisanguyen```

## What's in this folder?

Type in the following command to **list** available folders and files in your current directory:

```bash
# mac/linux/windows
ls
```
You should see similar folders. Thought it might not be exact:
```commandline
Applications	Documents	Library		Music		Public
Desktop		Downloads	Movies		Pictures	Sites
```
To visualize this in a different way, here is my directory tree:
```
root
-- Applications
-- Desktop
-- Documents
-- Downloads
-- Library
-- Movies
-- Music
-- Pictures
-- Public
-- Sites
```

## Changing Directories

To navigate down our file tree, we're going to use the ```cd``` command:
```
cd Desktop
```

You can confirm that you're on your Desktop by listing the contents:
```
ls
```
The items should look very familiar:

```commandline
Screenshot 2024-01-11 at 9.38.47 AM.png
Screenshot 2024-01-11 at 9.39.22 AM.png
Screenshot 2024-01-19 at 8.52.07 AM.png
Screenshot 2024-01-29 at 2.23.43 PM.png
Screenshot 2024-01-30 at 2.31.30 PM.png
```

## Making a New Folder
```
mkdir intro-to-python
```

Let's confirm the folder was created by listing the Desktop contents again.
```
ls
```

Once you confirm that you see the newly created folder,  let's **change directory** to ```intro-to-python``` by running the command:
```
cd intro-to-python
```

## Creating a new file

```
touch unit-0.py
```
The command ```touch``` will look for an existing file before creating a new one.

Let's double check that the file was created by listing the contents of the folder:
```
ls
```

Congrats! You've navigated through your directory and created a new file.

If you want to go back up a folder, you can use the command ```cd ..``` and you will go back to Desktop. Here's a visual:

```
├── root
│   ├── Desktop
│   │   ├── intro-to-python
```

Lastly, at any time, you can quickly navigate to your Desktop by using the command:

```commandline
cd ~/Desktop
```

## Further Reading
- [Command Line for Beginners](https://www.freecodecamp.org/news/command-line-for-beginners/) by FreeCodeCamp
- Test your knowledge with [Command Line Challenge](https://cmdchallenge.com/)
- [command line cheatsheet](../resources/terminal_cheatsheet.md)

[Back to Syllabus](/README.md)
