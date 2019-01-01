# wdio-v5-upgrade-helper-service
Utility library to allow usage of webdriverio v4 commands with webdriverio 5.0. Note the code in this experimential at this stage. For demo puproses only.

Installation instructions
```
git clone https://github.com/jdavis61/wdio-v5-upgrade-helper-service.git
npm install
npm run build
```

In your webdriver repo install locally.
```
npm install ../path/to/wdio-v5-upgrade-helper-service
```

Add the below to the wdio services property:
```
services: ['v5-upgrade-helper'],
```
