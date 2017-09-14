# Simple Academic Website Template
Simple, intuitive, mobile-friendly (Bootstrap-enabled) website for academics entering the market.

## Description
Many academics entering the market today are served by having a digital footprint which describes their research, teaching, and other relevant experience. While many 3rd-party hosted solutions exist, such as Wordpress.com, for those familiar with HTML and who wish to have their own hosted domain, this simple   template offers a quick way to get a presence online. It's also useful to experiment with HTML, CSS and learn more about the [Bootstrap Framework](https://getbootstrap.com/getting-started/).

[DOWNLOAD THE ZIPPED FILES](https://github.com/randal-sean-harrison/academic-website-template/archive/master.zip)


## What's included
The Zipped file contains the following folders and files:

```html
academic-website-template/
├── css/
│   ├── academicons.min.css
│   ├── custom.css
│   └── font-awesome.min.css
│   
├── docs/
│
├─── favicons/
│   ├── -- MULTIPLE FILENAMES.png (various sizes)
│   ├── browserconfig.xml
│   ├── manifest.json
│   └── favicon.ico
│
├─── fonts/
│   ├──academicons.eot
│   ├──academicons.svg
│   ├──academicons.ttf
│   ├──academicons.woff
│   ├──fontawesome-webfont.svg
│   ├──fontawesome-webfont.ttf
│   ├──fontawesome-webfont.woff
│   ├──fontawesome-webfont.woff2
│   └──FontAwesome.otf
│
├── img/
│   ├── jane-smith-logo.png
│   └── ilya-brik.png
│   
├── humans.txt
├── index.html
├── LICENSE.md
├── README.md
├── research.html
├── teaching.html
└── vitae.html
```

## The Favicon
The favicon is the logo-type icon which appears in browser bars and in the tabs of browser windows next to the Web page name. However, it's not required and may be removed by:

1. Deleting the contents of the **favicons/** folder.
2. Deleting the following lines from the **index.html**, **research.html**, **teaching.html**, and **vitae.html** files:

```html
<!-- favicons: these show at the top of your browser tab, etc. Visit http://www.favicon-generator.org/ to generate your own favicons -->
<link rel="apple-touch-icon" sizes="57x57" href="/apple-icon-57x57.png">
<link rel="apple-touch-icon" sizes="60x60" href="/apple-icon-60x60.png">
<link rel="apple-touch-icon" sizes="72x72" href="/apple-icon-72x72.png">
<link rel="apple-touch-icon" sizes="76x76" href="/apple-icon-76x76.png">
<link rel="apple-touch-icon" sizes="114x114" href="/apple-icon-114x114.png">
<link rel="apple-touch-icon" sizes="120x120" href="/apple-icon-120x120.png">
<link rel="apple-touch-icon" sizes="144x144" href="/apple-icon-144x144.png">
<link rel="apple-touch-icon" sizes="152x152" href="/apple-icon-152x152.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-icon-180x180.png">
<link rel="icon" type="image/png" sizes="192x192" href="/android-icon-192x192.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="96x96" href="/favicon-96x96.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/manifest.json">
<meta name="msapplication-TileColor" content="#ffffff">
<meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
<meta name="theme-color" content="#ffffff">
```

If you love the favicon, you may create your own by visiting [Favicon Generator](https://www.favicon-generator.org/) and upload your own image to generate your favicon files. Next, download the generated favicon files and simply replace the entire contents of your local **Favicons/** folder with the files generated by the Favicons Generator site. Easy peasy.


## Linking Your Vitae to a Google Doc
By embedding a Google Doc in the **Vitae** page, you may make edits directly to your vitae (qua Google Doc) which will be reflected in the Website in real time. To point the iframe to __your own__ Google Doc, then, do the following:

1. look for the following code on line 109 of the **Vitae.html** file:

```html
<iframe width='100%' height='5200' frameborder='0' scrolling='no' src='https://docs.google.com/document/d/1_AJVKpKeyh_NFvlKA6nOT7GbR8NuFfJjQn-5tIumWpY/preview' allowfullscreen></iframe>
```

2. Replace the **1_AJVKpKeyh_NFvlKA6nOT7GbR8NuFfJjQn-5tIumWpY** bit with your own unique Google Doc ID. This can be copied from the browser's URL bar once inside the Google Doc.

![image of unique Google Doc ID in browser URL bar](http://www.randalseanharrison.com/img/google-doc-id.png)



## Linking Your Vitae to a PDF
Rather than embed a Google Doc, you may wish to place a pdf of your vitae in the **docs** folder and link directly to that. To do so, simply replace this code...

```html
<iframe width='100%' height='5200' frameborder='0' scrolling='no' src='https://docs.google.com/document/d/1_AJVKpKeyh_NFvlKA6nOT7GbR8NuFfJjQn-5tIumWpY/preview' allowfullscreen></iframe>
```
... with this code (replacing **vitae.pdf** with the real name of your vitae file):  

```html
For more information, see my <a href="docs/vitae.pdf">Curriculum Vitae</a>
```
If you choose this option, I recommend you omit the Vitae page from the Website/navigation entirely, and add this line to the bottom of the About Me page (index.html)

## Creator
Randal Sean Harrison, Ph.D.
Emerging Technologies Librarian
University of Notre Dame
<https://randalseanharrison.com>

## Copyright License and Attribution
A few parts of this project are not in the public domain. Attribution and licensing information for those parts are described in detail in [License](https://github.com/randal-sean-harrison/academic-website-template/blob/master/LICENSE.md).

The rest of this project is in the worldwide public domain, released under the CC0 1.0 Universal public domain dedication.
