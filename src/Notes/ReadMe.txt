Angular:
  AngularJS
  Angular 2
  Angular 4 (stable version)
  Angular 5 (latest)

--------------------------------------------------------------------------------------------------------------------------------------------------------------
Note:
Server Side Controls -- Whenever use will request entire page will be compiler to HTML. The Server side processing is slow.
--------------------------------------------------------------------------------------------------------------------------------------------------------------
Angular:
    Advantages:
      - Rendering for any language and bind using HTML.
      - No server side compilation.
      - Faster Rendering time.
      - SPA - Single Page Application (MVC). Entire HTML gets loaded first (first request) time on the browser. After that only API calls will go to server.
      - Easy Integration with REST API.
      - Separation of code and build/write the code in a modular way.
      - Due to the point above, its easy to maintain.
      - Easy to test and debug. (Testing - Jasmine & Karma)
      - Its a framework and not a library.
          - It follows design patterns to solve the architectural issues.
          - Provides flexibility so you can replace any internal library with other external libraries.
--------------------------------------------------------------------------------------------------------------------------------------------------------------
Files and Folders On the Project Structure:

tslint.json - It will give us warnings and messages in case we dont follow the best practices etc.
tsconfig.json - Main typescript configuration file
README.md -
protractor.conf.js - This is configuration file for e2e or Automation testing.
package.json - [IMPORTANT] -
package-lock.json - [OPTIONAL] - This is where the packages are getting loaded from.
karma.conf.js - This is config file of Unit Testing.  No changes required here.
.gitignore - Items that we dont want to checkin on GIT.
.angular-cli.json - Master configuration file for an Angular application used for load and execution.
src -
  typings.d.ts - This is the type definition file.
  tsconfig.spec.json - This is the typescript configuration file for all of our typescript unit testcases.
  tsconfig.app.json - This is typescript configuration file for Angular components.
  test.ts - This file is required by karma.conf.js and loads recursively all the .spec and framework files
  styles.css - Any CSS code we write here will be avaiable to entire Application. But we can integrate other CSS too.
  polyfills.ts - This is to address browser compatibility issues.
  main.ts - This is the entrypoint of the code and the main.ts and platformBrowserDynamic().bootstrapModule(AppModule) is the first method to be invoked.
  index.html - This is the master page.
  favicon.ico - Home page title bar fav icon.
  environment -
    environment.prod.ts -
    environment.ts -
  assets
    .gitkeep -
  app
    app.component.css -
    app.component.html -
    app.component.spec.ts -
    app.component.ts -
    app.module.ts -
--------------------------------------------------------------------------------------------------------------------------------------------------------------
