# Unit 01 Command Line

1. On your Desktop, search for Terminal (Mac) or Command Line (Windows), and open the application. You should see your username & your laptop:
```
lisanguyen@lisan-macbook-pro-us ~ %
```
The tilda sign, ```~```, means you are in the ```root``` directory of your OS. The root directory is the first or top-most directory in a hierarchy.

2. Type in the following command to **list** available folders and files in your ```root``` directory:

```commandline
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

3. Let's navigate to the Desktop by **changing directories**.
```
cd Desktop
```

4. You can confirm that you're on your Desktop by listing the contents:
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

5. Let's make a new folder for this class:
```
mkdir intro-to-python
```
6. Let's confirm the folder was created by listing the Desktop contents again.
```
ls
```
7. Confirm that you see the folder you just created and let's **change directory** to ```intro-to-python``` by running the command:
```
cd intro-to-python
```
9. Next, let's create a new file:
```
touch unit-0.py
```
The command ```touch``` will look for an existing file before creating a new one.

8. Let's double check that the file was created!
```
ls
```

Congrats! You've nagivated through your directory and created a new file.

## Further Reading
- [Command Line for Beginners](https://www.freecodecamp.org/news/command-line-for-beginners/) by FreeCodeCamp
- Test your knowledge with [Command Line Challenge](https://cmdchallenge.com/)
- [command line cheatsheet](../resources/terminal_cheatsheet.md)

[Back to Syllabus](/README.md)
