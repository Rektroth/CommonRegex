# CommonRegex
Some regular expressions for common needs.

## Date
The format is `YYYY-MM-DD`. The dashes are required.

```
^(([02468][1235679]|[13579][01345789])((0[0][-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-9])|(0[469]|1[1])[-]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-9])|(0[469]|1[1])[-]([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])[-]((0[13578]|1[02])[-]([012][0-9]|3[01])|(0[2])[-]([01][0-9]|2[0-8])|(0[469]|1[1])[-]([012][0-9]|3[0])))$
```

## Time
The format is `HH:MM:SS.mmmm`. The semicolons are required. The milliseconds are optional.

```
^([01][0-9]|2[0-3])[:][0-5][0-9][:][0-5][0-9]([.][0-9]{4})?$

```

## Phone
The format is `+ISO REG-LOC-NUMB`. The dashes are required. `+ISO` and `REG` are optional.

```
^((([+][1-9][0-9]?[0-9]?)?[ ])?[1-9][0-9]{2}[-])?[1-9][0-9]{2}[-][1-9][0-9]{3}$
```

## Hexidecimal Colors

* No leading `#` without opacity: `^[a-f0-9]{6}$`
* Optional leading `#` without opacity: `^#?[a-f0-9]{6}$`
* Required leading `#` without opacity: `^#[a-f0-9]{6}$`
* No leading `#` with optional opacity: `^[a-f0-9]{6}([a-f0-9]{2})?$`
* Optional leading `#` with optional opacity: `^#?[a-f0-9]{6}([a-f0-9]{2})?$`
* Required leading `#` with optional opacity: `^#[a-f0-9]{6}([a-f0-9]{2})?$`
* No leading `#` with opacity: `^[a-f0-9]{8}$`
* Optional leading `#` with opacity: `^#?[a-f0-9]{8}$`
* Required leading `#` with opacity: `^#[a-f0-9]{8}$`
