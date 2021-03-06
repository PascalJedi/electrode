# Requirements

The requirements for setting up your development environment and your online deployments are described in the following sections.

### For Development On Your Local Machine
To generate and deploy your Electrode app and Electrode components, be sure your development environment includes the following requirements.

Install the following:

1.  [NodeJS LTS binary](https://nodejs.org/) version 8 or later

    -   We use `async/await` directly so Node 8 or later is required.

    -   We recommend a tool such as [nvm](https://github.com/creationix/nvm#install-script) for managing NodeJS installations.

2.  [electrode-ignite] and [xclap-cli]
    -   Electrode Ignite helps to bootstrap your development with Electrode.
    -   xclap-cli adds the global task runner command `clap`

```bash
npm install -g electrode-ignite xclap-cli
```

    -   You can Run the tool with just `ignite` and get an interactive menu or you can run it with command line arguments.

    -   Two examples of command line arguments:
        -   `ignite check-nodejs` - To verify your NodeJS and npm versions.
        -   `ignite generate-app` - To generate a new Electrode React app.

    -  Run `ignite check-nodejs` to verify.

#### Headless Chrome

Headless chrome brings all modern web platform features provided by Chromium and the Blink rendering engine to the command line. It is a great tool for automated testing and server environments where you don't need a visible UI shell.

In the Electrode Archetype App and Component, we are using Chrome Headless as the default option for automated testing.

In your Chrome browser, update Google Chrome if you see the option, and relaunch.

> Headless mode is available on Mac and Linux in Chrome 59. Windows support will be available in Chrome 60. To check what version of Chrome you are running, open chrome://version.

### For Online Deployments

-   A [Heroku](https://signup.heroku.com/dc) account + [CLI tools](https://devcenter.heroku.com/articles/heroku-command-line).
-   A [GitHub](https://github.com/) account.

Ready? Let's [build an Electrode app](../chapter1/quick-start/start-with-app.md).

[yo]: http://yeoman.io/

[yeoman]: http://yeoman.io/

[xclap-cli]: https://www.npmjs.com/package/xclap-cli

[generator-electrode]: https://www.npmjs.com/package/generator-electrode

[electrode-ignite]: https://www.npmjs.com/package/electrode-ignite
