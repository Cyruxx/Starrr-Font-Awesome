### STARRR Rating plugin ###
It's the jQuery starrr rating plugin with font awesome support.


#### Usage

##### Create the stars
```
<div class='starrr'></div>
```

##### With an existing rating
```
<div class='starrr' data-rating='4'></div>
```

##### Listen for events
```
$('.starrr').on('starrr:change', function(e, value){
  alert('new rating is ' + value);
});
```
