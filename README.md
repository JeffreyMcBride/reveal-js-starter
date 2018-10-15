# reveal-js-starter Repo
Starter repo for using Reveal.js, including local and CDN.

## Installation
### **Clone Repo**
    git clone https://github.com/JeffreyMcBride/reveal-js-starter.git

### **Change Directory Into Local Repo**
    cd reveal-js-starter

### **Install Dependency Packages**
    npm install

### **Start http-server (Allows for Directory Listing)**
    npm run http-server
    http://localhost:8080

### **Or Start lite-server (Allows for BrowserSync Auto Page Refreshing)**
    npm run lite-server
    http://localhost:3000/cdn.html
    http://localhost:3000/local.html
    http://localhost:3000/demo.html
    http://localhost:3000/demo-md.html
    
## Directory Structure
### **/.gitignore**
    Ignore node_modules/ for git commits and push

### **/cdn.html**
    HTML file using Reveal.js via CDN and external Markdown file demo.md, FYI this causes Speaker Notes to not work properly

### **/demo.html**
    HTML file from Reveal.js folder, demonstrates more Reveal.js capabilities 

### **/demo.md**
    Markdown file used with sample.html, included to demo more sophisticated Reveal.js slide syntax

### **/local.html**
    HTML file using Reveal.js via a local installation and external Markdown file demo.md, use npm install to download packages 

### **/package-lock.json**
    npm file for tracking package changes

### **/package-lock.json**
    npm file with settings for application and its dependencies, includes scripts for starting local dev web server 

### **/README.md**
    This File
