---
id: doc1
title: Installation 
sidebar_label: Installation
---

This guide explains how to set up your environment for Angular development using the Angular CLI tool. It includes information about prerequisites, installing the CLI, creating an initial workspace and starter app, and running that app locally to verify your setup.

## Prerequisites

Before you begin, make sure your development environment includes Node.js® and an npm package manager.

## Node.js

Angular requires a current, active LTS, or maintenance LTS version of Node.js. See the engines key for the specific version requirements in our package.json.

In a terminal/console window, run the following to check your node version

```
$ node -v
```

To get Node.js, go to [nodejs.org](https://nodejs.org/).   

## NPM Package Manager

Angular, the Angular CLI, and Angular apps depend on features and functionality provided by libraries that are available as [npm packages](https://docs.npmjs.com/about-npm). To download and install npm packages, you must have an npm package manager.

This setup guide uses the [npm client](https://docs.npmjs.com/cli/install) command line interface, which is installed with Node.js by default.

To check that you have the npm client installed, in a terminal/console window run:

```
$ npm -v
```

## Angular CLI

You use the Angular CLI to create projects, generate application and library code, and perform a variety of ongoing development tasks such as testing, bundling, and deployment.

### Install the Angular CLI globally.

To install the CLI using npm, open a terminal/console window and enter the following command:

```
$ npm install -g @angular/cli
```