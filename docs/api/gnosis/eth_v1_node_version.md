---
meta:
  - name: description
    content: eth/v1/node/version Beacon Chain REST API call details and examples.
  - name: keywords
    content: curl rest api beacon chain lighthouse gnosis
---

# eth/v1/node/version

Gnosis consensus layer Beacon Chain API call that returns the version of the consensus layer node.

**Parameters:**

* `none`

**Returns:**

* `data` — `object` with:
  * `version`

**Example:**

``` sh
curl -X GET https://beacon-nd-123-456-789.p2pify.com/3c6e0b8a9c15224a8228b9a98ca1531d/eth/v1/node/version
```
