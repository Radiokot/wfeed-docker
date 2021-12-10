# wfeed-docker
Docker compose setup for the Warm feed backend. 
Contains MySQL database, phpMyAdmin, [Updater](https://github.com/Radiokot/wfeed-updater) and [API](https://github.com/Radiokot/wfeed-api).
Ports for API and phpMyAdmin are available outside.

## Preparation
Fill the `keystore/updater-keystore.properties` file with the required secrets:
```
TUMBLR_CONSUMER_KEY=
TUMBLR_CONSUMER_SECRET=
TUMBLR_ACCESS_TOKEN=
TUMBLR_ACCESS_SECRET=
VK_ACCESS_TOKEN=
```
