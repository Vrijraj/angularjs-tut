# AngularJS Expressions
AngularJS expressions can be written inside double braces: `{{ expression }}`.

AngularJS expressions can also be written inside a directive:  `ng-bind="expression"`.

AngularJS will resolve the expression, and return the result exactly where the expression is written.

AngularJS expressions are much like JavaScript expressions: They can contain literals, operators, and variables.

Example {{ 5 + 5 }} or {{ firstName + " " + lastName }}

* If you remove the ng-app directive, HTML will display the expression as it is, without solving it

# AngularJS Numbers
AngularJS numbers are like JavaScript numbers:
`{{ 5+5 }}`
Example:

```js
<div ng-app="" ng-init="quantity=1;cost=5">

<p>Total in dollar: {{ quantity * cost }}</p>

</div>
```