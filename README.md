# My HTML/CSS A4 CV/RESUME 

This is my CV / resume done with HTML and CSS in a A4 format page :
- width: 210mm
- height: 297mm

I was tired of Microsoft Word ugly layout so I made this.

The CSS file has a rule to automatically adjust the format when you try to print the document.

## Requirements

- SASS 
  - Go to the [official website install page](https://sass-lang.com/install).
  - Choose **From Github**.
  - Download the version according to your OS.
  - Place the content in a folder called **sass**.

## Launch Application

- Launch sass with this command line in a terminal.
```
.\sass\sass .\style.scss .\style.css --watch --style compressed
```
- Open the **index.html** in the browser.
  
- Modify the code to feet your needs by changing the **index.html** and **style.css**.
  - Don't touch directly the **style.css** file as it is rendered by Sass from **style.scss**.
  
- In the browser, print the document and choose export to PDF.
  - Check if the background is rendered properlly.
  - Choose the A4 format (It should be selected by default).
  - Export.
  
- Done ! 
