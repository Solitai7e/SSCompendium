Karamarea
=========

There are several numbering systems of varying complexity within the Synapsian language. The digit-by-digit pronounciation of karamarea, which we'll be exploring in the second part of this section, is mainly applied to location-related purposes (house numbers, postal codes, street numbers, etc. - this is comparable to how e.g. 'one-six' is used in Life's English) and years, while a separate, more complex system incorporating powers of 16 is used for most other purposes (note that even more full/common version of expressing karamarea exist but we don't know enough to provide a reliable explanation of these).

In karamarea, the numbers 0 to 8 are named as follows: ::

    0 = nau
    1 = ore
    2 = noe
    3 = tre
    4 = pie
    5 = hie
    6 = kie
    7 = sjie
    8 = moe

16 is korr. The numbers above 8 and below 16 are formed as korrki(number) where korr means 16, ki means subtract, and (number) is the difference between the number and 16. Numbers are base16, and numbers above 16 are represented as the multiple of 16 directly higher than that number, and s. The only commonly used identifiers that exist are 0-8, 16, and some powers of 16, so numbers that involve digits from 9 to 15 require using a minus.

Generally, smaller numbers are created like this (using the number 30 as an example): ::

    no          2x
      ko        16 (rr are left out)
        ki      minus
          noe   2

``rr`` used to be used in numbers above 16 too but as the language developed, most people now leave out the rr if they are talking about numbers above 16 (in fact, some people leave it out altogether).

Also note that the e is left out for all other than the last digit. Since this sometimes causes hard-to-pronounce words, the digits form into other pronounciations: ::

    ore  => o
    noe  => no
    tre  => ta
    pie  => pi
    hie  => hi
    kie  => ki
    sjie => sji
    moe  => mo

A demonstration for larger numbers within the standard/full karamarea method will be done using the number 1000: ::

    1000 = 3E8 = 3, 14, 8

As karamarea has no numbers for 9 to F (9 to 15), illegal numbers like the 14 above are written by adding 1 to the unit before, and flipping the number itself. ``E`` on its own would go from ``14`` to ``1, -2`` (16-2), or ``korr`` ``ki`` ``noe`` (which in turn gets shortened to (o)kokinoe). So, ``3, E, 8`` would turn into ``3+1, -2, 8``. ::

    pi (4)    x hana (16^2)
    kino (-2) x korr (16)
    moe (8)

    4    x 16^2   = 1024
    (-2) x 16     = -32
    8             = 8
    1024 - 32 + 8 = 1000

    The rr (in korr) and na (in hana) can be left out, so:
    1000 = piha-kinoko-moe (full-number pronounciation)

    (Optionally, it can be pronounced as pihana-kinokorr-moe, to not cause confusion.)

----

As an example for the digit-by-digit method, this big number: ``728349`` will be used to demonstrate.

It makes sense to convert it to hexadecimal to make it a bit easier to see what we are doing: ``B1D1D`` or ``11, 1, 13, 1, 13``.

(Due to the fact that this method converts each digit separately as opposed to the entire number, the method for creating identifiers for 9 to F will simply handle the digit on its own.)

Now it needs to be converted into simple digit-by-digit karamarea (usually this would involve identifiers to show what digit you're on, but it's not required so they are left out here for simplicity): ::

    11  1  13  1  13

    No identifiers for B/11 exist, so it needs to be created:
    16    -   5    = 11 so
    korr  ki  hie  = 11
    The rr and e are left out, so kokihi = 11

    No identifiers for D/13 exist, so it needs to be created:
    16    -   3    = 13 so
    korr  ki  tre  = 13
    The rr and e are left out, and tre forms into ta, so kokita = 13

    11     1 13     1 13
    kokihi o kokita o kokitre

    728349 = kokihiokokitaokokitre (digit-by-digit pronounciation)

    (Some also leave out the koki and replace it with ki or i:
    kihiokitaokitre, or ihioitaoitre)

This means: ::

    1000 (full karamarea)           = piha-kinoko-moe
    1000 (digit-by-digit karamarea) = ta-kokino-moe

    1126 (full karamarea)           = piha-kiko-kie
    1126 (digit-by-digit karamarea) = pi-ki-kie

    1500 (full karamarea)           = kiha-kinoko-kipie
    1500 (digit-by-digit karamarea) = hi-kokita-kokipie

    etc.

Nau (na) is often used when there's a 0 in the number: 771 (3, 0, 3) would be tanatre, or when you simply say there's 0 of something (nau). Due to the fact that ki (minus) clashes with ki (6) unless at the end of a number, some have opted to use ka for 6 instead but this never really lifted off. Sometimes ko can be added after the o and no for base-16s and up, but not everyone does this. These differences are quite common for Synapsian.
