---
title: Ƶibcoin Frequently-Asked Questions
layout: minimal
---

# Ƶibcoin Frequently-Asked Questions

### Why not "mics" (pronounced "mikes") as a casual way of referring to microbitcoins?

Of prior proposals, that's the best – but still has problems. 

It requires the secondary spelling ("mike") to clarify pronounciation. There will be a natural tendency to abbreviate it with an 'm' – which risks confusion with 'millis', a very different unit. Using the proper metric abbreviation, µ ("mu"), then just makes things seem more arcane. Since it still references *micro-*, it still risks confusion with *milli-*, and still implies something that is tiny and perhaps invisible or ignorable. 

It may invite the questions, "Who's Mike? Is there a Mike Nakamoto, perhaps Satoshi's long-lost son, brother, or father?"

Comparatively, 'zib' or 'Z' can be unambiguously communicated, and used consistently across both formal software and casual conversation.

### Why not 'bits' to mean 'microbitcoins'?

People are already using the terms 'millibits' and 'microbits' as natural shortenings of 'millibitcoins' and 'microbitcoins', respectively. Using 'bit' to refer to the same thing as 'microbit' presents problems. 

Also, 'bit' already has an archaic meaning in money (1/8th of a dollar) and very current and prominent meanings within the Bitcoin system, as the binary digits and basic units of information in its hashes and protocol. Those kinds of bits represent information, are indivisible, and fit 8-to-a-byte, 16-to-a-word, etc. To the implementors of bitcoin, a phrase like "1000 bits" has a strong meaning, enough information to store a value up to 2^1000, and *not* a count of 1000 things-called-bits. (Such a count would fit into just 10 bits, since 1000 < 2^10.)

And if a 'bit' is 100 satoshi, then literally reading "bit-coin" would make one think of a "coin of 100 satoshi". But of course the unit "bitcoin" actually means a value 1 million times as large, 100,000,000 satoshi. 

So while 'bit' is catchy, it jumps into a semantic blender in relation to other key bitcoin concepts. It'd be hard to bootstrap as a term, and prone to misleading people for the entire duration of its use. ("What do you mean, my 256-bit private key? It should have thousands of bits in it!")

'Zib' was specifically contrived to match the compactness and general sound/lightness of 'bit', but without overloading the term with yet another contrasting meaning. While novel, it's about as easy to say or spell, and works better as a verb ("Could you please zib 10,000 to me?" compared to "Could you please bit 10,000 to me?"), because there's no comprehension-interference with the past-tense of "bite". ("He bit you 10,000 times? Did it leave marks?")

### What about the Bitcoin unit-abbreviation `XBT`, that's gaining momentum as a currency-code?

Zibcoin may be a better unit for quoting currency exchange rates, too, by avoiding deep-decimal values over certain expected quoting ranges. If needed, the currency-code `XZB` appears to be available.

----

(contribute more questions/answers via [zibcoin.org github project](https://github.com/gojomo/zibcoin.org))

