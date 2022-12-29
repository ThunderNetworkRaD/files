# files
- ### Create a directory
Async
```js
require('@thundernetworkrad/files').mkdir('./example')
```
It will create a directory called example
- ### Delete a directory
Async
```js
require('@thundernetworkrad/files').rmdir('./example')
```
It will delete a directory called example
- ### Map a directory
Async
```js
require('@thundernetworkrad/files').map('./example/*/*.js')
```
It return a list with the full path of all the file that ends with .js in a subfolder of ./example
