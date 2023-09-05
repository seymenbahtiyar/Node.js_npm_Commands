
# Node.js and npm Commands

This document provides a quick reference guide for the most commonly used Node.js and npm commands.

**Check Node.js Version**:
```shell
node -v
```
Displays the installed Node.js version.

**Check npm Version**:
```shell
npm -v
```
Displays the installed npm version.

**Initialize a New Node.js Project**:
```shell
npm init
```
Starts a guided process to create a new Node.js project and generates a `package.json` file.

**Install a Package**:
```shell
npm install <package-name>
```
Installs a Node.js package. For example, `npm install express` installs the Express.js library.

**Add a Package Locally to Your Project**:
```shell
npm install <package-name> --save
```
Adds a package to your project's `package.json` file as a dependency.

**Remove Packages**:
```shell
npm uninstall <package-name>
```
Removes a package from your project.

**Install a Package Globally**:
```shell
npm install -g <package-name>
```
Installs a package globally, making it available for all your projects.

**Update Project Dependencies**:
```shell
npm update
```
Updates the dependencies in your project.

**Check for Outdated Packages**:
```shell
npm outdated
```
Checks if packages in your project are outdated.

**Run Your Node.js Application**:
```shell
node <file-name.js>
```
Runs a Node.js application.

**Publish Your Packages (with npm)**:
```shell
npm publish
```
Used to publish your own package on npm.

**Delete Your Packages (with npm)**:
```shell
npm unpublish <package-name> --force
```
Used to delete your package from npm.

