<div align="center">
  <a href="https://koyeb.com">
    <img src="https://www.koyeb.com/static/images/icons/koyeb.svg" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Koyeb Serverless Platform</h3>
  <p align="center">
    Deploy a MERN application using MongoDB Atlas, Express, and React on Koyeb
    <br />
    <a href="https://koyeb.com">Learn more about Koyeb</a>
    ·
    <a href="https://koyeb.com/docs">Explore the documentation</a>
    ·
    <a href="https://koyeb.com/tutorials">Discover our tutorials</a>
  </p>
</div>


## About Koyeb and the example MERN application using MongoDB Atlas, Express, and React

Koyeb is a developer-friendly serverless platform to deploy apps globally. No-ops, servers, or infrastructure management.
This repository contains a MERN blog clone you can deploy on the Koyeb serverless platform for testing.

This example application is designed to show how an application using MongoDB Atlas, Express, and React can be deployed on Koyeb.

## Getting Started

Follow the steps below to deploy and run the MERN application with MongoDB Atlas on your Koyeb account.

### Requirements

You need a Koyeb account to successfully deploy and run this application. If you don't already have an account, you can sign-up for free [here](https://app.koyeb.com/auth/signup).

### Deploy using the Koyeb button

The fastest way to deploy the MERN application is to click the **Deploy to Koyeb** button below.

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/apps/deploy?type=git&repository=github.com%2Fkoyeb%2Fexample-mern-application&branch=main&build_command=yarn%20build-client&run_command=yarn%20start&env[CONNECTION_STRING]=&ports[3000]=&name=mern-on-koyeb)

Clicking on this button brings you to the Koyeb App creation page with everything pre-set to launch this application.

_To modify this application example, you will need to fork this repository. Checkout the [fork and deploy](#fork-and-deploy-to-koyeb) instructions._

### Fork and deploy to Koyeb

If you want to customize and enhance this application, you need to fork this repository.

If you used the **Deploy to Koyeb** button, you can simply link your service to your forked repository to be able to push changes.
Alternatively, you can manually create the application as described below.

On the [Koyeb Control Panel](//app.koyeb.com/apps), click the **Create App** button to go to the App creation page.

1. Name your application, for example `mern-blog`. 
2. For "Deployment method", choose Github.
3. Select the git repository and specify the branch where you pushed the code to. In my case, `main`.
4. In application configuration, add the build command "yarn build-client" and the start command "yarn start"
5. Add a Secret environment variable with the key `CONNECTION_STRING` and the connection string provided by Mongo Atlas.
6. Enter the port 3000, as this is the one we exposed from the server.
7. Name the service, for example `main`.

You land on the deployment page where you can follow the build of your application. Once the build is completed, your application is being deployed and you will be able to access it via `<YOUR_APP_NAME>-<YOUR_ORG_NAME>.koyeb.app`.

## Contributing

If you have any questions, ideas or suggestions regarding this application sample, feel free to open an [issue](https://github.com/koyeb/example-mern-application/issues) or fork this repository and open a [pull request](https://github.com/koyeb/example-mern-application/pulls).

## Contact

[Koyeb](https://www.koyeb.com) - [@gokoyeb](https://twitter.com/gokoyeb) - [Slack](http://slack.koyeb.com/)
