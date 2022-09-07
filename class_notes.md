# Class 1: Introduction

From my introductory email:

    This will also be about the process of exploring art through
    programming, and about reconnecting with joy of programming through
    art.  I'm hoping to work with students who are struggling to enjoy
    programming (but would like to enjoy it more) - i.e. if you love
    programming and spend all your free time programming already, this is
    not the course for you.  This is a forum where we will be talking
    frankly about burnout, doubt, etc.  I am by no means an expert in
    these things, but if you'd like to talk seriously and also build
    silly programs that make pictures perhaps this course is for you.
    
## What drew me to teach this class?

### Losing that special feeling

* Since I was a teenager I've always enjoyed programming.  Frequently
  it's been my job in various capacities but it was never something I
  felt it was *work*.

* During COVID times I had a lot of stress.  Prolonged anxiety
  probably put me in the worst state, mental health-wise, I've ever
  been.  During this time, I didn't have a lot of opportunity to write
  code either professionally or recreationally.
  
* Even when my health got better, my joy at programming didn't really
  come back the way it was before.
  
* It's OK to not program, it's OK to just program for you job, it's OK
  that things change as you get older.  But this made me a feel sad.
  
So for the past year or so I've been trying to rekindle my joy at
programming - and I think I've been a little successful.

### Wanting to share

I am by no means an expert at either art or psychology.  But I knew that:

* Students at Rose in Computer Science feel a lot of anxiety about
  programming and if they "belong".  We as a community don't really
  acknowledge the feelings about it openly.  So maybe a class to talk
  about things could help.
  
* There's an unquestioned assumption that if you were really *good* at
  programming, you wouldn't have negative feelings about it.  I felt
  like by being frank with you, I could help counteract some of the
  stigma.
  
* Computational art is this cool thing that doesn't get enough
  exposure

## Books

This course has two optional textbooks:

* The Artist's Way by Julia Cameron

  https://smile.amazon.com/Artists-Way-25th-Anniversary-ebook .
  
  There's stuff in here I don't like, and stuff I like.  But I like
  that it has a very uncompromising faith in the reader and that it's
  not afraid to sound silly.

* Generative Design by Benedikt Gross et. al

  https://smile.amazon.com/Generative-Design-Visualize-Program-JavaScript-ebook
  
  The code for this book is available on the web
  here : https://editor.p5js.org/generative-design/sketches.
  
I'd encourage you to get both, and read them as you desire.  I will be
selecting sections to motivate my lectures and you can "get by"
without either.  But if you want to explore something, does it really
make sense to be cheap about it?

## Technology

I'm going to allow you the freedom to use any programming technology
to do your art.  But my examples will probably all be in p5.js.

This is a javascript adaptation of the language Processing - basically
a simple language for interactive programs that can get surprising
deep.

The environment works on the web and it's available here:

https://editor.p5js.org/

Just be sure to sign up so you can save your stuff.

## Assignments

There is one required type of assignment for this class and that is
weekly "sketches" or graphical programs based on prompts I write.

I'll give you some potential starting points in p5.js.  You can spend
20 minutes tweaking one of those and submit it, or you can built a
whole new thing in a language or technology of your choice.

You'll submit source code and an active link, still picture, or video
of your creation.

## Colors

I am neither an artist nor a physicist.

Our perception of colors is a little odd, and in terms of computers
one of the tricky things is our relationship to RGB.  My take is the
RGB doesn't really match our visual intuition about colors which is
something like:

A color is a particular kind of thing, which can be varied from
totally dark (black) to totally light (white) and in the middle takes
on its purest form.

In RGB we don't represent this directly, and I think it makes it hard
to pick colors.

Let's instead consider HSL

Now hue represents pure color.
Lightness represents that light dark continuum.

Look here

https://colorizer.org/

If we max out saturation, we set one color to max and one to min, and then vary the 3rd.

If we adjust lightness, we'll move any non maxed up or the all of them down.

If we adjust saturation to something other than the max though, we
introduce the idea of "muddy" colors that can be equally "bright" but
not as "pure".
