# DateTimeRegex
Some regular expressions for dates and times.

## Date
The format is `YYYY-MM-DD`. The dashes are required.

```
^(([02468][1235679]|[13579][01345789])((0[0]\-((0[13578]|1[02])\-([012][0-9]|3[01])|(0[2])\-([01][0-9]|2[0-8])|(0[469]|1[1])\-([012][0-9]|3[0])))|((0[48]|[2468][048]|[13579][26])\-((0[13578]|1[02])\-([012][0-9]|3[01])|(0[2])\-([01][0-9]|2[0-9])|(0[469]|1[1])\-([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])\-((0[13578]|1[02])\-([012][0-9]|3[01])|(0[2])\-([01][0-9]|2[0-8])|(0[469]|1[1])\-([012][0-9]|3[0])))))|([02468][048]|[13579][26])(([02468][048]|[13579][26])\-((0[13578]|1[02])\-([012][0-9]|3[01])|(0[2])\-([01][0-9]|2[0-9])|(0[469]|1[1])\-([012][0-9]|3[0]))|([02468][1235679]|[13579][01345789])\-((0[13578]|1[02])\-([012][0-9]|3[01])|(0[2])\-([01][0-9]|2[0-8])|(0[469]|1[1])\-([012][0-9]|3[0])))$
```

## Time
The format is `HH:MM:SS.mmmmmm`. The semicolons are required. The milliseconds are optional.

```
^([01][0-9]|2[0-3])\:[0-5][0-9]\:[0-5][0-9](\.[0-9]{6})?$

```
