motelicemachine.github.io
=========================

Motelicemachine.com is built with Jekyll and hosted on Github. Jekyll is a static html-generator, which builds html-files from templates and markdown-files. Github is a code host which makes it easy to collaborate on projects. A project on Github is called a repository, or repo for short. 

The advantage of hosting the site on Github, is that the site is re-built automatically on Github when there are changes to the source-files – while other similar build-tools requires that we build the site locally before transferring the files to the web server.

The advantage of using a static html-generator instead of using a cms like Wordpress, is that we don’t have to worry about databases and server-side scripts – it’s just files. The site will also load much faster for the users, because the pages are generated beforehand – instead of on-the-fly when they are loaded in the browser.

Text-files can be altered/created directly on Github in a web browser. Binary-files, such as images, must be pushed to Github using git. 

The easiest way to do this, is to use the Github app for Mac or Windows.

Download and install the app, and then log-in using your Github username and password.

The next thing we have to do, is to clone the repo – which creates a local copy. 

Push the "clone to computer"-button and choose where you want to save the local copy. Add a new image to the slideshow-folder, and change the value of the "main_image"-key in _config.yml to the name of the new image. Use a simple Text Editor like notepad or similiar when editing text-files, do not use Word. You can also change the _config.yml-file directly on Github in a browser after you have uploaded a new image instead of changing the file locally first. 

Return to the Github-app. Double-click the name of the repo under "Cloned repositories". Add a description of what you have changed in the "commit summary"-field, and push the commit & sync button. (If the button label is only "commit", then push the button to the left of the commit-button to change the behavior of the button.)




*To be continued…*

## Resources

- [Github for Windows](https://windows.github.com)
- [Github for Mac](https://mac.github.com)
