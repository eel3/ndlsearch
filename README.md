ndlsearch
=========

Select bibliographic information from NDL (National Diet Library)
where ISBN is equal to user input.

License
-------

zlib License.

Target environments
-------------------

Cygwin, Linux, macOS.

ndlsearch_isbn is shell script (sh),
and so probably works fine on other Unix-like environment.

Set up
------

1. Install wget(1) or curl(1).
2. Install Python 2.7.
3. Install [isbnutil](https://github.com/eel3/isbnutil "isbnutil repository").
4. Put ndlsearch_isbn in a directory registered in PATH.
5. If you want to use curl(1), you must modify ndlsearch_isbn.

| function  | description                                           |
|:----------|:------------------------------------------------------|
| ndlsearch | Comment-out wget(1) line, and uncomment curl(1) line. |

Usage
-----

Please check help message `ndlsearch_isbn -h`

Example
-------

    $ ndlsearch_isbn 9784775302491
    ISBN 4775302493
    Title プログラミング言語AWK
    Author A.V.エイホ, B.W.カーニハン, P.J.ワインバーガー 共著,足立高徳 訳,
    Publisher 新紀元社
    Published-Year 2004
    NDC9 007.64
    $ _
