### loading css & js                     
```
var loader = new Script_loader();

loader.load( './css/style.css' );

var id = loader.load( './js/script.js', function(){
       // call function from script.js
});

```

### unloading  
```
       loader.unload( id );
       // or
       loader.unload( url );
```
