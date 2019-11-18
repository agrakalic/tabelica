# Tabelica
Tabelica is a simple, lightweight CSS/HTML templating starter package. Based on SASS, it contains basic yet useful features that will quickly get you off the ground for your next project.
## Features
- "Normalize" styles for all HTML5 elements
- Vertical rhythm based typography
- Responsive flexbox grid system with percentage based unit widths or completely flexible with self adjusting column widths. With or without gutter, you choose :)
- SVG inline icon system
- Advanced form element styles
- Simple customization with SASS variables
## What's in the box?
Tabelica package contains source files, as well as some demo pages to see it in action immediately after download. In `dist` folder you will find an `index.html` and compiled `css/main.css`. This would be your master template! If you feel more comfortable, you can use vanilla CSS as a starter.
Browse the files in `demo` folder to see how Tabelica looks like "out of the box". You will find examples for Tabelica's grid system, HTML element and form styles, SVG inline icons, as well as demonstration for vertical rhythm.
## Usage
Tabelica requires Node.js to run. If you don't have it installed already, go to the official website nodejs.org, download the package, open it and follow the wizard.
### Install
Download the Tabelica package to your project destination folder, open the command line interface and run:
```bash
npm install
```
to install the package and dependencies.
### Run
Start using the package by running:
```bash
npm run scss
```
This will start a watch task on all of the .scss files and compile the CSS code to the dist/css on every  edit.
### Recommendations
Instead of documentation, Tabelica have some demo files you can check out to see all the features in action. When getting started with Tabelica, good place to begin customizing is `src/scss/global/variables.scss`. It contains some basic parameters, sizes, colors, borders etc.
