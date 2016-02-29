---
title: "Unix, GNU and Linux"
image: unix_header.jpg
description: The unsung revolution fueling the digital age
author: drew 
---

Unix is an [operating system](https://en.wikipedia.org/wiki/Operating_system) (OS) invented in 1969 at Bell Labs by [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson), [Dennis Ritchie](https://en.wikipedia.org/wiki/Dennis_Ritchie) and others. And — due to the flexibility afforded by its modular, collaborative approach to computing — over 40 years later, Unix and its descendants [power the overwhelming majority of the world's computing](https://en.wikipedia.org/wiki/Usage_share_of_operating_systems#Market_share_by_category).

The family of operating systems which descend from Unix are referred to collectively as "\*nix".

Sites like Google, Facebook, Twitter and the vast majority of websites were built on and run on \*nix. Apple's iPhones, iPads and iPods, Android smartphones and tablets, smart TVs, refrigerators, cameras, cars, watches, set-top boxes — they all run \*nix. Unix and its offspring power everything from the [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) to (all of) the world's most powerful supercomputers.

The digital age was built on Unix and its descendants. So how did this happen?

In the early days of computing, software was shared freely amongst its users and authors, who were often the same people. If you wrote a software tool to perform a particular task you would share it with anyone who wanted it. If I improved that tool then I would share my changes with you and with everyone else. Since this benefited everyone, why would any of us behave any differently?

This culture of sharing and co-operating influenced the shape of early software, encouraging the production of small, simple programs intended to be used together to perform complex tasks — rather than complex, monolithic programs that tried to do everything. Smaller, simpler programs were easier to maintain, share, re-use and modify, and could be plugged together to perform complex tasks. Improvements to one small component would thus benefit *all* of the complex applications of which that small program was a part — helping oneself helped others.

Bell Labs is a research and development facility which, during the time of Unix's development, was owned by AT&T and was famous for encouraging undirected, open-ended research. Important inventions and developments that came out of Bell Labs include the transistor, cellular telephony, solar cells, practical lasers, communication satellites, the touch-tone telephone and, of course, Unix. [Brian Kernighan](https://en.wikipedia.org/wiki/Brian_Kernighan), one of the developers of Unix, talks about his time at Bell Labs in the video below.

{% include yt.html vidid="QFK6RG47bww" %}

Unix, born out of this culture of sharing and co-operation where a collaborative approach was *assumed*, embodied what is now referred to as 'The Unix Philosophy'. The most well-known statement of this philosophy, by [Doug McIlroy](https://en.wikipedia.org/wiki/Douglas_McIlroy), goes like this:

>Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface.

McIlroy adds:

>The notion of "intricate and beautiful complexities" is almost an oxymoron. Unix programmers vie with each other for "simple and beautiful" honours — a point that's implicit in these rules, but is well worth making overt.

This insistence on simple elegance, modularity, co-operation and text-as-the-universal-interface is a large part of what set Unix apart and is, along with various technical attributes, what has been passed on to Unix's descendants.

Unix gained widespread use through the 70s and 80s, particularly in academic and commercial settings but was not really suitable for individual use for a couple of reasons: Firstly, Unix was designed primarily for mainframes and there was little interesting amongst its academic and commercial users in transferring it to home computers. Secondly, because AT&T were, as a regulated monopoly, not allowed to sell software, licensing was difficult.

As the personal computer saw broad adoption, the rise of proprietary, commercial software, such as Microsoft's DOS, eroded the culture of early computing — sharing proprietary software is illegal and modifying it is impossible since the source code is not available. As programs could no longer share and build upon each others' functionality, software became large, complex and monolithic by default.

In 1983, [Richard Stallman](https://rms.sexy/), an artificial intelligence researcher at the Massachusetts Institute of Technology, began the GNU project, the aim of which was to create an entirely free version of the Unix operating system (GNU stands for "GNU's not Unix"). "Free", in this context, means "[free as in freedom, not free as in beer](http://www.gnu.org/philosophy/free-sw.en.html)", a notion circumscribed by what Stallman called 'the Four Freedoms':

* The freedom to run the program as you wish, for any purpose (freedom 0).
* The freedom to study how the program works, and change it so it does your computing as you wish (freedom 1). Access to the source code is a precondition for this.
* The freedom to redistribute copies so you can help your neighbor (freedom 2).
* The freedom to distribute copies of your modified versions to others (freedom 3). By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.

In order to ensure that these freedoms remained intact as software was modified and shared, the [GNU General Public License](http://www.gnu.org/licenses/gpl-3.0.en.html) (GPL) was created. Similar to the [Creative Commons](https://creativecommons.org/) license used on *Rounded Globe*, the GPL employs a [copyleft](https://en.wikipedia.org/wiki/Copyleft) mechanism that ensures that no one can close the software down and/or make a proprietary version — the software will be free for everyone, forever, for any purpose.

In 1991, [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds), a computer science student at the University of Helsinki, created the Linux kernel because he wanted Unix on his personal home computer — the kernel is the 'bottom layer' of the operating system; it is the intermediary between other software and the hardware — the final core component that the GNU project lacked. The resulting operating system — a complete, free Unix — is called GNU/Linux, though it is most often just referred to as Linux.

Linux exists today as a free universal operating system that embodies the continuation of the culture of early computing — it is produced, maintained and distributed by thousands of people all around the world. It powers the internet and has allowed companies like Google, Twitter and Facebook to create businesses without being crippled by software licensing costs (there are none). It runs smartphones, laptops, tablets, Kindles and watches. It's allowed the Raspberry Pi to bring accessible, malleable computing to classrooms and individuals without licensing costs. It runs the computers at [CERN](https://en.wikipedia.org/wiki/CERN), it's on the [Curiosity Mars rover](https://en.wikipedia.org/wiki/Curiosity_%28rover%29), it's aboard the [International Space Station](https://en.wikipedia.org/wiki/International_Space_Station) and it runs [Munich](http://www.techrepublic.com/article/how-munich-rejected-steve-ballmer-and-kicked-microsoft-out-of-the-city/). Unless you live in a cave, you use Linux many times every day.

Perhaps Linux's most surprising achievement, though, is getting huge, commercial entities like Google, Samsung, IBM, Toyota and countless others to work collaboratively. They all contribute — through paying developers, sponsorship and other mechanisms — to the Linux kernel and other parts of the operating system. And when they improve Linux for themselves they improve it for everyone else — even their direct competitors.

The one arena of computing where \*nix *doesn't* dominate is, of course, desktop operating systems (i.e. desktop PCs and laptops) where Microsoft's Windows holds sway. So, while Unix and its progeny have very much defined and shaped the technology of the world in which we live, and virtually *every* computer user interacts with it in some way on a daily basis, most everyday computer users are largely unacquainted with it. If you'd like to try Linux out on *your* desktop or laptop computer then [Ubuntu](http://www.ubuntu.com/desktop) or [OpenSUSE](https://www.opensuse.org/) are good places to start.

{% include yt.html vidid="SYRlTISvjww" %}
