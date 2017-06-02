---
layout:     post
title:      Parting ways with my crush.
date:       2017-06-02 12:31:19
summary:    The story of an airport goodbye.
categories: jekyll pixyll
---

From the moment we went into the airport, we dreaded the Airport Goodbye. In just a short while, we’d get our final hug, which would turn into a desperate “oh-please-don’t-go” clinging-together thing.

Then there was that horrible moment where one of us had to stay, and the other walked away. Walk, walk, walk, look back… walk… look back… smile sadly… wave… and disappear from sight.

We’d both feel empty, and suddenly so alone. The place is full of people – but, just at that moment, no one feels as lonely as the person who has just said goodbye to the one they love. People are rushing around and talking, and you can stand there with tears rolling down your face, and no one cares. Or perhaps, even if they do care, they know there’s nothing they could possibly do to help, and it feels like the kindest thing just to walk past.

There was that moment where we’d allow ourselves to imagine that there might be a possibility that the one we love would Suddenly Come Back. Maybe the flight would be cancelled and everyone would return to the departure lounge. Or maybe someone official-looking would suddenly appear and say, “No – you guys are supposed to be TOGETHER, not going to different places! Wait here for a moment – we’re bringing your partner back to stay with you forever.”

But it didn’t happen, and eventually there was nothing to do but give up and go home.


![desk](http://larryandcarla.com/wordpress/wp-content/uploads/2015/02/I-miss-you-already-watermarked.jpg)

### Circa 2017

My mother loved planning family vacations and so aware of the fact that I'd be home from college, in winter, she decided it might not be a bad idea to go to Mahabaleshwar via Pune. I would have opposed the idea if I could, but I couldn't because my mother doesn't appreciate opposition( No mother does).

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
