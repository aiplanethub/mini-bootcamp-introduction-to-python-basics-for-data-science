# Packages in Python

* In simple terms, Python packages are collections of multiple Python files.
* And these Python files are known as modules in Python.
* If we keep all of our code in the same file, it will result in:
  * Huge code base, which ends up being messy
  * Lots of code you won't use
  * Maintenance problem
* If we take an example of ourselves, we don't usually store all our files on our computer in the same location. We use a well-organized hierarchy of directories/folders for easier access.
* Similar files are kept in the same directory. For example, we may keep all the songs in the "music" directory. Analogous to this, Python has packages for directories and modules for files.
* As our program grows larger with many modules, we place similar modules in one package and different modules in different packages. This makes a project (program) easy to manage and conceptually clear.
* Similarly, as a directory can contain subdirectories and files, a Python package can have sub-packages and modules.
* This leads to the following hierarchy:
* Package Level: Directory/Folder of Python Scripts.
  * Module Level: Within a package, each script is a module that performs a specific function.
      * Script Level: We can specify functions, methods, and variables in a script.
* Thousands of packages are available in Python.
* For data science, the commonly used packages are:
  * Numpy: Working with arrays
  * Matplotlib: Data Visualisation
  * Scikit-learn: ML

## Importing packages/modules

* A Python package can have sub-packages in it. Further, these sub-packages have some modules (i.e., Python files).
* Each module consists of some Python functions.
* We need to load the module in our working environment to use these functions.
* To load any package or module, we use the term import followed by module name or the package name.
* In the video, the tutor has loaded the 'math' module of Python and used functions like sqrt (to calculate the square root of a number), pow (to calculate the power of a number), etc.










<iframe width="560" height="315" src="https://www.youtube.com/embed/DdGVBZv46PI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



















<iframe width="560" height="315" src="https://www.youtube.com/embed/V27FQ6UBTPY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>