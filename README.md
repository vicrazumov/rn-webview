## Messaging between React Native and WKWebView

[CRAlpha's react-native-wkwebview](https://github.com/CRAlpha/react-native-wkwebview) infused with [R1ZZU's messaging](https://github.com/R1ZZU/react-native-webview-messaging)

## Usage
To send message from WKWebView to React Native open console and execute 
```
window.webkit.messageHandlers.reactNative.postMessage('f251c210-e7c9-42fa-bae3-b9352ec3722a' + JSON.stringify({ type: 'text', payload: 'ttt'}))
```