# M2composerexample
Magento 2 Composer Module Example

Add `"andy-myers-space48/M2composerexample": "0.0.2"` to the require section of the composer.json file.


In the project composer.json file add the repo:

```javascript
"repositories": [
        {
            "type": "composer",
            "url": "https://repo.magento.com/"
        },
        {   "type": "vcs", 
            "url": "https://github.com/andy-myers-space48/M2composerexample" 
        }
```

Run `composer install` from the project root.
