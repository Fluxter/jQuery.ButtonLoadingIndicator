# jQuery ButtonloadingIndicator

A simple script that changes the button icon to the fontawesome Spinner and reverts it when done

## How to install

1. Download the script
1. Import the script via

   ```html
   <script src="jquery.buttonloader.js"></script>
   ```

1. Use it

## How to use

Start loading

```js
$("a").on("click", function(ev) {
  ev.preventDefault();
  $(this).startLoading();
  // Do work
  $(this).stopLoading();
});
```
