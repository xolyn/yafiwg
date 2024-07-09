# yafiwg

>
> A simple file index webpage generator for static webpage hosting services like Github Pages, Cloudflare R2,...
>

## demo
![image](https://github.com/xolyn/yafiwg/assets/118642042/9297a2f4-a174-4c71-961e-f198feca969b =250x250)
click here for a [demo](https://xolyn.github.io/file_tree.html)

## use
in cli, execute the following:
```bash
python yawifg.py <path/to/start>
```
where `path/to/start` indicates the folder you want to execute a "deep scan" of all files and folders to begin from. Angle brackets imply the optionality.

**The scanner will automatically ignore the `.git` folder and files within.** (Option to keep it will be added in future version)

> A common use is to place the `yafiwg.py` file under your github page repo folder and execute (you can use scripts to automatically trigger) it every time before you push your repo to remote. It solves the regret of not being able to view and easily jump back and forth among all your files in your github repo or some cloud storage/hosting services.  

### advantages
1. Light weight： only 2kB makes it able to run on even the crappiest device
2. High compatibility： HTML code that removes the fancy styles and properties that are not supported by old browsers. According to [Can I Use](https://caniuse.com/?search=details):
   > <img scr="https://caniuse.com/img/baseline/baseline-high-light.svg" width='20'>Baseline
   > 
   > Widely available across major browsers
3. Clarity and accuracy： Although use simple HTML elements, files' hierarchical relationships are well displayed and easy to understand. Optimized scanning mechanism on nested folders and empty folders.
4. Simple to use: One line of code, webpage's done compiling within a blink. Check any file in a simple click. 
