# Sonora's Tire Shop Static Website
Static website for local Phoenix tire shop at [http://sonoratires.com](http://sonoratires.com).

## Requirements

- Harp (static site generator)
- Gulp (node.js task runner)
- Surge (free static site hosting)

```
npm install -g harp gulp surge
```


## How To Use

Assuming you have NPM (Node Package Manager) on your machine, just run:
```
sudo npm install
```

First clone the repository to your working directory
```
git clone https://github.com/PochoLabs/llantera-sonoras.git
```
Move into that directory
```
cd llantera-sonoras
```
To start a local server with live reload, run:
```
gulp
```

### Compiling and Deploying

Once your are done editing it is time to compile and deploy to surge. To get that output simply run the command:
```
gulp compile
```
This will generate a `/www` folder in your directory where the compile and minified html, css, and JavaScript will be.

To deploy:
```
surge
```
