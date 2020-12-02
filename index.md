**Quick Links**

[2020](#2020)

# 2020

## Coursework

I spent January to April finishing up my undergraduate degree in CS and Combinatorics and Optimization at UWaterloo.
As a result of only having 2 easy required courses left to take, I spent most of term absorbing as much combinatorics knowledge as I could:

- Random Graph Theory (CO 749)

    We worked through some major results and built up probability tools along the way as needed.
    The key highlight for me was probably a more thorough understanding of various concentration results.
    I gave up on LaTeXing my notes since the calculations were quite gruesome, but have some hybrid [typed/scanned notes](https://nicholaspun.github.io/course-notes/co749_random/co749.pdf) on my notes site.
    The main reference was [Bollobás' book](https://www.cambridge.org/core/books/random-graphs/E21023008001CFA182CE666F5028489F), but it was actually a bit too fast for me to follow so I also referenced [Frieze and Karoński's book](https://www.cambridge.org/us/academic/subjects/mathematics/discrete-mathematics-information-theory-and-coding/introduction-random-graphs?format=HB).

- Graph Colourings (CO 749)

    We went through a lot of the cutting edge (as of the time this was written) in graph colourings.
    To be very honest, a _lot_ of the content went over my head.
    At the very least, though, I walked away with a _much_ more expanded view of graph theory and, as a bonus, picked up a couple tools, methods and concepts along the way.
    Overall, everything covered in this course was _super_ interesting and I definitely gained a better appreciation of some of the deeper results.
    Some of the references we went through can be found in my [scans](https://nicholaspun.github.io/course-notes/co749_colourings/co749.pdf).

- Combinatorial Design (CO 434)

    And now back to courses I actually understood a lot of.
    This course was the wildest mishmash of linear algebra, abstract algebra, number theory and combinatorics I've ever seen.
    It was so nice to see how seemingly different combinatorial problems could just be cast as one another.
    I don't doubt that there were even deeper connections that I missed, so I'll definitely be revisiting this material in the near future.
    I started typing up my [notes](https://nicholaspun.github.io/course-notes/co434/co434.pdf) and the main reference for this course was Stinson's _[Combinatorial Designs: Constructions and Analysis](https://www.springer.com/gp/book/9780387954875)_.

And since I'm also a CS student, I did actually take some CS courses:

- Introduction to Symbolic Computation (CS 487)

    This course was the perfect balance between mathematics and computer science.
    _Some_ of the proofs were glossed over (which was actually reasonable since an algebra course was not a prereq), but the textbook: _[Modern Computer Algebra, 3rd Edition (von Zer Gathen, Gerhard)](https://www.cambridge.org/core/books/modern-computer-algebra/DB3563D4013401734851CF683D2F03F0#)_ went through all the gory details so I was content.
    We pretty much went through all of Part I and II and Chapter 14, of which I typed up partial [notes](https://nicholaspun.github.io/course-notes/cs487/cs487.pdf) for. 
    I wrote up a project surveying primality testing methods which I may put up on a later date.
    Quite a fun project---pretty much covered all of chapter 18 in the textbook, but also had to hunt around for references to other algorithms.

- Models of Computation (CS 365)

    Took a deep dive into most of Part I (Automata theory) and Part II (Computability theory) of Sipser's _[Introduction to the Theory of Computation, 3rd edition](https://math.mit.edu/~sipser/book.html)_.
    We meant to do more, that is, the plan was to spend 3-4 weeks on Part III (Complexity theory), but unfortunately, due to COVID-19, we only got through Chapter 7 (Time complexity).
    The complexity portion was a bit more interesting to me so my plan is to go through Chapter 8 and 9 by myself and then pick up Arora and Barak's _[Computational Complexity: A Modern Approach](http://theory.cs.princeton.edu/complexity/)_ and work through that.


## Algorithms

- Introduction to Algorithms (MIT 6.006, Fall 2011) 
[[Course Site]](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/index.htm)
[[Lectures]](https://www.youtube.com/playlist?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)


    The material taught here was review, but I wanted to make sure I wasn't missing anything before moving onto the followup course: 6.046J.
    I basically just sped through the lecture videos and sketched answers to their problem sets (minus the coding portions).

- Design and Analysis of Algorithms (MIT 6.406J, Spring 2015)
[[Course Site]](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/)
[[Lectures]](https://www.youtube.com/playlist?list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

    Mostly review as well.
    I hadn't seen any of the distributed content or the cache-oblivious content so that was nice.
    I'm surprised they jam pack such a large breadth of content in the latter half of the course.
    I guess from the perspective of a student this is an awesome teaser to algorithms in different areas.
    I loved the Network Flow theory (CO351) course at UWaterloo so it was great to see them going over the max-flow, min-cut theorem.

    It was interesting to see a lot of familiar looking questions on the problem sets.
    I guess a lot of these are your bread-and-butter-type extensions to the core material taught in lectures.
    The problem sets reminded me a lot (maybe too much) of when I would sit in my chair for hours on end trying to solve them for the first time.

- A Second Course in Algorithms (Stanford CS261, Winter 2016)
[[Course Site]](http://timroughgarden.org/w16/w16.html)
[[Lectures]](https://www.youtube.com/playlist?list=PLEGCF-WLh2RJh2yDxlJJjnKswWdoO8gAc)
    
    Parts III and IV were all content I hadn't seen before.
    The problem sets and exercises are extremely interesting and I have to admit that some of the problems in the problem sets are genuinely tough.
    As of the time that I'm writing this, there are still a couple problems that I don't yet have the solution to.

    The main takeaways for me was the brief introduction to online algorithms and the emphasis on primal-dual methods for algorithm design in the latter half of the course.
    I had seen primal-dual algorithms before, but these lectures really helped it click.

    Looking ahead, I kind of want to learn more techniques and methods.
    I have my eye on [_Online Algorithms: The State of the Art_](https://link.springer.com/book/10.1007/BFb0029561) by Fiat and Woeginger.
    I'll, of course, update this site if I continue down that route.
    The graduate course CS266 was also mentioned in this course, but unfortunately they don't seem to have course notes or videos.
    I may flip through [_Parameterized Algorithms_](https://www.springer.com/gp/book/9783319212746) by Cygan et al..

- I/O Efficient Algorithms (Coursera) [[Course Site]](https://www.coursera.org/learn/io-efficient-algorithms)

    Was motivated to learn more about cache-oblivious algorithms from the teaser at the end of 6.046J.
    The course helped to solidify some concepts, and I also learned some more cool concepts such as time-forward processing and buffer trees.
    Check out my certificate for this course [here](https://www.coursera.org/account/accomplishments/certificate/PR2Z7JQ93Z8Y)!

<!-- - [Algorithmic Lower Bounds: Fun with Hardness Proofs (6.890, Fall 2014)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-890-algorithmic-lower-bounds-fun-with-hardness-proofs-fall-2014/): In-progess -->

<!-- - [Advanced Data Structures (6.851, Spring 2012)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/index.htm): In-progress -->


## Deep Learning

### Projects

- [Similar Images Purger](https://github.com/nicholaspun/similar-images-purger) -
The project that kickstarted my journey of picking up deep learning.
My goal was to remove similar looking images from my massive photo album (We actually consider the dual problem of producing a representative set of images from the album instead).
To that end, I dip my feet into [_TuriCreate_'s image similarity model](https://apple.github.io/turicreate/docs/userguide/image_similarity/) and play around with clustering algorithms available in [scikit-learn](https://scikit-learn.org/stable/)

- [IZ*Net](https://github.com/nicholaspun/IZ-Net) -
This project came after I took the CNN course on Coursera (see below), so I knew a tad bit more about deep learning.
As such, this is a more hands-on project where I build CNN models from scratch in order to create a face recognition model and also code up a simplified version of the YOLO algorithm to do face detection.

- [ARAMNet](https://github.com/nicholaspun/ARAMNet) -
A portion of a larger project I spent some time on in trying to solve a toy probability problem, inspired by ARAM, a game mode in popular game League of Legends.
As part of our work, we create an RNN to help us performs simulations and obtain empirical evidence for our toy problem.

### [Deep Learning Specialization (Coursera)](https://www.coursera.org/specializations/deep-learning)

I successfully completed the entire Deep Learning specialization!
(Certificate can be found [here](https://coursera.org/share/fc71fc75bc6bf0057ad12224e0b438f3)!)
It was quite the journey, I learned a lot of cool things and got a taste on various different architectures and problems in this field.
Andrew Ng did a wonderful job of simplifying the content and peeling out the important bits for discussion during the lectures.
That said, although we covered a huge breadth of material, I think the next goal for me is to delve into a bit more depth on particular topics.
I'll probably continue expanding my knowledge in this field; I have a couple other courses and textbooks I'll probably give a shot in the upcoming months.

### [Generative Adversarial Networks (Coursera)](https://www.coursera.org/specializations/generative-adversarial-networks-gans)

Lo and behold, Deeplearning.ai has a course for GANs as well.
After finishing the Deep Learning specialization, this one has been quite digestible so far.
I completed the [first course](https://www.coursera.org/learn/build-basic-generative-adversarial-networks-gans) (See [certificate](https://www.coursera.org/account/accomplishments/certificate/W4UW5T563DC3)) and am well on my way into the second. 
The third seems to be unavailable for now, so we'll see when that comes out for me to finish up this specialization.

## Computer Networking

Currently on Chapter 4 of [Computer Networking: A Top-Down Approach](https://www.pearson.com/us/higher-education/program/Kurose-Computer-Networking-A-Top-Down-Approach-7th-Edition/PGM1101673.html).
(Update October 2020: And probably will be for a while ... I've reprioritized the things I want to learn right now, so this sitting in the back-burner for now ...)

_(Last updated Dec. 1st)_

