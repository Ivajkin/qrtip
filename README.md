# qrtip
LZM compression of data for creating readable QR

[![Build Status](https://travis-ci.org/apiaryio/qrtip.png)](https://travis-ci.org/apiaryio/qrtip)
[![Dependency Status](https://david-dm.org/apiaryio/qrtip.png)](https://david-dm.org/apiaryio/qrtip)
[![devDependency Status](https://david-dm.org/apiaryio/qrtip/dev-status.png)](https://david-dm.org/apiaryio/qrtip#info=devDependencies)

Converts linear growth of URLs to logarithmic growth.

## Scripts

- `decode.min.js` - untip function for QR reading, tip function for QR compression

## Example usage 

```javascript
var encodedQR = tip(data);
var code = untip(encodedQR);
```

## API Reference

`untip(encodedQR)` - decode a text from encoded QR

`tip(data)` - encode a text to encoded QR

- - - 

NOTE: contact t.s.ivaykin@gmail.com for inquiries, abzalov.m@samberi.com for code usage examples.
