# telostat

This is the company website of `telostat`.

## Development

### Installing Yarn and Nodejs

In case you do not have Nodejs or Yarn installed on your system, please install them:

    https://github.com/nvm-sh/nvm#installing-and-updating

and install yarn:

    npm i -g yarn


No more static website generators to just build a landing page with single html and single css files.

First, install the development dependencies:

    yarn install

I even built a small dev environment with `serve` and `sass` commands.

Just run:

    yarn start

from the command line and it will start to serve your website at: 

http://localhost:5000

As you change the any styling file, it will re-compile the styles. Just refresh your browser tab and you are good to go.

### Custom Styling

There is a `index.scss` file under `./styles` directory. Make the style changes in that file then save it.


## Deployment

Nothing special here. Just run `yarn build` command and it will compile your `scss` files into one, big, compressed `styles.css` file under `public/` directory. This is your website. Deploy that `public` folder anywhere and it will work.