This repository shows how to easily deploy applications to S3 + Cloudfront using Gulp.

### Getting Started
To add this to your application, do the following.
 - Add the devDependencies provided in this package.json file to your devDependencies.
 - Type ```npm install```
 - Copy the gulpfile.js (or append the contents) to your application directory.
 - Copy the .env.example and rename it to ```.env``` in your application.
 - Add all the parameters to this file
 - **IMPORTANT:** Add ```.env``` to your .gitignore file!

You should now be able do the following.

```gulp deploy:dev``` - To deploy to development environment.
```gulp deploy:prod``` - To deploy to production environment.
