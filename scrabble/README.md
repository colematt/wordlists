# Official Scrabble Word Lists

> The official Scrabble player's dictionary, known as OSPD, is widely available on the internet. There is also a list targetted at Scrabble players known as the Enable list. This has been explicitly placed in the public domain. The Enable list is much more comprehensive than OSPD; you can read the authors' comments if you are interested. We have left their comments exactly as found, so a couple of references (e.g. to SIGWORDS.LST) do not make sense in this context. Note that OSPD contains no words over 8 letters; one reason that the Enable list is so much larger is that it includes longer words (which are of course much less likely to be used in Scrabble).

-- [National Puzzlers' League Wiki](http://wiki.puzzlers.org/dokuwiki/doku.php?id=solving:wordlists:about:start#scrabble_tm_dictionaries)

## ENABLE
The Enhanced North American Benchmark LExicon (ENABLE) is the most carefully researched, and therefore the most authoritative word list and reference available for Scrabble™ players. The word list file itself retains the name WORD.LST, to retain compatibility with the WORDY utilities written for it. The word list is in plain ASCII format, unencrypted, and is placed in the Public Domain for anyone to use as they see fit. It is non-proprietary, free, and freely available for any legal use, and therefore it can truly function as standard and a benchmark for the Scrabble™ community.

The master word list in ENABLE, WORD.LST, is not the so-called TWL98, a proprietary word list prepared by an "official" dictionary committee, rather, it is an even more accurate and authoritative reference for the competitive and tournament Scrabble™ player. It has been updated to reflect the changes that will go into place as of January 1, 1998, so many "old friends", such as "vin" and "da" have now disappeared. The original WORD.LST contained 100,701 words, this enhanced version has over 172,000. This word list would not have been possible without the help of a number of people in the Scrabble™ community, most notably Alan Beale for his tireless research, and to them go my thanks.

Ample documentation for the claims of accuracy and authoritativeness of the ENABLE list is contained in the SUPP10.ZIP archive, particularly in the file DOOM_ENA.DOC. This file contains a detailed listing of the differences between the ENABLE list and the DOOM/TWL98 list, including sources and justifications for the additions and corrections.

The master word list, WORD.LST, contains all 70 of the MW10 "also called" words. These are the italicized entries in the MW10 hidden in definitions of other words with the notation "also called". An example of this is found in the entry for "streelight", wherein is the notation "also called streetlamp". Therefore, the word "streetlamp" belongs in the ENABLE WORD.LST. A complete list of these "also called" words, with appropriate cross-references, may be found in the ALSO.LST file in the SUPP10.ZIP archive. Note that the DOOM/TWL98 list opened this particular "can of worms" with the adoption of the word "starfruit", found in the definition of "carambola". Nevertheless, the DOOM/TWL98 list still includes only about half of these words.

In contrast to other word lists, the ENABLE list has not been crippled by being limited to words under an arbitrary length. The ENABLE list is eminently suitable for most word games, such as Anagrams and Clabbers, and for crossword puzzle solving, rather than just for Scrabble™. A great deal of research has gone into removing this limitation, however the list is much the better for it.

The file SIGWORD.LST is a list of the 500 words longer than 8 letters in WORD.LST that do not appear in the MW10, but do appear in other standard sources. These "signature words" distinguish this list from others. Of course, those wishing to may delete the SIGWORD.LST words from the WORD.LST in order to obtain a more "standardized" listing. This may be accomplished simply and quickly using the UNIX "comm" utility in the following manner:

comm -23 word.lst sigword.list > word.lst.new.
This will create the file "word.lst.new" with the signature words deleted. All you DOS and Windows™ users may, if you wish, edit the WORD.LST file manually to remove the SIGWORD.LST words (this should not take more than a few hours). It would also be fairly simple to write a utility to automatically accomplish this in any of the commonly used programming languages such as C, C++, Perl, sed, awk, or even, heaven forbid, Visual Basic™. This is left as an exercise for the reader.

The ENABLE master word list, WORD.LST, is herewith formally released into the Public Domain. Anyone is free to use it or distribute it in any manner they see fit. No fee or registration is required for its use nor are "contributions" solicited (if you feel you absolutely must contribute something for your own peace of mind, the authors of the ENABLE list ask that you make a donation on their behalf to your favorite charity). This word list is our gift to the Scrabble™ community, as an alternate to "official" word lists. Game designers may feel free to incorporate the WORD.LST into their games. Please mention the source and credit us as originators of the list. Note that if you, as a game designer, use the WORD.LST in your product, you may still copyright and protect your product, but you may *not* legally copyright or in any way restrict redistribution of the WORD.LST portion of your product. This *may* under law restrict your rights to restrict your users' rights, but that is only fair.

The accuracy of the WORD.LST is due, in great part, to the herculean efforts of Alan Beale. He has put in many hours of multi-dictionary research in checking conjugations, inflections, and obscure parts of speech of thousands of words. In every sense of the word, he is as much the father of the word list as anyone.

Ross Beresford (ross@bryson.demon.co.uk) has incorporated the WORD.LST from WORDY into his North American Scrabble™ version of his excellent TEA word list generation / analysis program. See his home page, http://www.bryson.demon.co.uk/, for word list info and more details of TEA.

WORD.LST (pronounced "word-dot-list") is now the generic term for the ASCII-format word file released into the Public Domain as a standard and a reference for crossword-type games. As laptop and palmtop computers become more common and affordable, it will be convenient to use the WORD.LST in conjunction with utilities such as SEARCH.EXE (part of the WORDY package) to adjudicate disputes in word game competitive play. The OSPD™ in its various versions and incarnations is not particularly well suited for this application as it is poorly organized, sometimes difficult to interpret, and clumsy to use (try locating the word PELVES in the printed OSPD, for example). Furthermore, the WORD.LST is free from corporate politics, scheming and conniving, committee wrangling, "politically correct" appeasement, compromising, greed motive, and all other such ***nonsense***. The WORD.LST is yours, word game players! Use it. Help keep it updated and corrected. Distribute it (you do *not* need permission to do so, but tell us about it)!

Scrabble and OSPD are trademarks owned by Milton Bradley, a division of Hasbro.

Windows and Visual Basic are a trademarks of the Microsoft Corporation.

WORDY is *not* copyrighted and is *not* a trademark. It may be found under 'W' in any dictionary, just as scrabble, the verb, may be found under 'S'. The make-believe word "hasbro" may be whimsically defined as "possessing a male sibling" (named Milton, I guess).

ENABLE is not a trademark. WORD.LST is not a trademark.

This whole trademark business has been taken to ridiculous extremes.

I would like to express my gratitude to Linus Thorvalds for making possible Linux, a UNIX operating system, without which all the work on the ENABLE list would scarcely have been possible. Linux, like other flavors of UNIX, contains, as "standard equipment", wonderful built-in text and list processing commands and utilities such as comm, diff, uniq, sed, awk, Perl, vi, and emacs. On a previous incarnation of WORD.LST, the best DOS sort program I could find (a shareware utility, as the DOS sort command choked on files longer than 64K) took a full 45 minutes to sort a 1 megabyte word list. This time around, the Linux sort command sorted the full 1.7 megabyte WORD.LST in about *10 seconds*. I am convinced that any serious word list processing requires a UNIX-like operating system and at at least a rudimentary grasp of programming.

Linux is *not* a trademark (this was the subject of a recent court battle).

Disclaimer: Neither I nor Alan Beale is in any way associated with the so-called "Official Dictionary Committee", nor with the NSA in any of its guises or avatars (i.e., neither the National Scrabble™ Association nor the National Security Agency). We did not and do not have access to the so-called TWL98, and the ENABLE list is not derivative from it. We do believe, however, the the ENABLE list is more thoroughly researched, more accurate, and therefore a more authoritative and generally useful replacement for the TWL98 list.

                                 M\Cooper
                                PO Box 237
                        St. David, AZ 85630-0237
              -------------------------------------------
                         thegrendel@theriver.com
              http://personal.riverusers.com/~thegrendel/