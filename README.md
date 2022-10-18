## Installation ⚒️

Installing Node & Gulp

1. First of all, make sure you have installed [Node](https://nodejs.org/en/) (LTS). If Node.js is already installed in your system, make sure the installed version is `LTS` and jump to step 2

2. Install the Gulp CLI: Open Terminal/Command Prompt and run the following command and wait until it finishes. If you have already installed Gulp CLI, you can skip this step and jump to step 3.

```bash
npm install --global gulp-cli
```

1. Navigate to the Sneat root directory and run following command to install necessaryl dependencies listed in `package.json`.

```bash
# Install yarn
npm install --global yarn

# Install necessary dependencies
yarn
```

4. Now, you are ready to run `npm` tasks, below command will start the server and watch the code using [browsersync](https://browsersync.io/). Open [http://localhost:3000/](http://localhost:3000/) to check your development 🚀.

```bash
# yarn
yarn serve
```
