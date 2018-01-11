
# Haskell Learning Resources and References

This list, organized roughly by topic or theme, contains resources **I**
have found to be most useful during my journey as a student of
Haskell. It's not meant to be comprehensive, and I may have
deliberately left some resources off of this list--there is more out
there than I'm going to include here. But I consider these learning
resources and references to be either the best out there, or otherwise
foundational and important. (For example, I think the Haskell wiki
sucks in a lot of ways, but there is enough important stuff on there
that I would be remiss if I didn't include it in this list.)


## Online Tutorials, Books, and Online Courses

This section contains resources that are meant to be gone through in a
relatively linear fashion. I'll mark which ones I've gone through
completely vs. which I've taken bits and pieces from.

### [Introduction to Functional Programming at edX](https://www.edx.org/course/introduction-functional-programming-delftx-fp101x-0), taught by Erik Meijer

I went through this entire course. This was the course that got me
over the hump, so to speak, in Haskell. At the end of this course I
had a relatively strong grasp of the basic algebraic
structures--functors, monoids, monads, etc.--which are pervasive in
Haskell, I felt pretty comfortable mentally parsing type signatures
and understanding how to do basic stuff in Haskell. I really
appreciate this course because there is an emphasis on
fundamentals--like breaking down how an expression is evaluated in
Haskell via redex analysis, and "following the types" to understand
how to implement, say, a monad instance. Erik Meijer can be
somewhat...eccentric and quite concise in his explanations, but if you
bear with him, participate in forum discussions, and work your way
through all of the exercises, you'll come out of the course with a
solid foundation in Haskell.

### [CIS194 at University of Pennsylvania](http://www.cis.upenn.edu/~cis194/fall16/)
  
I believe this was originally created by [Brent
Yorgey](https://byorgey.wordpress.com/), but it looks like it's
taught by others now. In any case, I have not gone through this
course exhaustively, but pulled out exercises here and there to work
on, and found it to be a great resource. Others who have gone
through it more exhaustively suggest it's a great way for a
self-learner to get a foundation in Haskell.
  
### [Graham Hutton's Programming in Haskell](http://www.cs.nott.ac.uk/~pszgmh/pih.html)

I've only read parts of it when focusing specific topics, but that
being the case, this is the best book I've found to use as a textbook
for learning Haskell on your own. The sneaky way he teaches about
monads via parsing without once using the 'm-word' blew me away the
first time I encountered it (as an excerpt in Erik Meijer's course
listed above, I should mention).

It's also worth checking out [Graham Hutton's
publications](http://www.cs.nott.ac.uk/~pszgmh/#bibliography)--lots of
great stuff on [folds](http://www.cs.nott.ac.uk/~pszgmh/bib.html#fold)
in particular--an amazing resource.

### [Haskell on Wikibooks](https://en.wikibooks.org/wiki/Haskell)

A bit more uneven, but pretty decent in my experience. I've also only
used this for focusing on specific topics but it's well-structured in
that sense: the individual topic sections tend to be cohesive enough
that you can pick and choose what you want based on where you're at in
your learning process. Keep this one in your back pocket for when you
need to focus on stuff like understanding better how the state monad
works, or monoids...etc.

### [LYAH](http://learnyouahaskell.com/) and [Real World Haskell](http://book.realworldhaskell.org/)
  
Two resources, both with flaws, but still useful for beginners. If
you try some of these other sites and don't like them, take a look at
both of these and see if the style works for you. Note that Real
World Haskell is kind of old at this point, so the specific
approaches they take for things like parsing and whatnot may not be
up-to-date with current best practices/libraries, but the foundation
is still very solid.

### [School of Haskell](https://www.schoolofhaskell.com/)

There's overlap here with some of the resources above, but it can be
worth picking through this site especially to find topic-specific
tutorials by pretty prominent members of the Haskell community. Some
of the material here is quite advanced however.

### [Yesod Web Framework](https://www.yesodweb.com/)

I've actually not ever used the Yesod web framework, but I've found
some of the sections of this onlien book incredibly useful for
understanding modern Haskell development practices, especially for
stuff like [advanced Monad Transformer stack design and
usage](https://www.yesodweb.com/book/monad-control). Stuff like this
can really put the more abstract, general documentation in context.


## (Meta-)References

### [What I Wish I Knew When Learning Haskell](http://dev.stephendiehl.com/hask/)

One of my favorite references for Haskell, especially useful as an
"advanced Beginner" or intermediate Haskell programmer. Worth checking
out his section on monads before approaching this topic for some
guidance on how to think about this contentious, overblown topic. Also
see his summaries of various GHC extensions--useful for getting a
basic grasp on the "why" of extensions that you've seen a lot but not
yet used.

### [wiki.haskell.org](https://wiki.haskell.org)

Kind of a mess, but with nuggets of gold throughout. Notable sections
include the
[Typeclassopedia](https://wiki.haskell.org/Typeclassopedia) (by Brent
Yorgey, mentioned above) which goes through some of the most important
algebraic structures used in day-to-day Haskell; the section on
[folds](https://wiki.haskell.org/Fold) (see the links at the bottom
too, especially [Foldr Foldl
Foldl'](https://wiki.haskell.org/Foldr_Foldl_Foldl%27)), 

### [Haskell Hierarchical Libraries](https://downloads.haskell.org/~ghc/latest/docs/html/libraries/index.html)

Library documentation for stuff that is foundational or included by
default in GHC. Probably a good place to start if you're asking
questions like, "what is the Haskell lib for <standard data structure
or set of functions you can expect to see in most programming
languages>, and what module/package is it in?"

### [Glasgow Haskell Compiler User's Guide](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/)

Docs for the compiler you're probably using to compile Haskell. This
is a great resource for libraries, GHCi details, profiling and
debugging, and extensions too, in particular.

### [Stack docs](https://docs.haskellstack.org/en/stable/README/)

Docs for the system that you're probably using to install and create
Haskell projects.

### [Hoogle](http://hoogle.haskell.org/)

Great for looking up functions or type signatures to figure out where
a type signature is coming from, what functions implement it, etc. Not
sure why it says "type search doesn't work," seems like it does...?

### [Hackage](https://hackage.haskell.org/)

You'll probably end up coming here when trying to find the
documentation for a specific Haskell package,
e.g. [mtl](https://hackage.haskell.org/package/mtl) or
[containers](https://hackage.haskell.org/package/containers), for
example.


## Specific Topics

**FILL ME IN!**

### Monads

### Monad Transformers

### Type-level programming and dependent types in Haskell



## Academic and Advanced Resources

I've barely dipped my toes in the water with most of these but it
becomes obvious quickly if you spend any time with any one of these
collections that there is enough knowledge here to last one a
lifetime. Enjoy, don't drown...

### [Simon Peyton Jones's page at Microsoft Research](https://www.microsoft.com/en-us/research/people/simonpj/)

I heard this guy did some Haskell stuff _shrugs_

### [Philip Wadler's home page](http://homepages.inf.ed.ac.uk/wadler/)

Great, important papers here, written in an entertaining
style. Professor Wadler is one of the people who helped create Haskell
and has contributed a lot to the language over the years. Check out
his [papers on
monads](http://homepages.inf.ed.ac.uk/wadler/topics/monads.html),
[Propositions as
Types](http://homepages.inf.ed.ac.uk/wadler/topics/history.html#propositions-as-types),
and more for a background in some of the ideas that helped make
Haskell what it is today.

### [okmij.org (Oleg Kiselyov's site)](http://okmij.org/ftp/)

Quite frankly, an incredibly intimidating collection of
resources. Oleg is notable for his writing on all kinds of topics, in
particular, in the Haskell realm, I think his papers on [Extensible
Effects](http://okmij.org/ftp/Haskell/extensible/) have been
influential. I've only really touched a few items here and there--in
particular I found his page on [tagless-final
style](http://okmij.org/ftp/tagless-final/) to be a useful guide on
the subject (in particular the lecture notes/tutorial at the top:
[Typed Tagless Final Interpreters: Lecture
Notes](http://okmij.org/ftp/tagless-final/course/lecture.pdf)).

### [Graham Hutton's publications](http://www.cs.nott.ac.uk/~pszgmh/#bibliography)

Already mentioned above. Lots of good stuff here, and I find Professor
Hutton's writing to be very approachable.

### [Richard Bird's publications](https://www.cs.ox.ac.uk/people/richard.bird/)

Not a lot linked to there but check out his book on [Functional
Pearls](https://www.amazon.com/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383)
if you want to really blow your mind. I think I made it through like
one or two of the articles in that book (which is a collection of
articles taken from a recurring column in the Journal of Functional
Programming. More context to be found on Prof. Jeremy Gibbons site
[here](https://www.cs.ox.ac.uk/people/jeremy.gibbons/pearls/)

### [The Monad Reader](https://themonadreader.wordpress.com/)

Collections of articles on various esoteric and not-so-esoteric topics
in Haskell. "The Monad.Reader is a electronic magazine about all
things Haskell. It is less formal than journal, but somehow more
enduring than a wiki-page."

### [The Comonad Reader](http://comonad.com/reader/)

A blog with a few rotating authors, notably [Edward
Kmett](https://github.com/ekmett) (apologies to Dan Doel and Gershom
Bazerman, you are probably also notable but Edward Kmett has his name
on every damn library in the ecosystem, so...) 

I occasionally look at this blog, realize how out of my depth I am,
bookmark it for later and close the tab. Something to aspire to.
