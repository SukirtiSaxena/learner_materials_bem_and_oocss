# How to run SASS
Sass will take your preprocessed file and save it as a normal CSS file that you can use in your website.

## Steps to run .scss file and get .css

Step 1: First install Sass using the options below :
    If you use Node.js, you can install Sass using npm by running -

    npm install -g sass

Step 2: run sass --version to be sure it installed correctly. If it did, this will include 1.43.4. 

Step 3: Once Sass is installed, you can compile your Sass to CSS using the sass command. You'll need to tell Sass which file to build from, and where to output CSS to. For this website use following command -

    sass styles.scss styles.css

Step 4: Now css file is generated and you can view index.html with full styles!!