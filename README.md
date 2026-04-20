# Git Template
To use this template adjust the following:<br>
In file setup.cfg adjust the variables:
- name,
- version,
- author,
- author_email,
- description,
- url

In directory scr crerate subdirectory with the package name, e.g. *src/helloworld*<br>
Put all package source code in directory. If required, create subdirectories under the package directory.<br>
In the package directory create file \_\_init\_\_.py. In this file set the version number: \_\_version\_\_= "0.0.1"<br>
The file \_\_init\_\_.py is needed to make it a Python package.

`Note:` You might want to delete the toml file as otherwise the archrive file may not install when building a SAS Runtime Container. <br>
Delete toml file when you get message: *'ModuleNotFoundError' No module named 'tomli'*
