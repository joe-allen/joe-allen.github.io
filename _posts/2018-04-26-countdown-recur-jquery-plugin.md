---
layout: post
title:  "Countdown Recur - A jQuery Plugin!"
date:   2018-04-26 12:27:19
categories: [code, javascript, jQuery]
comments: true
---
This plugin will allow you to set the `start date`, `end time`, and `number of weeks` (along with a few other settings) for a countdown timer. Good to use if you need a weekly recurring timer that ends at a certain time, but picks up the next day.


<!--more-->

THINGS TO REMEMBER:

{% highlight javascript %}
// Madatory settings:
	startDate: '04/25/2018',              // Set today's date (!important - must set otherwise countdown will not end)
	weeksToRecur: 1                       // Set number of weeks countdown should recur, defaults to 4 weeks

// Optional settings:
	debug: false,                         // This stops the time in order to update the css
	textColor: 'green',                   // Color of timer text, defaults to green
	endDay: 'Sunday',                     // End day for timer, defaults to "Sunday"
	endTime: '11:59:00 am',               // End time for timer, defaults to "11:59:59 pm", Format like '05:05:20 pm'
	deadlineText: "Sorry, time's up!",    // Text to show user after timer ends
{% endhighlight %}

Check out the [Countdown Recur Timer][action] in action.
[Countdown Recur Timer repository][gh].

[action]:       https://joe-allen.github.io/projects/countdown-recur/
[gh]:   				https://github.com/joe-allen/joe-allen.github.io
