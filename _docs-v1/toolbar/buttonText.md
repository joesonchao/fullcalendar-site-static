---
title: buttonText
since_version: 1.3
---

Text that will be displayed on buttons of the header.

<div class='spec' markdown='1'>
Object, *default*:

```
{
  prev:     '&lsaquo;', // <
  next:     '&rsaquo;', // >
  prevYear: '&laquo;',  // <<
  nextYear: '&raquo;',  // >>
  today:    'today',
  month:    'month',
  week:     'week',
  day:      'day'
}
```
</div>

If you wanted to change the prev/next buttons to use &lt; and &gt; characters, here is what you would do:

```js
$('#calendar').fullCalendar({
  buttonText: {
    prev: '&lt;',
    next: '&gt;'
  }
});
```
