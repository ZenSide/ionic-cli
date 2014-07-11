Ionic-Cli
=========

The Ionic Framework command line utility makes it easy to start, build, run, and emulate [Ionic](http://ionicframework.com/) apps. In the future, it will also have support for our mobile development services and tools that make Ionic even more powerful.

## Installing

```bash
$ sudo npm install -g ionic
```

## Starting an Ionic App

```bash
$ ionic start myApp [template]
```
There are three choices of templates.

* Side-Menu (sidemenu)
* Tabs (tabs)
* Blank (blank)

## Testing in a Browser

```bash
$ ionic serve
```


## Adding a platform target

```bash
$ ionic platform ios android
```

## Building your app

```bash
$ ionic build ios
```

## Emulating your app

```bash
$ ionic emulate ios
```

## Running your app

```bash
$ ionic run ios


## Packaging an app (beta)

Using Ionic's service, you can compile and package your project into an app-store ready app without
requiring native SDKs on your machine.

```bash
$ ionic package debug android
```

The third argument can be either `debug` or `release`, and the last argument can be either `android` or `ios`.


## Cordova Commands

Ionic uses Cordova underneath, so you can also substitute Cordova commands to prepare/build/emulate/run, or to add additional plugins.

Note: we occasionally send anonymous usage statistics to the Ionic team to make the tool better.
