# new-hotspot-01

## config
edit file conf.js

- setCase: sets the input case to uppercase, lowercase, or none.
- defaultMode: sets the main login page mode, either voucher or member (username & password).

```javascript
var config = {

    loginvc : "Enter the Voucher Code then click Connect.",
    loginup : "Enter Username and Password <br> then click Connect.",
    voucherCode : "Voucher Code",
    setCase : "none", // lowercase, uppercase or none
    defaultMode : "voucher", // voucher or member
    theme : "default", // default, dark, lite

    // server information
    url : "https://demo.mikhmon.online", // Mikhmon server URL
    SessionName : "demo", 

}
```
