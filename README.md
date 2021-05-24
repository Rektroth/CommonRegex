# CommonRegex
Collection of regular expressions for common requirements.

## Date
The format is `YYYY-MM-DD`. The dashes are required.

* `-` seperators: `^(([02468][1235679]|[13579][01345789])((0[0][-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-9])|(0[469]|1[1])[-]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-9])|(0[469]|1[1])[-]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))$`
* `/` seperators: `^(([02468][1235679]|[13579][01345789])((0[0][/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-8])|(0[469]|1[1])[/]([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-9])|(0[469]|1[1])[/]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-8])|(0[469]|1[1])[/]([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-9])|(0[469]|1[1])[/]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-8])|(0[469]|1[1])[/]([012][0-9]|3[0])))$`
* `-` or `/` seperators: `^[(([02468][1235679]|[13579][01345789])((0[0][-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-9])|(0[469]|1[1])[-]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-9])|(0[469]|1[1])[-]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))(([02468][1235679]|[13579][01345789])((0[0][/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-8])|(0[469]|1[1])[/]([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-9])|(0[469]|1[1])[/]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-8])|(0[469]|1[1])[/]([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-9])|(0[469]|1[1])[/]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[/]((0[13578]|1[02])[/]([012][0-9]|3[01])|(0[2])[/]([01][0-9]|2[0-8])|(0[469]|1[1])[/]([012][0-9]|3[0])))]$`
* no seperators: `^(([02468][1235679]|[13579][01345789])((0[0]((0[13578]|1[02])([012][0-9]|3[01])|(0[2])([01][0-9]|2[0-8])|(0[469]|1[1])([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])((0[13578]|1[02])([012][0-9]|3[01])|(0[2])([01][0-9]|2[0-9])|(0[469]|1[1])([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])((0[13578]|1[02])([012][0-9]|3[01])|(0[2])([01][0-9]|2[0-8])|(0[469]|1[1])([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])((0[13578]|1[02])([012][0-9]|3[01])|(0[2])([01][0-9]|2[0-9])|(0[469]|1[1])([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])((0[13578]|1[02])([012][0-9]|3[01])|(0[2])([01][0-9]|2[0-8])|(0[469]|1[1])([012][0-9]|3[0])))$`

## Time
Hour figure must be 2 digits; no `AM` or `PM`.

Required Figures | Optional Figures | No Seperators | Optional Seperators | Required Seperators
---------------- | ---------------- | --------- | --------------- | ---------------
Hours, Minutes |  | `^([01][0-9]\|2[0-3])[0-5][0-9]$` | `^([01][0-9]\|2[0-3])[:]?[0-5][0-9]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]$`
Hours, Minutes | Seconds | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9])?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9])?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9])?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9])?$`
Hours, Minutes | Seconds, 1 millisecond | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]{1-2})?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]{1-2})?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9])?)?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9])?)?$`
Hours, Minutes | Seconds, 2 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{2})?)?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{2})?)?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{2})?)?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{2})?)?$`
Hours, Minutes | Seconds, 3 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{3})?)?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{3})?)?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{3})?)?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{3})?)?$`
Hours, Minutes | Seconds, 6 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{6})?)?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{6})?)?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{6})?)?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{6})?)?$`
Hours, Minutes | Seconds, 9 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{9})?)?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{9})?)?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{9})?)?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{9})?)?$`
Hours, Minutes | Seconds, 12 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{12})?)?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9]([0-5][0-9]([0-9]{12})?)?)(([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{12})?)?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9]([:][0-5][0-9]([.][0-9]{12})?)?$`
Hours, Minutes, Seconds | | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9])(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9])]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]$`
Hours, Minutes, Seconds | 1 millisecond | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]{1-2}$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]{1-2})(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9])?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9])?$`
Hours, Minutes, Seconds | 2 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{2})?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{2})?)(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{2})?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{2})?$`
Hours, Minutes, Seconds | 3 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{3})?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{3})?)(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{3})?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{3})?$`
Hours, Minutes, Seconds | 6 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{6})?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{6})?)(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{6})?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{6})?$`
Hours, Minutes, Seconds | 9 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{9})?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{9})?)(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{9})?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{9})?$`
Hours, Minutes, Seconds | 12 milliseconds | `^([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{12})?$` | `^[(([01][0-9]\|2[0-3])[0-5][0-9][0-5][0-9]([0-9]{12})?)(([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{12})?)]$` | `^([01][0-9]\|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{12})?$`

## Phone
The format is `+ISO REG-LOC-NUMB`. The dashes are required. `+ISO` and `REG` are optional.

```
^((([+][1-9][0-9]?[0-9]?)?[ ])?[1-9][0-9]{2}[-])?[1-9][0-9]{2}[-][1-9][0-9]{3}$
```

## Hexidecimal Colors
.. | No Leading `#` | Optional Leading `#` | Required Leading `#`
-- | -------------- | -------------------- | --------------------
**3-digit** | `^[a-f0-9]{3}$` | `^[#]?[a-f0-9]{3}$` | `^[#][a-f0-9]{3}$`
**3/6-digit** | `^[a-f0-9]{3}([a-f0-9]{3})?$` | `^[#]?[a-f0-9]{3}([a-f0-9]{3})?$` | `^[#][a-f0-9]{3}([a-f0-9]{3})?$`
**3/6/8-digit** | `^[a-f0-9]{3}([a-f0-9]{3}([a-f0-9]{2})?)?$` | `^[#]?[a-f0-9]{3}([a-f0-9]{3}([a-f0-9]{2})?)?$` | `^[#][a-f0-9]{3}([a-f0-9]{3}([a-f0-9]{2})?)?$`
**6-digit** | `^[a-f0-9]{6}$` | `^[#]?[a-f0-9]{6}$` | `^[#][a-f0-9]{6}$`
**6/8-digit** | `^[a-f0-9]{6}([a-f0-9]{2})?$` | `^[#]?[a-f0-9]{6}([a-f0-9]{2})?$` | `^[#][a-f0-9]{6}([a-f0-9]{2})?$`
**8-digit** | `^[a-f0-9]{8}$` | `^[#]?[a-f0-9]{8}$` | `^[#][a-f0-9]{8}$`

## Email
```(?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*|"(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21\x23-\x5b\x5d-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])*")@(?:(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?|\[(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?|[a-z0-9-]*[a-z0-9]:(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21-\x5a\x53-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])+)\])```

*Note: This is the official [RFC 5322 specification](https://www.ietf.org/rfc/rfc5322.txt), but it not generally recommended that it be used to validate emails; you should instead design a regular expression for your specific purposes. Less broad regular expressions for emails may be added in the future.*
