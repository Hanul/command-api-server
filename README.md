# command-api-server
API to call commands

## Usage
```js
require('command-api-server')({
    port : 8225,
    api : {
        'call-this' : [{
            delay : 10,
            folderPath : '/home/dev',
            commands : [
                'forever restartall'
            ]
        }]
    }
});
```