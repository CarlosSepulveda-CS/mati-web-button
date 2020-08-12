## Integrate [Mati KYC service](https://getmati.com/) to your website with Mati Web SDK

This is how it would look like in your HTML code:

```
<mati-button clientid="<YOUR_CLIENT_ID>" flowId="<YOUR_FLOW_ID>" metadata="<JSON_METADATA_STRING>"/>
```

And this is how it would look like with a "live" configuration:

```
<mati-button clientid="1234567890abcdef12345678" flowId="1234567890abcdef12345678" metadata='{"ourKey":"ourValue","anotherKey":"anotherValue"}' />
```

This is how the button would look like on your page:

<img src="https://gist.githubusercontent.com/rastyagaev/f4536bb44c4812c8079c035f62167eed/raw/5fabbb375d78e574f058306992177f22b396a9db/web-button-preview.png" width="211" />


### Integrate

Add this script to your `<script>` tag 

```
<script src="https://web-button.getmati.com/button.js"></script>
```

Get your Client ID and Flow ID from your Mati Dashboard and put this code snippet where you want it to be in your webpage

```
<mati-button clientid="<YOUR_CLIENT_ID>" flowId="<YOUR_FLOW_ID>"/>
```

### API

#### Button attributes

| Attribute name | Description                                                                                     |
|----------------|-------------------------------------------------------------------------------------------------|
| `clientid`     | The Client ID is a unique Identifier that you can get from your [Mati Dashboard](http://dashboard.getmati.com/)|
| `flowId`       | The Flow ID is a unique Identifier for your flow configuration that you can also get from your [Mati Dashboard](http://dashboard.getmati.com/)|
| `metadata`     | JSON string for sending information related to your verification. You can use it to pass User IDs or similar information |

### Examples

* Vanilla JS: see `index.html`

* Angular: https://codesandbox.io/s/angular-3z773

* React: https://codesandbox.io/s/interesting-boyd-xcg63
