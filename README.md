You must have TrueAutomation client, Node.js and NPM installed on your machine.

## How to run test:

* Checkout the project

```
git clone https://github.com/pyavchik/trueautomation-webdriverio-remote.git
```

* Init the project, using `trueautomation init` command

* Install necessary packages, using the command `npm install`


## Running tests

### ChromeDriver

To run a test, at first you need to start a remote ChromeDriver, use a separate command line to do this.
If you do not have a ChromeDriver on your machine, you can use the ChromeDriver already downloaded with the project.

To use the downloaded ChromeDriver, just run it from the project's root folder:

```bash
environment/chromedriver
```

Then, you can run the default test:

```bash
npm test
```

### Geckodriver

To run a test, at first you need to start a remote Geckodriver, use a separate command line to do this.
If you do not have a Geckodriver on your machine, you can use the Geckodriver already downloaded with the project.

To use the downloaded Geckodriver, just run it from the project's root folder:

```bash
environment/geckodriver
```

Then, you can run the default test:

```bash
npm test

```
