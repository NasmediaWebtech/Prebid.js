# Overview

```
Module Name: NasmediaAdmixer Bidder Adapter
Module Type: Bidder Adapter
Maintainer: prebid@nasmedia.co.kr
```

# Description

Module that connects to NasmediaAdmixer demand sources. 
Banner formats are supported.
The NasmediaAdmixer adapter doesn't support multiple sizes per ad-unit and will use the first one if multiple sizes are defined.


# Test Parameters
```
    var adUnits = [
      {
        code: 'banner-ad-div',
        sizes: [[300, 250]],  // banner size
        bids: [
          {
            bidder: 'nasmediaAdmixer',
            'params': {
              'media_key': '19038695',
              'adunit_id': '24190632',
            }
          }
        ]
      }
    ];
```
