
## Installation

* Clone the project:

```bash
$ git clone https://github.com/versatica/mediasoup-demo.git
$ cd mediasoup-demo
$ git checkout v3
```

* Ensure you have installed the [dependencies](https://mediasoup.org/documentation/v3/mediasoup/installation/#requirements) required by mediasoup to build.

* Set up the mediasoup-demo server:

```bash
$ cd server
$ npm install
```

* Copy `config.example.js` as `config.js` and customize it for your scenario:

```bash
$ cp config.example.js config.js
```

**NOTE:** To be perfectly clear, "customize it for your scenario" is not something "optional". If you don't set proper values in `config.js` the application **won't work**.

* Set up the mediasoup-demo browser app:

```bash
$ cd app
$ npm install
```


## Run it locally

* Run the Node.js server application in a terminal:

```bash
$ cd server
$ npm start
```

* In a different terminal build and run the browser application:

```bash
$ cd app
$ npm start
```

* Enjoy.


