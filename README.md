[![License: GFDLv1.3](https://img.shields.io/badge/license-GFDLv1.3-blue
)](https://www.gnu.org/licenses/fdl-1.3.html)

> [!IMPORTANT]
>
> This project is not supported anymore. But can be reopened if interest will
> be in it. Please, let me know if you need something. Just write me email to
> `igor.mironchik at gmail.com`.

# The book about real examples of Qt Widgets usage

> Copyright (C) 2019-2024 Igor Mironchik.
> 
> Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License".

> Note that in the last release of GIF Editor underlying work with GIF format
was changed and use now [`qgiflib` library](https://github.com/igormironchik/qgiflib).
`ImageMagick` is not very good to work with GIF, as it needs to have all frames
in memory, that with large GIFs makes GIF Editor unusable, whereas `qgiflib`
stores actual frames as PNG files on disk, that allows to load really big GIFs.
>
> So keep it in mind when you'll read this book.

1.  [Preface](preface.md)
2.  [Chapter 1 - GIF editor](chapter01/01.md)
    * [Introduction](chapter01/01.md)
    * [Basics of a main window](chapter01/02.md)
    * [Launching](chapter01/03.md)
    * [Plans](chapter01/04.md)
    * [Frame](chapter01/05.md)
    * [Frame on tape](chapter01/06.md)
    * [Tape](chapter01/07.md)
    * [View](chapter01/08.md)
    * [Reading](chapter01/09.md)
    * [Saving](chapter01/10.md)
    * [What else](chapter01/11.md)
    * [Crop](chapter01/12.md)
    * [About](chapter01/13.md)
3.  [Chapter 2 - working with camera](chapter02/01.md)
    * [Introduction](chapter02/01.md)
    * [View](chapter02/02.md)
    * [Video surface](chapter02/03.md)
    * [Camera](chapter02/04.md)
    * [Capture images](chapter02/05.md)
4.  [Chapter 3 - multithreading](chapter03/01.md)
    * [Introduction](chapter03/01.md)
    * [Implementation](chapter03/02.md)
5.  [Chapter 4 - mistakes handling](chapter04/01.md)
6.  [Chapter 5 - QML](chapter05/01.md)
    * [Introduction](chapter05/01.md)
    * [C++ and QML](chapter05/02.md)
    * [Board](chapter05/03.md)
    * [Main window](chapter05/04.md)
    * [Dialogues](chapter05/05.md)
    * [Start of the application](chapter05/06.md)
7.  [Chapter 6 - Porting from Qt5 to Qt6](chapter06/01.md)
8.  [Links](links.md)
9.  [Thanks](thanks.md)
10. [GNU Free Documentation License](fdl-1.3.md)
