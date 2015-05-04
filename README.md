# animated.js

It is a jQuery plugin, wrapper for animated.css and waypoints.js, animate trigger by scroll event.

## Install

You can get the source from github, or install it by bower.

### Download source

    git clone https://github.com/yufeiminds/animated.js

### Bower

    bower install animated.js

## Usage

### Default settings

```javascript
    {
        'animate_getter': function(e) { return e.data('animated'); },
    }
```

### Init

```javascript
    $(document).ready( function() {
        $('[data-animated]').animated({
            /* Your custom settings */
        });
    });
```

## Contribute

1. Fork this repo.
2. Modify it.
3. Create a pull request.

happy coding...!

## Contact

**Email**

yufeiminds@gmail.com
