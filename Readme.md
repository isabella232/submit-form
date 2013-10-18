
# submit-form

  Submit a form programmatically, triggering its submit handlers.

## Installation

    $ component install segmentio/submit-form

## Example

```js
var submit = require('submit-form');
var form = document.querySelector('form');

form.onsubmit = function (e) {
  console.log('submitted!');  
};

submit(form);
// "submitted!"
```

## API

### submit(form)
  
  Submit a `form` programmatically, triggering its submit handlers.
  
## License

  MIT
