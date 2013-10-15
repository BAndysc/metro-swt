metro-swt
=========

Little library with cool, modern looking UI for SWT (Java).

![Simple window](http://i.imgur.com/0wiqvbA.png)


Usage
-----

Assumming you have imported `MetroSWT-x.x.x.jar` library to your project (binary already build in bin/ folder):

1. Instead of creating new instance of Shell class, **create new `MetroShell` object**.
2. Viola!


**Important notes**
* **Do NOT put widgets directly into the shell, instead put widgets to `shell.getContent()` composite**
* MetroShell is able to hold menubar, but keep in mind you have to call `setMenu(Menu menu)` method **after** you had created all menu items
