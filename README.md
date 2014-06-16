# CIF Software Development Kit for Javascript

The CIF Software Development Kit (SDK) for Javascript contains library code and examples designed to enable developers to build applications using CIF.

# Installation

# Examples
## Client
```javascript
<script type="text/javascript" src="cif.sdk.js"></script>

<script type="text/javascript" charset="utf-8">

    var cli = new cif.sdk.Client({token: "1234"});
    cli.ping(function(err, success) {
        if (err) {
            throw err;
        }

        console.log("ping was successful: " + success);
    });

</script>
```
## Search
## Ping
## Submit

# License and Copyright
Copyright (C) 2014 the CSIRT Gadgets Foundation

Free use of this software is granted under the terms of the GNU Lesser General Public License (LGPL v3.0). For details see the file LICENSE included with the distribution.