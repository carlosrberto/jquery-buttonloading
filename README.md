# jQuery buttonloading

jQuery plugin to add image loader in buttons


## Use case

When submiting a form disables the submit button and add a loader.

## Usage

```javascript
$(function(){
    $('.button').buttonloading({
        imageLoader: 'loader.gif'
    });

    // enable
    $('.button').buttonloading('enable');

    // disable
    $('.button').buttonloading('disable');
});
```
