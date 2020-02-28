# ideal-react
WIP for idealized React + Redux + Node + Saga + Jest

Here is the basic structure. I need to modify create-react-app to eventually put these into place.

```
Idealized React + Redux + Saga + Jest Structure

~/User/kitrok/projects
/projectFoo
    +--/deploy
    +--/dist
    +--/node_modules
    +--/src
    |   +--/client
    |   |   +--/actions
    |   |   |   +--index.js
    |   |   |   +--fooa.js
    |   |   |   +--foob.js
    |   |   |   + ...
    |   |   | 
    |   |   +--/components
    |   |   |   +--/FooThingA
    |   |   |   |   +--foothinga.jsx
    |   |   |   |   +--foothinga.scss
    |   |   |   |   + ...
    |   |   |   | 
    |   |   |   +--/MainApp
    |   |   |       +--globals.scss
    |   |   |       +--mainapp.jsx
    |   |   |       +--mainapp.scss
    |   |   |       +--responsive.scss
    |   |   |       +--responsive-320.scss
    |   |   |       +--responsive-480.scss
    |   |   |       +--responsive-640.scss
    |   |   |       +--responsive-768.scss
    |   |   |       +--responsive-1024.scss
    |   |   |       +--responsive-1280.scss
    |   |   | 
    |   |   +--/enums
    |   |   |   +--foomodes.js
    |   |   |   +--foostates.js
    |   |   |   +--fooflags.js
    |   |   |   +--fooetcetera.js
    |   |   | 
    |   |   +--/i18n
    |   |   |   +--en.json
    |   |   |   +--en-AU.json
    |   |   |   +--en-GB.json
    |   |   |   +--fr.json
    |   |   |   +--fr-CA.json
    |   |   |   + ...
    |   |   | 
    |   |   +--/reducers
    |   |   |   +--index.js
    |   |   |   +--fooa.js
    |   |   |   +--foob.js   
    |   |   |   + ...
    |   |   |   
    |   |   +--/routes
    |   |   |   +--/foopatha
    |   |   |   |   +--index.js
    |   |   |   |   +--foopatha.scss
    |   |   |   | 
    |   |   |   +--/foopathb
    |   |   |   +--/foopathc
    |   |   |   + ..
    |   |   | 
    |   |   +--/saga
    |   |   |   +--index.js
    |   |   |   +--fooa.js
    |   |   |   +--foob.js
    |   |   | 
    |   |   +--/utils
    |   |       +--utilityfuncsa.js
    |   |       +--utilityfuncsb.js
    |   |       + ..
    |   | 
    |   +--/server
    |   |   +--/config
    |   |   |   +--fooconfig-dev.json
    |   |   |   +--fooconfig-stage.json
    |   |   |   +--fooconfig-prod.json
    |   |   |   + ..
    |   |   |
    |   |   +--/middleware
    |   |   |   +--index.js
    |   |   |   + ..
    |   |   |
    |   |   +--/views
    |   |       +--/viewa
    |   |       |  +--index.html
    |   |       |  + ..
    |   |       |
    |   |       +--/viewb
    |   |       + ..
    |   |  
    |   +--app.js
    |   +--application.scss
    |   +--client.js
    |   +--routes.jsx
    |   + ..
    | 
    +--/test
    |   +--/client
    |   |   +--/actions
    |   |   +--/reducers
    |   |   +--/utils
    |   |   + ..
    |   |
    |   +--/server
    |
    +--build.sh
    +--jest.config.js
    +--package.json
    +--package-lock.json
    +--README.md




```
