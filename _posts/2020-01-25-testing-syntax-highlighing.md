---
layout: post
title: "Testing Syntax Highlighing"
description: ""
category: 
tags: []
---

Let's see if syntax highlighing works...here's some example Ruby code:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

And some Powershell as well...


{% highlight powershell %}
Get-PrinterDriver | Select-Object Name, MajorVersion, DriverVersion

Name                   MajorVersion    DriverVersion
----                   ------------    -------------
Microsoft XPS Docu...             4 2814750890000385
Samsung Universal ...             3  844424930656256

{% endhighlight %}

{% include JB/setup %}
