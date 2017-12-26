
Install commands

sudo npm install -g live-server
sudo npm install -g babel-cli

yarn init
yarn add babel-preset-react
yarn add babel-preset-react babel-preset-env

babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch