# Jupyter Notebook Commands & Shortcuts
(fork from fastai_deeplearn_part1/tools/jupyter_notebook.md)

In [Kaggle 2017 data science survey](https://www.kaggle.com/surveys/2017) of 16K data scientists, Jupyter Notebook came up as 3rd most important self-reported tool for data science.  

## Notebook Features
* can add text, images, code, shell commands - all in one place
* can document what we're doing as we go along and code
* can put pictures, videos, html tables, interactive widgets
* great experimentation environment

## Help
<kbd> h </kbd> shows the list of shortcuts

## Notebook Commands / Shortcuts
* <kbd> Shift + Enter </kbd> to run cell  
* <kbd> Shift + Tab </kbd>  First time pressing:  tells you what parameters to pass 
* <kbd> Shift + Tab </kbd> Press 3 times:  gives additional info about method

### Select multiple cells 
<kbd> ESC </kbd>    <kbd> Shift+ :arrow_up: </kbd>  extend select cells above  
<kbd> ESC </kbd>   <kbd> Shift+ :arrow_down: </kbd>  extend select cells below  


## Notebook Source Code Access

### look at documentation for code (or function)
* <kbd> ? </kbd> + <kbd> function name </kbd>  
  * Example: <kbd> ?ImageClassifierData.from_paths </kbd>
  
### look at source code for a function
* <kbd> ?? </kbd>  + <kbd> function name </kbd>   
  * Example:  <kbd> ??ImageClassifierData.from_paths </kbd>

### find out where a particular function or class comes from
* <kbd> function name </kbd>, then <kbd>Shift + Enter </kbd>  
  * Example of Input:  <kbd> ImageClassifierData </kbd> <kbd>Shift + Enter </kbd>
    * Example of Output: `fastai.dataset.ImageClassifierData`
  * Example of Input:  <kbd> display </kbd> <kbd>Shift + Enter </kbd>
    * Example of Output: `<function IPython.core.display.display>`
    

### find out what parameters that the function can take, also shows default parameter options
* Within function, <kbd>Shift + Tab </kbd> 
* `object`, then <kbd> Tab </kbd> shows all the options for that object or function

### run a shell command 
* From with a code cell, prefex the bash command by an exclamation mark, ex:
```bash
!ls {PATH}
```

## Convert your notebooks to .md 
```bash
jupyter nbconvert --to <output format> <input notebook> 
```

## Jupyter Notebook Gist Sharing
- press the Gist share button (the yellow highlighted one). It will generate a link for your Jupyter notebook to share for trouble-shooting.

---
## Resources

* [How to Change Your Jupyter Notebook Theme](https://jcharistech.wordpress.com/2017/05/18/how-to-change-your-jupyter-notebook-theme/)
