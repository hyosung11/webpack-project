# webpack-project
Learning how to use webpack

Quick Fix: Babel 7 Plugins
Just a heads up on a quick correction from the previous video. To add a plugin to babel compiler you would need to have it under the plugin property in package.json file like this:

```Javascript
{
  "babel": {
    "presets": [ ... ],
    "plugins": [ ... ],
  }
}
```

Resources: Webpack 4 Configurator
Configuration shouldn't be hard. As time goes one, I believe we will move towards less and less configuration. Here is a great tool to make configuring your Webpack easy. Enjoy playing with it! http://web.jakoblind.no/webpack-config/
