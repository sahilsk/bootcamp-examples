
[Source](http://www.golang-book.com/guides/bootcamp "Permalink to Bootcamp | Go Resources")

# Bootcamp | Go Resources

The following videos were put together in July of 2015 for the [Summer Web Bootcamp][1] at Fresno City College. The videos cover the material in _An Introduction to Programming in Go_ along with the basics of server-side web development with Go and Google App Engine.

Thanks to the hard work of Todd McLeod (and others) these videos are available for free on Youtube. An outline is available at [is.gd/gobootcamp][2]. An additional outline is available [here][3]. Source code is available on [Github][4]. Questions, concerns or comments can be sent to [Caleb Doxsey][5].

## Links

1. Week 1
    1. [Day 1][6]: Machine Setup, Hello World, Variables, Types, A Deeper Look, Control Structures
    2. [Day 2][7]: Strings Revisited, Arrays, Slices and Maps, Functions
    3. [Day 3][8]: Review, Pointers, Structs and Interfaces
    4. [Day 4][9]
    5. [Day 5][10]
2. Week 2
    1. [Day 1][11]
    2. [Day 2][12]
    3. [Day 3][13]
    4. [Day 4][14]
    5. [Day 5][15]
3. Week 3
    1. [Day 1][16]: To-Do List, Twitter Clone, Data Store
    2. [Day 2][17]: Templates, Projection Queries, Email, Polling
    3. [Day 3][18]: Sort, Web, SQL
    4. [Day 4][19]: Long-Polling, App Engine Channels, Chat, Search
    5. [Day 5][20]: Search, Cloud Storage, Cloud API, URL Fetch
4. Week 4
    1. [Day 1][21]: Markdown, Self-Destructing Messages, Side-Channel Attacks, Cloud Storage, Stocks, Net HTML
    2. [Day 2][22]: ChartJS, Credit Cards, OAuth, Dropbox OAuth, GitHub OAuth, GitHub, Task Queue

Most of the presented material is basically correct, though sometimes I wasn't very clear or made broad, general assertions, which are debatable but merely stated with no tip of the hat to a contrary point of view. These videos are intended for beginner instruction not technical perfection.

Unfortunately I also made a few outright mistakes. Errata:

* I misinterpreted the meaning of Scanln, expecting it to read an entire line, when in fact it only reads to the first space.
* Permissions are used as octal, not hexadecimal. I showed one example using 0x777 when it should've been 0777.
* When discussing hashing I think I said "pairing bit", but meant "parity bit".
* At some point I said a for range loop on a string is byte by byte. Strings are stored as bytes, but the for range loop is actually rune by rune. It will interpret UTF8 for you.

[1]: http://summerwebbootcamp.com/sponsors.html
[2]: http://is.gd/gobootcamp
[3]: https://docs.google.com/document/d/1dfZvXsjDhq2NlrkFOikXPaBW55QJBoJd-2NFjUs5FlY/edit?usp=sharing
[4]: https://github.com/golang-book/bootcamp-examples
[5]: mailto:caleb@doxsey.net
[6]: /guides/bootcamp/week-1/day-1
[7]: /guides/bootcamp/week-1/day-2
[8]: /guides/bootcamp/week-1/day-3
[9]: /guides/bootcamp/week-1/day-4
[10]: /guides/bootcamp/week-1/day-5
[11]: /guides/bootcamp/week-2/day-1
[12]: /guides/bootcamp/week-2/day-2
[13]: /guides/bootcamp/week-2/day-3
[14]: /guides/bootcamp/week-2/day-4
[15]: /guides/bootcamp/week-2/day-5
[16]: /guides/bootcamp/week-3/day-1
[17]: /guides/bootcamp/week-3/day-2
[18]: /guides/bootcamp/week-3/day-3
[19]: /guides/bootcamp/week-3/day-4
[20]: /guides/bootcamp/week-3/day-5
[21]: /guides/bootcamp/week-4/day-1
[22]: /guides/bootcamp/week-4/day-2
  
