---
layout: post
category : memo
tags : [ubuntu linux]
---

{% include JB/setup %}

1. install package
{% highlight bash %}
sudo add-apt-repository ppa:fingerprint/fingerprint-gui
sudo apt-get update
sudo apt-get install fingerprint-gui policykit-1-fingerprint-gui libbsapi
{% endhighlight %}

2. enable service
{% highlight bash %}
    sudo pam-auth-update  # enable all options
{% endhighlight %}

