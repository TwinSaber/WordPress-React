# WordPress-React - Plain

## Building & Running
This is a plain installation of React, version `17.0.2`. 

There are three files that have been added to allow it to be a WordPress theme, these are: 
- public/index.php
- public/style.css
- public/screenshot.png

To run the project for development, use the `npm start` command. 

To build the project for deployment as a WordPres theme, there are a few things to do:  

1. Add the `"homepage": "wp-content/themes/{react}",` line to the package folder, replacing `{react}` with the name of your theme folder. 

2. Use the `npm run build` command 

3. Place the `build` folder in to the `themes` folder of WordPress. 
