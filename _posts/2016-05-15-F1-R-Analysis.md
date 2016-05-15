---
layout: post
title: F1 R Analysis
subtitle: Fooling aroung with twitter and R
bigimg: /img/bcn.JPG
---

The wordcloud for the SpanishGP:
... you can [SpanishGP]({Spanishgp.pdf)

How about a yummy crepe?

![Crepe](http://lafenicegelato.com/wp-content/uploads/2014/09/crepes-with-chocolate.jpg)

Here's a code chunk:

~~~
x <- 5 + 10
print(x)
~~~

And here is some code with syntax highlighting

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

{% highlight sql %}
update MeasVisualizations
Set SeriesColor ='03A9F4', SeriesColorFromTheme= 0
where MeasurementId in (SELECT mm.MeasurementId
  FROM [EMEA_16].[dbo] .[MeasVisualizations] mv inner join MeasMetadata mm on mv.MeasurementId =mm. MeasurementId where ChartId= 5598 and Dimension1 like '%F4a')
{% endhighlight %}
