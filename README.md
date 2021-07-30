# xenialbase db

an open source database creator built using node


# How to install

```sh
$ npm i xenialdb
```

# Example usage

```javascript
var xenialdb = require('xenialdb')
var db = new xenialdb('data.json')
db.ready = function(){
  db.value.c= "turtle is the best"
  db.value.d="hello"
  db.value.message="unknown"
	db.write(function(){
		console.log("Data stored!")
    console.log(db.value);
	})
	
}

```
