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

# How to signup

https://forms.gle/Q4L6SaLvWaF8r9it8

# Class 2: Daily Pages & Shapes & Transforms

## Checkin with students

Names, share your first assignment if you want, and how the coding felt.

## Daily pages

  "I am up and have a headache and have taken asprin and feel a little
  better although still shaky.  I may have the ful after all.  I am
  getting to the bottom of a lot of unpacking and still no teapot from
  Laura whom I am sorely missing.  What a heartbreak..."

*3 daily pages of handwritten writing, written stream of consciousness*

Key notes:

* There is no "topic" for the daily pages

* They are not meant to be art, or even writing

* Nothing is too silly to be written

* They can be what you don't think you should allow yourself to be
  (e.g. self-pitying, mean to others, etc.)
    
* Never skip them (especially not based on your mood)

* Do not share your daily pages.  Usually do not read your daily pages.

* "An inner source of wisdom"?

### Self honesty

I think they represent an opportunity to honestly think with yourself.
I think oftentimes we restrict ourselves from total thought (with good
reason, sometimes) but I think that it is important to explore our
total thoughts.

When I am debugging seriously, I have a mantra - "first understand the
problem".  Not allowing doubt, not allowing "solutions".

I think this kind of forced thought becomes habitual - and when
habitual it doesn't serve us.

## Shapes & Grids

https://editor.p5js.org/generative-design/sketches/H1Klcc5ay4

https://editor.p5js.org/generative-design/sketches/HJ3gqcq6kN

https://editor.p5js.org/generative-design/sketches/ryklecq9Ty4

https://editor.p5js.org/generative-design/sketches/B1egg99cTy4

https://editor.p5js.org/generative-design/sketches/SkMel5qcakE

https://editor.p5js.org/generative-design/sketches/S1Qelc5qaJE

Hint: there are always many more variations that I don't show you!

## Transforms

https://editor.p5js.org/generative-design/sketches/ByDlgcq9a1V

    function drawRect() {
      rect(-10, -5, 20, 10);
    }

    function draw() {
      background(220);
      translate(375, 20);
      for(i = 0; i < 300; i++) {
        drawRect();
        translate(0,15);
        //rotate(.1);
        //scale(.98);
      }
      
      
    }

# Class 3: Mazes and Artist Date


## Artists Date

An artist date is a block of time, perhaps 2 hours weekly especially
set aside to nurture your creative consciousness.

* A great junk store

* A solo trip to the beach

* Watch an old movie


Is this something that makes sense for programmers?

## Mazes

So I want to talk about mazes!  They're a fun programming problem.

I'm going to talk about 2 algorithms for perfect unbiased mazes:

    * perfect: no cycles, single path between any pair of nodes
    
    * unbiased: any maze is equally likely
    
### Aldous-Broder Algorithm

1. Start somewhere, mark it as visited

2. Move to a random neighboring square

3. If this square hasn't been visited square, "carve the passage" into
   the maze
   
4. Go to 2

Use the moodle PDF for some diagrams

Here's my implementation:

https://editor.p5js.org/hewner/sketches/H0gVqsSFH

### Wilson's Algorithm

1.  Mark a random square as visited

2.  Go to another random square which is unvisited

3.  Make a tentative random walk

4.  If in the process of this walk you visit a square twice, remove
    the loop
    
5.  Once you reach a visited square, carve that path into the map and
    mark the whole path as visited

6.  Go to 2
