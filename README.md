# PUI Cursor
[![Build Status](https://travis-ci.org/pivotal-cf/pui-cursor.svg)](https://travis-ci.org/pivotal-cf/pui-cursor)


## A javascript implementation of cursors for use in a React Flux architecture

PUI Cursor is loosely based on [OM Cursors](https://github.com/omcljs/om/wiki/Cursors) and uses a [weak map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap) to hold data privately.

This allows for the separation of application state from the DOM and from web components.  


To run the tests:
`npm test`



Also contains pure render mixin for cursors.

Developed with React 0.12

(c) Copyright 2015 Pivotal Software, Inc. All Rights Reserved.