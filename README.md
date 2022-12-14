# howto-node-red-alter

# Node-RED

http://nodered.org

[![Build Status](https://travis-ci.org/node-red/node-red.svg?branch=master)](https://travis-ci.org/node-red/node-red)
[![Coverage Status](https://coveralls.io/repos/node-red/node-red/badge.svg?branch=master)](https://coveralls.io/r/node-red/node-red?branch=master)

Low-code programming for event-driven applications.

![Node-RED: Low-code programming for event-driven applications](http://nodered.org/images/node-red-screenshot.png)

## Quick Start

Check out http://nodered.org/docs/getting-started/ for full instructions on getting
started.

1. `sudo npm install -g --unsafe-perm node-red`
2. `node-red`
3. Open <http://localhost:1880>

## Getting Help

More documentation can be found [here](http://nodered.org/docs).

For further help, or general discussion, please use the [Node-RED Forum](https://discourse.nodered.org) or [slack team](https://nodered.org/slack).

## Developers

If you want to run the latest code from git, here's how to get started:

1. Clone the code:

        git clone https://github.com/node-red/node-red.git
        cd node-red

2. Install the node-red dependencies

        npm install

3. Build the code

        npm run build

4. Go to `C:\Users\user\Documents\node-red-al-v3\node-red\packages\node_modules\node-red\settings.js`

5. Change Port

6. Create User Admin  
   
        node-red admin hash-pw
        
7. Copy hash password to `setting.js` (adminAuth)

8. ### IMPORTENT 

    goto `packages.json` (main folder).
    
    for key `scripts` >> `start` change value to `node packages/node_modules/node-red/red.js --userDir ./packages/node_modules/node-red`

9. Run

        npm start



## Copyright and license

Copyright OpenJS Foundation and other contributors, https://openjsf.org under [the Apache 2.0 license](LICENSE).
