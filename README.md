# yawifg
>
> A simple file index webpage generator for static webpage hosting services like Github Pages, Cloudflare R2,...
>

## demo
click here for a [demo](https://xolyn.github.io/file_tree.html)

## use
in cli, execute the following:
```bash
python yawifg <path/to/start>
```
where `path/to/start` indicates the folder you want to execute a "deep scan" of all files and folders from. Angle brackets imply the optionality.

**The scanner will automatically ignore the `.git` folder.** (Option to keep it will be added in future version)

### advantages
1. Light weight： only 2kB makes it able to run on even the crappiest device
2. High compatibility： HTML code that removes the fancy styles and properties that are not supported by old browsers. According to [Can I Use](https://caniuse.com/?search=details):
   > Baseline
   > 
   > Widely available across major browsers
3. Clarity and accuracy： Although use simple HTML elements, files' hierarchical relationships are well displayed and easy to understand. Optimized scanning mechanism on nested folders and empty folders.
4. Simple to use: One line of code, webpage's done compiling within a blink. Check any file in a simple click. 
