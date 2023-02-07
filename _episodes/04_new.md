---
layout: page
title: "R Training: Session 1 - Part 2"
order: 4
session: 1
length: 30
toc: true
---

**Assign a name to your command.**

This action will become very useful. You assign names to objects so that then you can perform operations with these objects, such as plotting.


{% highlight r %}
## 1.2 Create an object using the assign symbol (<-)
a <- 2+2 # Run this command and look at pane 3
{% endhighlight %}

<br>

**Plot your variable 'a'.** 

{% highlight r %}
## 1.3 Let's plot our object
plot(a) # This appears on pane 4
{% endhighlight %}

<img src="/figure/rmarkdown/04_new/unnamed-chunk-2-1.png" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

<br>

## Using built-in data

R has readily available data sets for you to explore, play, analyse, plot... 

Run this command if you want a list of what's available:


{% highlight r %}
data()
{% endhighlight %}

There are a few that are commonly used in R-Training sessions. You will encounter these frequently:

- mtcars
- USArrests
- iris

<br>

**Iris data set**

This data set holds information about 50 flowers of 3 species of iris. 

{% highlight text %}
## Error in knitr::include_graphics(c("images/iris.png")): Cannot find the file(s): "images/iris.png"
{% endhighlight %}

<br>
If you want to know more about this data set. 


{% highlight r %}
?iris # Look at pane 4
{% endhighlight %}

