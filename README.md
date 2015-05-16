# learning-clojure
Resources and suggestions from the Boston Clojure Group for how to learn Clojure 

## Curriculum

### Beginner
- Environment Setup: Java, Leiningen, IDE (optional) or use [Try Clojure](http://tryclj.com/)
- [Koans](http://clojurekoans.com/) to get a taste of Clojure (low barrier of entry, can try in small chunks, free)
- Setup your favorite text editor for a Clojure dev workflow, particularly including the inline help functionality
- Book, one of:
  - (easy) Clojure for the brave and true 
  - (mid) Clojure Programming
  - Easy 4clojure problems
  - Come to the Boston Clojure Group (or local one)
  - Get a Clojure mentor  (how?)

### Advanced
- clojure.test
- Build a website with some web framework (ring, compojure, pedestal, etc)
- Give a talk on your local Clojure Group meetup
- Online videos (see list below)
  - Conferences
  - Clojure/conj
  - Clojure/west
  - EuroClojure
  - StrangeLoop
  - Poly Conf

### Expert

- Contributing to open source projects
  - LightTable
  - Incanter  
  - how about a list of easier projects people can contribute to?
  - [Github search on open clojure(script) issues with label 'helpwanted'](https://github.com/search?l=&amp;q=extension%3Aclj+extension%3Acljs+label%3Ahelpwanted&amp;ref=advsearch&amp;type=Issues&amp;utf8=%E2%9C%93)
  - [Github search on open clojure(script) issues with label 'newbie'](https://github.com/search?utf8=%E2%9C%93&amp;q=extension%3Aclj+extension%3Acljs+label%3Anewbie&amp;type=Issues&amp;ref=searchresults)
  - Take part in https://clojurecup.com/
  - Work at a Clojure shop (TODO paste in Boston list)
  - Mentor someone to become Clojure programmer

### Teacher's Notes
- Consider not mentioning the L-word.
- Clojure's contempt for the comma is inspirational.
- Begin with the value syntax leaving symbols and lists for last.
- Tell them Clojure values are like Java String if they know Java.
- Bring stickers.

### Categories
- Lisp Philosophy
- Clojure(Script)
- Clojure Internals(?)
- Concurrency
- Immutability(?)
- FP-vs-OOP(?)

## Books
### Beginner Books 

- [Programming Clojure](https://pragprog.com/book/shcloj2/programming-clojure) - Stuart Holloway
- [Clojure for the brave and true](http://www.braveclojure.com/)
  - Not yet finished, but good/easy read for people who don't have much of programming background.
- [Living Clojure](http://shop.oreilly.com/product/0636920034292.do)
  - Living Clojure starts out with a well-written beginner introduction to Clojure, covering basic syntax and core type and functions in a clear and easy to understand form. After the gentle intro however, there's a fairly abrupt jump to advanced topics including concurrency types, macros, multimethods and protocols. The second half of the book is a list of learning resources plus a curriculum sequence of problems meant to gradually build Clojure proficiency.
- [Clojure from the ground up](https://aphyr.com/posts/301-clojure-from-the-ground-up-welcome) - good for people new to programming
- [ClojureScript: Up and Running](http://shop.oreilly.com/product/0636920025139.do)
  - in case you're interested in cljs specifically. Bootstrap environment & get basics of clojure.

### Expert Books
- [Clojure Programming](http://www.amazon.com/Clojure-Programming-Chas-Emerick/dp/1449394701/ref=sr_1_1?ie=UTF8&amp;qid=1431646066&amp;sr=8-1&amp;keywords=clojure+programming)  -  Chas Emerick et. al.  
- [Joy of Clojure](http://www.amazon.com/dp/1617291412/ref=sr_1_1?ie=UTF8&amp;tag=fogus-20) - very in depth about Protocols
- [Clojure In Action](http://www.manning.com/rathore/)
- [Java Concurrency in Practice](http://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601) (About java but explains the problems Clojure is solving)
- [Mastering Clojure Macros](https://pragprog.com/book/cjclojure/mastering-clojure-macros)

### Special Domain
- [Web Development with Clojure](http://www.amazon.com/Web-Development-Clojure-Build-Bulletproof/dp/1937785645/ref=pd_sim_14_2?ie=UTF8&amp;refRID=1XCZZAQS6D1XGFK3SD5Y)
- [Clojure Web Development Essentials](http://www.amazon.com/Clojure-Development-Essentials-Ryan-Baldwin/dp/1784392227/ref=pd_sim_14_10?ie=UTF8&amp;refRID=0CVDV1WMBASVFJSJJJWB)
- [Mastering Clojure Data Analysis](http://www.amazon.com/Mastering-Clojure-Data-Analysis-Rochester/dp/1783284137/ref=pd_sim_14_2?ie=UTF8&amp;refRID=1X482550WHF1S5ESTDBW)
- [Clojure Data Analytics Cookbook](http://www.amazon.com/Clojure-Analysis-Cookbook-Second-Edition/dp/1784390291/ref=pd_sim_14_2?ie=UTF8&amp;refRID=0JG9268N8309HFVKN5PW)
- [Clojure for Machine Learning](http://www.amazon.com/Clojure-Machine-Learning-Akhil-Wali/dp/1783284358)

### General Lisp thinking
- [SICP](http://mitpress.mit.edu/sicp/full-text/book/book.html) - theory of programming (CS textbook, written for Scheme)
- [The Little Schemer](http://www.amazon.com/The-Little-Schemer-4th-Edition/dp/0262560992) (only ~50 pages, thinking recursively in Scheme)
- [The Reasoned Schemer](http://mitpress.mit.edu/books/reasoned-schemer) (miniKanren and logic programming in Scheme)
- [On Lisp](http://www.paulgraham.com/onlisp.html) (thinking in Lisp and macrology)

## Videos
- [Simple Made Easy](https://www.youtube.com/watch?v=rI8tNMsozo0)  - Rich Hickey
- [Are We There Yet](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/AreWeThereYet.md) - Rich Hickey
- [SICP Video Lectures](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/) - Hal Abelson and Gerald Jay Sussman
- [The Value of Values](https://www.youtube.com/watch?v=-6BsiVyC1kM)  - Rich Hickey
- [Implementation details of core.async Channels](https://vimeo.com/100518968) - Rich Hickey
- [Designing Front End Applications with core.async](http://go.cognitect.com/core_async_webinar_recording) - David Nolen
- [Inside Transducers](https://www.youtube.com/watch?v=4KqUvG8HPYo) - Rich Hickey

## Libraries
- [Clojure Werkz](http://clojurewerkz.org/)
- [Arcadia](https://github.com/arcadia-unity/Arcadia) - Clojure in Unity
- [Clojure Toolbox](http://www.clojure-toolbox.com/)
- https://crossclj.info

## Tutorials
- [Beginner Web REPL](http://www.tryclj.com/)
- [Clojure MOOC](http://mooc.fi/courses/2014/clojure/)
- http://www.lisperati.com/clojure-spels/casting.html
- [Using Emacs with Clojure](http://www.braveclojure.com/using-emacs-with-clojure/) 
- [Light Table interactive ClojureScript tutorial](https://github.com/swannodette/lt-cljs-tutorial)
- [ClojureScript 101](http://swannodette.github.io/2013/11/07/clojurescript-101/) - using core.async to build search for image from wiki
- [om tutorial](https://github.com/omcljs/om/wiki/Basic-Tutorial)
- [Learn Datalog Today](http://www.learndatalogtoday.org/) - [Datalog](http://en.wikipedia.org/wiki/Datalog) tutorial (something you might heard of when looking into Datomic/Datascript)

## Problem sites
- http://clojurekoans.com/
- http://clojurescriptkoans.com/
- http://www.4clojure.com/problems
- http://exercism.io (great site but the problem set is language-universal and some of them are un-idiomatic in a functional language)
- http://www.codewars.com/
- https://www.codingame.com/home

## Clojure Documentation
- [Grimoire](http://conj.io/)
- http://clojuredocs.org
- http://clojure-doc.org

## Build / Dependency Tools
- Leiningen
- Boot
- Maven

## Editors and IDEs
- Emacs ([cider](https://github.com/clojure-emacs/cider) , company-mode, auto-complete, [smartparens](https://github.com/Fuco1/smartparens) ) (spacemacs?) Aquamacs!
- Vim ([fireplace](https://github.com/tpope/vim-fireplace), [vim-leiningen](https://github.com/tpope/vim-leiningen), paredit, [rainbow-parentheses](https://github.com/eapache/rainbow_parentheses.vim))
- IntelliJ (Cursive)
- Eclipse (Counterclockwise)
- Light Table
- [Sublime Text](https://sublimetext.com/) (+ [paredit](https://github.com/odyssomay/paredit) & [lisp-indent](https://github.com/odyssomay/sublime-lispindent))
- Textmate
- [Atom](https://atom.io/) - clojure mode, paredit, nrepl-eval, emacs bindings

## Testing
- midje
- clojure.test
- test.check

## ClojureScript
- [figwheel](https://github.com/bhauman/lein-figwheel) - lein plugin to enable livereload experience (blogpost with demo)
- [datascript](https://github.com/tonsky/datascript) - Immutable database and Datalog query engine in ClojureScript
- [om](https://github.com/omcljs/om)/[reagent](https://github.com/reagent-project/reagent)/[quiescent](https://github.com/levand/quiescent)/[rum](https://github.com/tonsky/rum)
- [chestnut](https://github.com/plexus/chestnut)
- [devcards](https://github.com/bhauman/devcards)

## Clojure in Production
- usual Jar deployment workflows
- docker-clojure

## Alternative platforms
- ClojureScript
- [Python](http://halgari.github.io/clojure-py/) 
- [CLR](https://github.com/clojure/clojure-clr) 
- [Pixie](https://github.com/pixie-lang/pixie.git)

## Clojure-inspired / transpilers
- [wisp](https://github.com/Gozala/wisp) (JavaScript Lisp)
- [Hy](http://docs.hylang.org/) (Python Lisp)

## Clojure Presentations
- [Better Living Through Clojure](https://docs.google.com/presentation/d/1y8TJECz9b1n_gTgeL2qdXWXThkiPnZ1gXGozfkPsWcY/edit#slide=id.p)  - MIT IAP 2015 Presentation

## Clojure Online Forums / Sites / Newsletters
- Clojure IRC Channel
- ClojureScript IRC Channel
- Clojure Google Group
- ClojureScript Google Group
- Clojure on LinkedIn
- Clojure Subreddit 
- Clojure Gazette - Newsletter by Eric Normand

## Single Topic Posts
- [Clojure Destructuring](http://blog.jayfields.com/2010/07/clojure-destructuring.html)  - Jay Fields

## Meta-lists
- [Top Clojure Articles article](http://adambard.com/blog/greatest-clojure-hits/)
- [Awesome Clojure](https://github.com/razum2um/awesome-clojure)
- [Learn Clojure](http://learn-clojure.com/) 

## Cheatsheets
- [ClojureScript](- http://cljs.info/cheatsheet/)
- [Clojure](http://clojure.org/cheatsheet)
- [Paredit](http://emacswiki.org/emacs/PareditCheatsheet)

## Common Beginner Hurdles
- Environment setup (Cider and Leiningen helped me)
- [So many parens](http://www.thejach.com/imgs/lisp_parens.png)!!  (But not so many as other LISPs!)
- Immutable everything
- Writing loops
- [Contrib library got reorganized](http://dev.clojure.org/display/community/Where+Did+Clojure.Contrib+Go) 
- there needs to be a resource to help solve [command line bullshittery](http://pgbovine.net/command-line-bullshittery.htm) 
- Emacs [C-x M-c M-](https://i2.wp.com/imgs.xkcd.com/comics/real_programmers.png?resize=740%2C406) [16-fingers](http://fc04.deviantart.net/fs71/i/2011/029/8/3/emacs_user_at_work_by_earlcolour-d38aj2x.jpg) bullshittery
- Doubt about the usefulness of LISP (stereotype about it being a dead language used only [for AI](https://image.slidesharecdn.com/clojure-110806031926-phpapp01/95/clojure-7-728.jpg)) I think this is totally dated - the grad students and other younger people I work with know nothing about this. Put another way, it's irrelvant.

## Boston Clojure Group Resources
- [Boston Clojure Group Meetup](http://www.meetup.com/Boston-Clojure-Group/) - Usually the 3rd Thursday of every month at Akamai, Kendall Sq.
- [Boston Clojure Group Google Group](https://groups.google.com/forum/#!forum/boston-clojure)
- [Boston Clojure Group Github](https://github.com/boston-clojure)
- Boston Clojure Group Hashtag: #bosclj

