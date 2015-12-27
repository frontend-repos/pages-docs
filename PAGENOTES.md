# PAGE NOTES

Notes description

__GULP COMMANDS__

- __`gulp serve`__
    * fire up browser-sync
    * run several other gulp commands concurrently `gulp nunjucks`, `gulp post`
    * watches css files and pre-process, minifies, concat
    * watches html/nunjucks files and builds page templates and copies to destination directory
    - __options__
        * Build `gulp serve --build=production` copies templates to the dist folder.

- __gulp nunjucks__
    * watches html/nunjucks files and builds page templates and copies to destination directory
    * options
        * `gulp nunjucks --build=production`  copies templates to the dist folder.