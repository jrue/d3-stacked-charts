## D3 Stack Charts

This is a simple template for making a line chart in D3. 

**src/stack-bar.html**

<img src="https://raw.githubusercontent.com/jrue/d3-stacked-charts/master/screenshots/screenshot1.png" width="50%" height="auto" style="max-width:50%;height:auto;">

**src/area-chart.html**

<img src="https://raw.githubusercontent.com/jrue/d3-stacked-charts/master/screenshots/screenshot1.png" width="50%" height="auto" style="max-width:50%;height:auto;">

**src/area-chart-fill.html**

<img src="https://raw.githubusercontent.com/jrue/d3-stacked-charts/master/screenshots/screenshot1.png" width="50%" height="auto" style="max-width:50%;height:auto;">

**src/stream-graph.html**

<img src="https://raw.githubusercontent.com/jrue/d3-stacked-charts/master/screenshots/screenshot1.png" width="50%" height="auto" style="max-width:50%;height:auto;">

## Install instructions

To install, fork this repo, then clone a copy to your computer. (Note: You will need [Node.js](https://nodejs.org/en/) installed for this command to work.) Open a Terminal window in the directory from where you cloned your repository, and run the following command:

```
npm install
```

Next, install Grunt globally if you don't have it already.

```
sudo npm install -g grunt-cli
```

Then, run grunt to initiate the watch task.

```
grunt
```

Open the URL in your browser and modify the files in the `src` folder. 

## Deploy to Github Pages

To deploy to Github, simply run the deploy command, which will copy the `dist` folder to gh-pages branch. NOTE: You should probably change one of the file names to `index.html`.

```
grunt deploy
```

