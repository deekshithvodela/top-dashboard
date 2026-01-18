# HTML
This folder contains all the files related to HTML and CSS code.

## Folder structure
```plaintext
html/
├── README.md
├── assets
│   └── images
│       ├── css.png
│       ├── css.png:Zone.Identifier
│       ├── flexbox.jpg
│       ├── flexbox.jpg:Zone.Identifier
│       ├── hot-chocolate.jpg
│       ├── html.png
│       ├── html.png:Zone.Identifier
│       ├── starawberry-jam.webp
│       ├── sunny-side-up-egg.jpg
│       └── vdlogo.jpg
├── css
│   ├── recipes.css
│   └── styles.css
├── index.html
├── pages
│   ├── about.html
│   ├── e-logs
│   │   ├── css-e-log.html
│   │   ├── flexbox-e-log.html
│   │   └── html-e-log.html
│   ├── e-logs.html
│   └── recipes.html
└── recipe
    ├── hot-chocolate.html
    ├── strawberry-jam.html
    └── sunny-side-up-egg.html

```
## Introduction
I am currently using HTML and CSS to build this project.
I am using CSS FLexbox for layout.

## Main Layout

```plaintext

+--------------------------------------------------+
|                                                  |
|                 BODY                             |
|                 display:flex;                    |
|  +--------------------------------------------+  |
|  |              NAVIGATION BOX                |  |
|  |              flex-grow:0;                  |  |
|  |                                            |  |
|  +--------------------------------------------+  |
|                                                  |
|  +--------------------------------------------+  |
|  |                                            |  |
|  |                                            |  |
|  |              MAIN SECTION BOX              |  |
|  |              flex-grow:1;                  |  |
|  |                                            |  |
|  |                                            |  |
|  +--------------------------------------------+  |
|                                                  |
|  +--------------------------------------------+  |
|  |                FOOTER BOX                  |  |
|  |                flex-grow:0;                |  |
|  |                                            |  |
|  +--------------------------------------------+  |
|                                                  |
+--------------------------------------------------+


```