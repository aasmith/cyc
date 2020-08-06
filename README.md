cyc
===

Reads bicycle data using Bluetooth.

Using Bluetooth and Geolocation Web APIs, connects to a "Cycling Power"
bike computer. Logs instantaneous power, wheel & crank revs, plus joules.

Currently a work in progress that will only work with devices that
return exactly the above fields.

Supported devices
-----------------

Yamaha e-bikes maybe?

Running locally
---------------

```
ruby -run -ehttpd . -p8000
```

