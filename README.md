# Bootstrap DatePicker Highlighter
This is a small repository to highlight the date on mouse hover and according to specific algorithm.



data-highlight
---------

Date or String.  Default: $.noop

A data attribute on element will get a string or date and Highlight the dates on hover, active and focused. Possible values for highlight:

* ``1w``: **Weekly** - This would always highlight the week.
* ``date eg:2015-11-15``: **Bi-Weekly** - This would be able to calculate the pay period start/end date and highlight accordingly. Format of date should be: ``yyyy-mm-dd``
* ``1/2m``: **Twice a month** - This would always highlight the 1st through 15th or the 16th through the end of the month.
* ``1m``: **Monthly** - This would highlight the entire month


Sample to use highlighter in HTML.

```html
    <input type="text" data-highlight="1w">
```
