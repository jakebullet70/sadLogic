## Hexo Installation

This website uses [Hexo](https://hexo.io/) to generate itself. If you want to build the website, read the [docs](https://hexo.io/docs/) to install node.js via npm.

Node.js can be installed on windows using the [installer](http://nodejs.org/) or by installing the [node version manager for windows](https://github.com/coreybutler/nvm-windows).

Once node.js is installed, install hexo with `npm install -g hexo-cli`.

## Hexo Server

Hexo generates a normal static website that has no dependencies. You can generate and serve (for local testing) the website with Hexo.

To generate the website, navigate in the command prompt to the git repository folder and run:

```
hexo generate
```

This takes all of the stuff in the **.\source** and uses the **.\_config.yml** config file and **.\themes** folder to generate the website. This is generated website is put in the **.\public** folder.

To run and test the website, run:

```
hexo server
```

This creates a local webserver hosted at `http://localhost:4000`.