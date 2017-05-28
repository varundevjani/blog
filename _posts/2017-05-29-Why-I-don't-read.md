---
layout:     post
title:      Why I can't read novels.
date:       2017-05-29 12:31:19
summary:    and how it got worse as I grew up.
categories: realisation
---

I have never been an avid reader. My parents made several attempts to inculcate the habit 
but failed miserably every time. Back when I was in the third standard a few of my friends decided to become
members at a library nearby so I did too. And while they made their way through a fair share of books, I found it 
hard to get past books with more than a hundred pages or so. But the collection of books was fairly large and I found a few books that catered to this limitation of mine. The library was divided into different sections having books 
catering to readers of different maturity. While my friends progressed onto the _Young Adults_ section, I found it hard to let 
go of the _Nancy Drew Notebooks_[^1], I had grown fond of. Every book in that series was under 150 pages(my personal favourite being _Recipe for Trouble_). 

_![book](https://images-na.ssl-images-amazon.com/images/I/51SC94A2D6L._SX317_BO1,204,203,200_.jpg)_

In hindsight, that probably taught me how to be 'to the point' and well within 'word limits' but left me lacking in verbosity.
Soon after though, I stopped reading that as well when I realised that my T.V. was a better entertainer. So while my friends were exchanging copies of _Agatha Christie_, _Twilight_ and what not, I sat busy watching re-runs of _The Simpsons_. It wasn't until things had gotten beyond repair that I began to introspect.

The first thing that came to mind was,_"Hey! I am pretty decent at studying which too involves reading a lot of text. How, then, am I able to do that?"_
Obviously it's because reading is optional but there's no escaping education. But jokes apart, the more I thought about it, the more I realised how different the two activities were.

* Firstly, the process of studying involves _revision_. So we keep reading the same things over and over before we're evaluated. This leads to a recklessness of some sorts when it comes to reading texts because you know that even if you miss something important you'll probably catch it on your next pass(and you usually wiil). Unfortunately, this doesn't apply to novels and as I progress through one, I subconsciously use the same method as I do while studying. Naturally, I'm lost after a while.
* Secondly, 
* Potatoes
* Milk

All links are easy to [locate and discern](#), yet don't detract from the [harmony
of a paragraph](#). The _same_ goes for italics and __bold__ elements. Even the the strikeout
works if <del>for some reason you need to update your post</del>. For consistency's sake,
<ins>The same goes for insertions</ins>, of course.

### Code, with syntax highlighting

Here's an example of some ruby code with line anchors.

{% highlight ruby lineanchors %}
# The most awesome of classes
class Awesome < ActiveRecord::Base
  include EvenMoreAwesome

  validates_presence_of :something
  validates :email, email_format: true

  def initialize(email, name = nil)
    self.email = email
    self.name = name
    self.favorite_number = 12
    puts 'created awesomeness'
  end

  def email_format
    email =~ /\S+@\S+\.\S+/
  end
end
{% endhighlight %}

Here's some CSS:

{% highlight css %}
.foobar {
  /* Named colors rule */
  color: tomato;
}
{% endhighlight %}

Here's some JavaScript:

{% highlight js %}
var isPresent = require('is-present')

module.exports = function doStuff(things) {
  if (isPresent(things)) {
    doOtherStuff(things)
  }
}
{% endhighlight %}

Here's some HTML:

{% highlight html %}
<div class="m0 p0 bg-blue white">
  <h3 class="h1">Hello, world!</h3>
</div>
{% endhighlight %}

# Headings!

They're responsive, and well-proportioned (in `padding`, `line-height`, `margin`, and `font-size`).
They also heavily rely on the awesome utility, [BASSCSS](http://www.basscss.com/).

##### They draw the perfect amount of attention

This allows your content to have the proper informational and contextual hierarchy. Yay.

### There are lists, too

  * Apples
  * Oranges
  * Potatoes
  * Milk

  1. Mow the lawn
  2. Feed the dog
  3. Dance

### Images look great, too

![desk](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)

_![desk](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)_


### There are also pretty colors

Also the result of [BASSCSS](http://www.basscss.com/), you can <span class="bg-dark-gray white">highlight</span> certain components
of a <span class="red">post</span> <span class="mid-gray">with</span> <span class="green">CSS</span> <span class="orange">classes</span>.

I don't recommend using blue, though. It looks like a <span class="blue">link</span>.

### Footnotes!

Markdown footnotes are supported, and they look great! Simply put e.g. `[^1]` where you want the footnote to appear,[^1] and then add
the reference at the end of your markdown.

### Stylish blockquotes included

You can use the markdown quote syntax, `>` for simple quotes.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse quis porta mauris.

However, you need to inject html if you'd like a citation footer. I will be working on a way to
hopefully sidestep this inconvenience.

<blockquote>
  <p>
    Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.
  </p>
  <footer><cite title="Antoine de Saint-Exupéry">Antoine de Saint-Exupéry</cite></footer>
</blockquote>

### There's more being added all the time

Checkout the [Github repository](https://github.com/johnotander/pixyll) to request,
or add, features.

Happy writing.

---

[^1]: Important information that may distract from the main text can go in footnotes.
