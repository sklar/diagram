[contributing]:  CONTRIBUTING.md
[changelog]:     CHANGELOG.md



# diagram


Simple alternative of a [Bank Payment System](http://www.bankpaymentsystem.com/key-features) Key Features schema.

![node](http://img.shields.io/badge/node-6.9.x-7FC100.svg?style=flat-square)
![libsass](http://img.shields.io/badge/libsass-4.5.x-C44C8D.svg?style=flat-square)


### Table of Contents

* [Requirements](#requirements)
* [Quick Start](#quick-start)
* [Usage](#usage)

------


## Requirements

1. [Git](http://git-scm.com/downloads)    
1. [Node](https://nodejs.org/en/download/) `6.9.x`  


## Quick Start

1. Clone repo  

    ```
    https://github.com/sklar/diagram.git
    ```
1. Install dependencies  

    ```
    npm install
    ```
1. Generate distribution  

    ```
    npm run build
    ```

1. Run

    ```
    npm start
    ```


## Usage

You can get list of all available scripts by running `npm run`.

| script          | description                                                                                              |
| --------------- | -------------------------------------------------------------------------------------------------------- |
| __build__       | Build `dist`                                                                                             |
| __clean__       | Clean up npm cache, `node_modules` and other compilation directories                                     |
| __server__      | Run `dev` server                                                                                         |
| __start__       | Build `dist` and run `dev` server with watcher                                                           |
| __watch__       | Watch source for changes and rebuild on change                                                           |
