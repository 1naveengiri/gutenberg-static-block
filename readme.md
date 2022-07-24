# Gutenberg Static Block
this is just an example of how to create a simple static block in gutenberg. 


## Create Gutenberg block
A WordPress plugin is a set of files within the site’s wp-content/plugins directory. For our tutorial, we will use the @wordpress/create-block package to generate the necessary plugin files.

you can use following command to create a plugin with Gutenberg block. 

`npx @wordpress/create-block gutenberg-static-block`


## Production build

Use `npm run build` for running once to create a “production” build. This compresses the code down so it downloads faster, but makes it harder to read using browser tools—good for final deployment but not while developing.


## local build

Use `npm run start` for creating a “development” build, this does not compress the code so it is easier to read using browser tools, plus source maps that make debugging easier. Additionally, development build will start a watch process that waits and watches for changes to the file and will rebuild each time it is saved; so you don’t have to run the command for each change.





