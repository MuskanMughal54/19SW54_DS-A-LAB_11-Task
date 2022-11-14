------

title = "Python Dark mode"
date = 2022-1-11
draft = false
keywords = ["Python Dark Theme", "Background Foreground Color"]
description = "This article demonstrates about dark mode in Python."
postlink = 280435
inarticle = true
tags = ["Python Dark Theme", "Background Foreground Color"]
author = "Abid Ullah"
reviewer = "Jinku Hu"

------

The purpose of this article is to explain how you can apply dark mode in Python. The method of making  dark mode in python will be described here as well as its usage with a proper example. 

## Dark Mode in Python

Object-oriented, high-level, interactive, interpreted, and general-purpose Python is a programming language. Since 1991, it has been in development. With Python, programmers can write programs and instructions using fewer lines of code, attracting millions of developers.

It will transform your Python IDLE 2.7 into a Dark Theme, reducing eye strain in low light conditions if you are a Python developer and especially if you are a night-owl programmer. For those who wish to experience the Monokai theme of Sublime Text, Python IDLE 2.7 can be customized to add the Dark theme.

This article intends to teach you how to use custom color schemes with IDLE, Python's built-in IDE. By adjusting how IDLE highlights your code, you can make your editor more intuitive and boost your performance. For me, writing code is much more challenging when the color theme in my editor is uncomfortable or straining. Having too much contrast between the background and the foreground makes it difficult to read your own code. It can be confusing or unintuitive to use a theme that does not work for you, as you may be expecting certain pieces of code to be highlighted in a certain color, but your IDE is using a completely different one. It may be that your code comments are displayed in a bright red color when you would prefer them to be more subdued.

## **Python IDLE**

Python IDLE, or Integrated Development and Learning Environment(IDLE), is a standard IDE included with the Python installation package for the Python programming language.

By searching for 'IDLE' in the Start menu in Windows Operating System, you can open Python IDLE.

![Idle](D:\Python_Articles\Dark_modePython\Darkmode_pics\Idle.PNG)

For Linux and macOS, Python IDLE is not included by default in Python distributions.

The Python IDLE can be installed on Ubuntu Linux by using the following command:

```python
$ sudo apt-get install idle
```

A single line python statement can be executed using Python IDLE. Python IDLE is used by developers primarily for developing, modifying, executing, and debugging Python scripts. A Python IDLE text editor contains all the features you need to write Python scripts efficiently and effectively. Aside from syntax highlighting, autocompletion, and smart indent, it also includes some awesome features. A key feature of IDLE is its debugger, which provides stepping and breakpoints.

The official website of Python has a download link which comes with Python IDLE automatically.

**Reasons to add dark theme to your Python IDLE?**

Nowadays, dark themes are becoming increasingly popular among night-owl programmers. There are some people who just like the vibe of dark themes, while others use them to reduce eye strain and save battery life. In the eye doctor's profession, programmers are the main source of income

**Pros:**

Low-light conditions, especially at night, can reduce eye strain with dark themes. The contrast between foreground and background reduces eye strain. Python IDLE syntax highlighting can be easier to read with dark themes like monokai. Enjoy coding while protecting your most precious organ - your eye.

**Python IDLE Dark Theme Code [Monokai Theme Included]:**

Python IDLE already includes the following code, which you'll need in the next section, which explains how to make your Python IDLE have a dark theme.

As part of the Monokai Theme code, syntax highlighting and various text editor components' colors are changed by default.

```python
[monokai]

normal-foreground= #F8F8F2
normal-background= #272822
keyword-foreground= #F92672
keyword-background= #272822
builtin-foreground= #66D9EF
builtin-background= #272822
comment-foreground= #75715E
comment-background= #272822
string-foreground= #E6DB74
string-background= #272822
definition-foreground= #A6E22E
definition-background= #272822
hilite-foreground= #F8F8F2
hilite-background= gray
break-foreground= black
break-background= #ffff55
hit-foreground= #F8F8F2
hit-background= #171812
error-foreground= #ff3338
error-background= #272822
cursor-foreground= #F8F8F2
stdout-foreground= #DDDDDD
stdout-background= #272822
stderr-foreground= #ff3338
stderr-background= #272822
console-foreground= #75715E
console-background= #272822
```

#### Activating theme

1. Place config-highlight.cfg in your idle config directory, which is commonly located at: C:/Users/.idlerc, C:/Users/%user%/.idlerc, Python/Lib/idlelib, /home/.idlerc, $HOME/.idlerc.

2. Select Highlighting under Options > Configure > IDLE

3. The "Dracula" theme can be selected under "Custom Themes."
   It is not advisable to write multiple lines of code that contain functions/classes in the IDLE shell. If this is the case, you can select New File from the File menu in IDLE.

   There are a number of options available in IDLE's Format, Edit, and Options menus.

   ![Python_IDLE Shell](D:\Python_Articles\Dark_modePython\Darkmode_pics\Python_IDLE Shell.PNG)

   This allows you to select any font face, font size, make the font bold, and even calibrate the indentation width.

   The menu icon is located in the top right corner of the IDE window and allows users to swiftly choose between bright and dark color themes in the Python IDE. Wing switches to the light or dark themes set up on the first User Interface options page when Dark Theme or Light Theme is selected.

   Wing also provides the ability to mimic the OS display style on Windows and macOS. At the moment, Windows always has a light theme. Wing will follow the system-defined display style on macOS. It should be noted that you can choose the editor's theme independently of the main display theme in both scenarios.

   The IDLE program provides you with this feature so that each user can work with the font size that is most comfortable for him/her. You may need an IDE that allows you to increase the font size when your monitor is too small. You can relieve your eyes with IDLE and give them a sense of relief.

   You can also change the indentation, which follows PEP-8 coding guidelines, which is set to 4 spaces by default.

   ![Configure](D:\Python_Articles\Dark_modePython\Darkmode_pics\Configure.PNG)

   Keys: This feature allows you to map different key presses to actions, also known as keyboard shortcuts. You need these components to increase your overall productivity when using an IDE. It's up to you whether you want to come up with your own keyboard shortcuts or use the defaults.

   The keys are displayed in an Action - Key format, which displays the action that is performed when a specific key or keys are pressed. Idle keys feature is rarely used by developers, but it makes life easier for those who need to write a lot of code quickly.

   Using the horizontal tab at the top, select "Highlights"

   ![Highlights](D:\Python_Articles\Dark_modePython\Darkmode_pics\Highlights.PNG)

   You can choose between "IDLE Classic/IDLE Dark/IDLE New" on the right hand side under "Highlight Theme".

   ![bg](D:\Python_Articles\Dark_modePython\Darkmode_pics\bg.PNG)

   Then click OK after clicking Apply

   Done!

   Now you may restart your system, Open Python IDLE, From the menu bar select Options -> Configure IDLE -> Highlighting & You will be able to see the monokai theme under the Highlighting themes section. Select Monokai dark theme and Enjoy

   ![Dark_Theme_OP](D:\Python_Articles\Dark_modePython\Darkmode_pics\Dark_Theme_OP.PNG)

   ##### **Conclusion:**

   This article's final section covered how to install a dark theme in Python IDLE so you can run scripts like a pro without straining your eyes.

   The following subjects are covered: What is Python IDLE?, How can I set up Python IDLE on my system? Why is it necessary to give your Python IDLE a black theme? and the way to make your Python IDLE have a dark theme.

   In this Python article, we hope to have demonstrated how to add dark theme in python with step by step guidelines.

   ​