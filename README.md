The official source code of https://kahootsmasher.com

## Deployment

OS X, Linux and Windows:

```sh
git clone https://github.com/idiidk/kahoot-tools.git
cd kahoot-tools
sudo npm install
sudo npm run build
screen -S kahootsmasher
node kahoot-tools.js
```

To run kahoot-tools in dev mode, follow the steps above but replace ```npm run build``` with: ```npm run dev```
