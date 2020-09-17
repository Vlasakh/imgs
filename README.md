# Initial page

Check 2

![](.gitbook/assets/some.png)



| name | type | required | default | description | Example |
|:-:|:-:|:-:|:-:|-|-|
| endpoint | string | + |  |  |  |
| method | string |  | get |  |  |
| payload  | Object |  |  | for post, put, patch |  |
| headers | Object |  |  | deprecated, backward compatibility |  |
| urlParams  | Object |  |  | object for param in url string | /some-api/path/:someid |
| queryParams  | Object |  |  | object, that will be transformed as query params | /some-api?param1=val1&param2=val2 |
| requestParams  | Object |  |  | defines Axios config params |  |
| fallbackErrorMsg   | string |  |  | this msg will be shown if there is an error, instead of a general message |  |
| addAuthToken  | boolean |  | false | if `true` - will add an access token to the request header |  |
| sessionRequired  | boolean |  | true | if `true` - will check for an access token. If there is no token - will dispatch the logout message and stop the request |  |
| successCallback  | function |  |  |  |  |
| errorCallback  | function |  |  |  |  |
| debugThrottling  | number |  |  | use it to test and debug your API request, adds a delay before run request |  |
| sse  | Object |  |  | used to identify if it's an SSE request & also contains all its eventTypeHandlers |  |
