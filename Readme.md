### Install serve or a local server
`npm i -g serve`

### Serve contents of the current directory.
`serve .`

### Open the ad-wrapper.html file
`http://localhost:3000/index-wrapper`

### In order to listen to a different domain.
`serve -l tcp://domain.com:3000 .`


Open the random-ad file. Open the dev tools and inspect memory. When the page is refreshed, Javascript VM memory is reset.


Open the ad-wrapper. Open the dev tools and inspect memory. Every time the page gets refreshed VM memory does not go down. The number of DOM nodes increase too.