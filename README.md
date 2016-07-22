# NotifyJS
A Java Script Notification plugin. Implements Google Material Design Snackbar Design Specs.

## Usage
```javascript
//Basic usage
notify("Notification Text goes here");

//Advanced Usage
notify("Advanced Notification", {duration: 2500, onAction: actionHandler, onFinish: finishHandler});
```

## Settings
- duration: Duration of the notification (default - 5 seconds)
- onAction: fired when the notification object is clicked
- onFinish: fired when the notification duration finsihes and the object is removed

## Possible enhancements
- Add animation while displaying Notification
