
User attributes are Key-Value objects stored in the form of a `HashMap<String,Object>`.

Data types of these attributes can be: `Integer`, `String`, `Float`, `Boolean`, `Date` and `null`.

An example that includes all this attributes could be:

{% highlight java %}
HashMap<String,Object> attrs = new HashMap<String,Object>();
attrs.put("age", 30);
attrs.put("name", "John");
attrs.put("frequence", 1.3);
attrs.put("facebook_account", true);
attrs.put("last_activity", new Date());
attrs.put("social_profile", null);
{% endhighlight %}

{% include alert.md type='info' message="You should not store nothing more than user information on this collection, i.e. do not store information related with the device (like model or carrier). This information is stored on the device entity, as explained below." %}
