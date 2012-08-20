---
layout: post
title: "cheche: javascript"
category: 
tags: [javascript]
---
{% include JB/setup %}


# JavaScript Functions: 

1. Declarative function

{% highlight javascript %}
// syntax
function functionname (param1, param2, ..., paramn) {
    function statements
}

// example
function sayHi(toWhom) {
   alert("Hi " + toWhom);
}
{% endhighlight %}

2. Anonymous function

{% highlight javascript %}
// syntax
var variable = new Function ("param1", "param2", ... , "paramn", "function body");

// example
var func = new Function("x", "y", "return x * y");
{% endhighlight %}


3. Function literal / function expression
{% highlight javascript %}
// syntax
var func = function (params) {
  statements;
}

// example
var func = function (x, y) {
   return x * y;
}
alert(func(3,3));
{% endhighlight %}
