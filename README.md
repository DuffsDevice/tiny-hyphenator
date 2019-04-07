# TINY-HYPHENATOR

My quick shot at *Word Hyphenation* a.k.a *Syllable Boundary Detection*. Use this library to achieve efficient and hopefully exact word hyphenations. :wink:

Currently the only language supported is German (with a rather high percentage (95%) of correct hyphenations), but it should easily be adaptable for other languages.
This library spans ~370 lines of C++ code.

At the moment there is no documentation, please refer to the comments in the code, they should hopefully be quite helpful.
Apart from that, you should find a sample that illustrates the usage of **tiny-hyphenator**.
The algorithm is not based on any published one and works without a dictionary.
It's is written in plain C++ and is tested under GCC 4.7, 4.8 and 4.9.
