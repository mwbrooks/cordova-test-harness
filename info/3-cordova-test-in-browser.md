# Apache Cordova in Browser Testing

Unfortunately, mobile-spec will not run in the browser. This is because 
mobile-spec will not run the tests until the event `deviceready` has fired.

## DeviceReady Event

The `deviceready` event is emitted by Apache Cordova when your application starts.
The event fires when Apache Cordova has established the native-to-javascript
bindings that enable it's API.

## A Challenge

If you want to take on an alternative project, you could provide a mechanism
that fires the `deviceready` event when using a desktop browser. Talk to @mwbrooks
if you're interesting in trying to solve this.
