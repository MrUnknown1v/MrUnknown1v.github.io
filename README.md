
# A simple Github Pages template for academic personal website.

## Preview
![Screenshot of the Website](screenshot_full.png)


## Introduction

This is an academic personal website template based on [bootstrap](https://github.com/StartBootstrap/startbootstrap-new-age).

The template is designed to integrate Markdown files as content input.  There's no need to compile the webpage before deployment.  Upon loading, the Markdown files are automatically parsed and embedded into the page.

This template supports LaTeX formula input. You can use `$...$` and `\(...\)` as delimiters for inline-math, or use `$$...$$` and `\[...\]` as delimiters for display-math. Macros such as `\ref{...}`, `\eqref{...}`, and `\begin{equation}...\end{equation}` are also supported. See [MathJax](https://docs.mathjax.org/en/latest/index.html) for more details.

:milky_way: Demo: https://mrunknown1v.github.io/


## Getting Start



### 1. Edit page content

(1) Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) Modify the content of each section, which corresponds to `contents/*.md`.

(3) Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) Push it: 
```
git commit -am 'init'
git push
```


### 2. Enjoy

Fire up a browser and go to `https://<username>.github.io`



## License

Copyright Maximus Perez 2025. Licensed under an MIT license. You can copy and mess with this template.
