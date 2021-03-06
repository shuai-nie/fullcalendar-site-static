---
title: header
since_version: 1.3
---

Defines the buttons and title at the top of the calendar.

<div class='spec' markdown='1'>
Object/`false`, *default:*

```js
{
  left:   'title',
  center: '',
  right:  'today prev,next'
}
```
</div>

Setting the header options to `false` will display no header. An object can be supplied with properties `left`, `center`, and `right`. These properties contain strings with comma/space separated values. Values separated by a comma will be displayed adjacently. Values separated by a space will be displayed with a small gap in between. Strings can contain any of the following values:

`title`
:   text containing the current month/week/day

`prev`
:   button for moving the calendar back one month/week/day

`next`
:   button for moving the calendar forward one month/week/day

`prevYear`
:   button for moving the calendar back on year

`nextYear`
:   button for moving the calendar forward one year

`today`
:   button for moving the calendar to the current month/week/day

*a view name*
:   button that will switch the calendar to any of the available views


Specifying an empty string for a property will cause it display no text/buttons.
