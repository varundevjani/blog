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

![book](https://images-na.ssl-images-amazon.com/images/I/51SC94A2D6L._SX317_BO1,204,203,200_.jpg)

In hindsight, that probably taught me how to be 'to the point' and well within 'word limits' but left me lacking in verbosity.
Soon after though, I stopped reading that as well when I realised that my T.V. was a better entertainer. So while my friends were exchanging copies of _Agatha Christie_, _Twilight_ and what not, I sat busy watching re-runs of _The Simpsons_. It wasn't until things had gotten beyond repair that I began to introspect.

The first thing that came to mind was,_"Hey! I am pretty decent at studying which too involves reading a lot of text. How, then, am I able to do that?"_
Obviously it's because reading is optional but there's no escaping education. But jokes apart, the more I thought about it, the more I realised how different the two activities were.

* Firstly, the process of studying involves _revision_. So we keep reading the same things over and over before we're evaluated. This leads to a recklessness of sorts when it comes to reading text because you know that even if you miss something important you'll probably catch it on your next pass(and you usually will). Unfortunately, this doesn't apply to novels and as I progress through one, I subconsciously use the same method I do while studying. Naturally, I'm lost after a while.

* Secondly, while studying, _not everything in the text is important_. Back in school, in a lot of subjects, we actually had teachers have us mark the important paragraphs in the text and a quick glance through this highlighted text comprised 'studying'. As I got older I trained myself to spot the 'important stuff' myself. This training made reading novels harder as I was unable to appreciate the interlinking of words or even sentences for that matter, while looking for 'important stuff'. 

So we've know established that my methodology of studying is partly to blame, STEM education itself was making it harder. Since education in Science involves questioning what you're being taught and what you're reading I would often find myself questioning what was happening in novels. I'd question the character's feelings, their decisions, facts, which ultimately left me miserable.

Let me illustrate with a few lines from _The Fault in Our Stars_ (how and why I was reading that book can be left aside for now).

<blockquote>
  <p>
     I am not a mathematician, but I know this. There is an infinite between 0 and 1. There's .1 and .12 and .112 and an infinite collection of others. Of course there is a bigger infinite set of numbers between 0 and 2, or between 0 and a million. Some infinities are bigger than other infinities. A writer we used to like taught us that.
  </p>
  <footer><cite title="Hazel's eulogy to Augustus">Hazel's eulogy to Augustus</cite></footer>
</blockquote>

Now while this whole monologue probably got you teary eyed, all I could think was:
_"Dear Hazel, 
Its true you're no mathematician. Otherwise, you would have known that the set of reals between 0 and 1 is as big as the set of reals between 0 and 2. Take any real between 0 and 2 and divide it by 2. You'd have a corresponding real between 0 and 1. That's a one-one mapping. Cantor himself proved both those infinities to be equal. And while some infinities are larger than others, you chose the wrong example." 

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
