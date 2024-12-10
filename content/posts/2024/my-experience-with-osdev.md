+++
title = "My Experience With Operating System Development"
date = "2024-12-10T07:25:57-05:00"
author = "Liam Greenway"
cover = ""
tags = ["osdev", "operatingsystem", "c", "c#", "assembly", "asm"]
keywords = ["osdev", "experience", "blog"]
description = "I talk about Operating System Development and x86(_x64)"
showFullContent = false
readingTime = false
hideComments = false
+++

# My (Short Lived) Experience With Operating System Development

### Preamble
A while ago (April-September 2024), I decided to try OSDev. I first started working in [C#](https://dotnet.microsoft.com/en-us/languages/csharp/) with the library/framework [Cosmos](https://cosmosos.github.io/), and I actually got pretty far (as in a terminal and a purple screen). Eventually, I realized that C# wouldn't work for several reasons. I could actually make a [full os in C#](https://en.wikipedia.org/wiki/Singularity_(operating_system)/), but the toolchain was too complicated, and I decided to use C (which has more preexisting tools and support) and got to work on lithium (my most recent attempt). Working on lithium helped me a lot. It forced me to learn C and how CPUs work on a fundamental level. I used this to work on my own CPU design later. During this short-lived phase, I used The [Operating System Development Wiki](https://wiki.osdev.org/Expanded_Main_Page), [Daedalus Community's Making an OS(x86)](https://www.youtube.com/watch?v=MwPjvJ9ulSc&list=PLm3B56ql_akNcvH8vvJRYOc7TbYhRs19M) series, and [nanobyte's Building an OS](https://www.youtube.com/watch?v=9t-SPC7Tczc&list=PLFjM7v6KGMpiH2G-kT781ByCNC_0pKpPN). I highly reccommend dipping your toes into OSDev. Even though it went nowhere, I learned a lot of other skills that I would've never bothered to look into.

### The C# Arc
I started my OSDev journey with the [Cosmos](https://cosmosos.github.io/) library/framework. I became acustommed to the prexisting API for doing things an OS would do. There were functions for printing to, changing the color of, and clearing the screen. There was a system to play audio, a system to display a GUI, and a system for mounting filesystems. I named my OS XenOS (my youtube channel and github name at the time was Xeno). 