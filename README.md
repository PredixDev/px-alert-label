# px-alert-label [![Build Status](https://travis-ci.org/predixdesignsystem/px-alert-label.svg?branch=master)](https://travis-ci.org/predixdesignsystem/px-alert-label)

---

## Overview

Px-alert-label is a Predix UI component used to draw attention to a particular piece of information on the screen.

## Usage

### Prerequisites

1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

### Getting Started

First, install the component via bower on the command line.

```
bower install px-alert-label --save
```

Second, import the component to your application with the following tag in your head.

```
<link rel="import" href="/bower_components/px-alert-label/px-alert-label.html"/>
```

Finally, use the component in your application:

```
<px-alert-label type="important"></px-alert-label><span>Drink your beer!</span>
```

<br />
<hr />

## Documentation

Read the full API and view the demo [here](https://www.predix-ui.com/#/modules/px-alert-label).

## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### LiveReload

By default gulp serve is configured to enable LiveReload and will be watching for modifications in your root directory as well as `/css`.

## GE Coding Style Guide

[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

### Known Issues

Please use [Github Issues](https://github.com/predixdesignsystem/px-alert-label/issues) to submit any bugs you might find.
