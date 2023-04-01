---
layout: post
title:  "Code displays"
---
Jekyll uses Rouge by default for syntax highlighting, here are some tests.

I have some text.

I want some _italics_.

I want some **bold**.

# this is heading 1

## this is heading 2

### this is heading 3

you want a list?
* first
* second
* third

you want an ordered list?
1. whatever
1. whatever
1. whatever

Ruby:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Python with line numbers:
{% highlight python linenos %}
def print_hi(name):
    print("Hi, {}".format(name))

print_hi('Tom')
# prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

C with line numbers:
{% highlight c linenos %}
void print_hi(string name) {
  printf("Hi, %s", name);
}
print_hi("Tom");
/* prints 'Hi, Tom' to STDOUT. */
{% endhighlight %}