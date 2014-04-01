shootproof-sdk
==============

DEPRECATED - DO NOT USE THIS ... it was just a placeholder until the ShootProof guys deployed their own.

use ShootProof's SDK instead: https://github.com/ShootProof/php-sdk

This is just a wrapper for the shootproof SDK that is available at http://developer.shootproof.com/code

You will need to add this to your composer.json file.  I don't want to submit this to https://packagist.org/ as I believe the ShootProof guys should do that.
```json
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/jpirkey/shootproof-sdk"
        }
    ]
```

along with actually requiring that SDK:
```json
   "require": {
      "jpirkey/shootproof-sdk" : "dev-master"
   }

```
