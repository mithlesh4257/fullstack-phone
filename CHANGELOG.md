# Changelog

# 0.1.0

* API:
    * Refactored into server & client modules for easy inclusion
    * Made handler instantiable instead of a singleton
    * Changed `loadMeta` to return full metadata when called with no arguments
    * Switched parameter order of `getExampleNumberForType` to match other APIs (`regionCode` last)
    * Changed `PHONE_INVALID_FOR_COUNTRY` error message to `PHONE_INVALID_FOR_REGION` (more accurate)
* Metadata:
    * Updated to libphonenumber v8.5.1

## 0.0.1 (Unpublished)

* Initial version that requires copying generated files and modifying paths