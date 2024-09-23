**< [Back to main](../index.md)**

**< [Back to materials](../materials.md)**

Unfortunately, in the current situation many of us, who was working in Finale to engrave their scores, are forced to switch to another score editing software due to the reason that Finale won’t be supported anymore, so it means that we have the last current version of it and only one year of possibility to install it on another device and authorize with our license. Of course, we still can use our installed instances of the program until its compatibility reaches the border of new OS architecture, but it’s not forever.

During the past decades, we saw the rise and dawn of Sibelius from an incredible alternative to Finale to subscription-based software (which price is extremely unpleasant, especially for students), and the painful death of Finale. Now we do have another corporate monster — Dorico. I’m very afraid that no matter how good and developed Dorico now is, it could happen with it the same.

That's why I want to introduce you [Lilypond](http://lilypond.org/), a free open-source cross-platform software for engraving scores. 20 years ago Lilypond was mostly like a joke on the background of such giants like Sibelius and Finale, but during these years it was developing by hands of enthusiasts and now is a very good alternative to existing software. Lilypond is written in one of the dialects of [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)), which makes it super compatible and reusable on all devices. Even without its original team, the project will continue to develop because of its architecture and open-source.

Now in Lilypond you can easily engrave such complex notation as very small microtones, multiphonics, different kinds of graphic notation, and many more without installing additional packages, fonts etc. All of that is already built-in. A lot of things about layout and other boring stuff are already well automated, and if you aren’t satisfied with its result, you can adjust it to your needs.

The only problem is that Lilypond is a programming language, which makes approaching it a bit harder than approaching some GUI-based software such as Sibelius, Finale or Dorico. But there is also a solution. Lilypond has a few [GUI-based environments](https://lilypond.org/easier-editing.html), that simplify your life during the engraving process. I reccomend to use Frescobaldi as a GUI for Lilypond, it’s better documentated than the other and more convenient to use. In Frescobaldi you have such familiar tools as Score Manager (to create blank score with the title, composer, instruments and etc), dynamic and articulation marks, lines, that you can just grab and place into the score.

An incredible feature of Lilypond is an implementation into BACH library in Max/MSP and OpenMusic, which allows you to create ready-to-print scores for performers out of BACH and OM patches, which could be an essential tool for algorithmic and computer-assisted composition. And if to go further, Lilypond is just a programming language, a text — so you can generate material for your scores in any other programming language and then just format it in Lilypond layout. Because of its text-based structure you can even use github to make version control and to backup all your scores.

You can be afraid of the big amount of text that you should read and understand, so I made a research for you (and for me, sure, because I’m also planning to start using it), and I have some most important resources. I definitely recommend to start from video-tutorials and only then dive into the books that they offer.

- [Installing process](https://lilypond.org/doc/v2.24/Documentation/learning/installing)

- [Video tutorials](https://youtube.com/playlist?list=PLHi8BvxILUV6x9FqEmZiYrEj6VMGmTKjt&si=EvQ59bfyJH42t1sx) from Ben Lemon. Really helps to start engrave some simple scores in a small amount of time. Super understandable short videos.
<iframe width="100%" height="500" src="https://www.youtube.com/embed/videoseries?si=uG4Yx4gEeuy02TO1&amp;list=PLHi8BvxILUV6x9FqEmZiYrEj6VMGmTKjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>

- [Video tutorials](https://youtube.com/playlist?list=PL3frlaLiaXz_zQmiGbGeh3Q96sO6nt-l-&si=7NbAqGWTvvA7Wnnl) from Mikhail Puchkov. Mikhail Puchkov is a russian composer and also one of the main pioneers of Lilypond nowadays, and he has recorded 4 tutorials for contemporary composers about some elements of contemporary notation, and he was planning to make more. Unfortunately (not for me and Valerii), it's in russian, but you can use auto-generated subs or voice-translation tools.
<iframe width="100%" height="500" src="https://www.youtube.com/embed/videoseries?si=7NbAqGWTvvA7Wnnl&amp;list=PL3frlaLiaXz_zQmiGbGeh3Q96sO6nt-l-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>

- [Learning manual](https://lilypond.org/doc/v2.24/Documentation/web/learning). Must-have to read. The content of the first chapter of the book is pretty the same as the content of Ben Lemon's tutorials. But Chapter 2 and 3 give you more deep understanding of the syntax and mechanics that are covered under Lilypond. 

- [Notation manual](https://lilypond.org/doc/v2.24/Documentation/web/notation). All needed information is here. How to notate the shit with full explanation, and you can easily search through the document.

- [Snippets](https://lilypond.org/doc/v2.24/Documentation/web/snippets). Just some snippets with ready-to-use solutions.

- [Essay](https://lilypond.org/essay.html) of Lilypond's developers about engraving and philosophy. It's a small essay from devteam about their inspiration and development process of Lilypond. Optional to read, but it's quite interesting.