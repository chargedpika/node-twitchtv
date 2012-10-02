
# node-twitchtv

  TwitchTV client for Node applications.
  
  
## Getting started

- Sign up for an application (need a client_id) at TwitchTV: http://www.twitch.tv/settings?section=applications
- 

```javascript

var account = require("../secrets/user.json");

var client = new TwitchClient(account).auth();
  
client.games({ limit: 20, offset: 21}, function(err, games) {
  console.log(games);
});
```

## Retrieving a list of games


## Retrieving a list of channels

## Retrieving a list of users



## License 

(The MIT License)

Copyright (c) 2012 Jaime Bueza &lt;jbueza@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.