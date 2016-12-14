#Node Version Manager

Install the latest v5.x.x release of node:

`nvm install 5`

Install the specific release of node:

`nvm install 5.8.0`

Switch to a specific version:

`nvm use 6`

Install node + all global packages of currently used version:

`nvm install node --reinstall-packages-from=node`

Reinstall global packages contained in <VERSION> to the current version in use:

`nvm reinstall-packages <VERSION>`

Set an alias for a specific release:

`nvm alias my-alias <VERSION>`


Thx to https://michael-kuehnel.de/node.js/2015/09/08/using-vm-to-switch-node-versions.html
