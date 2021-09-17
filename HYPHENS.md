# Hyphens

Hyphens are one of the most confusing parts of English grammar, and misuse of
hyphens is rampant. Of course, clarity is king, so ultimately, if a hyphen or
absence of a hyphen makes something clearer, that is the correct use of a
hyphen. However, hyphens exist to resolve ambiguity, and thus to aid in
parsing, so it's important to use them thoughtfully.

I won't provide an actual guide on using hyphens here. If you want one, I
highly recommend the Chicago Manual of Style, which enumerates every case in
common English usage. Rather, in this document, I will look at the underlying
logic behind hyphens. I believe that understanding the logic will help writers
to use hyphens intuitively, rather than haphazardly.

Note that I am not a linguist, but a computer scientist. This is not the
perspective of an expert on linguistics, but I believe it to be largely
correct. Hopefully, an outside perspective is easier to understand.

Hyphens are not dashes. Do not use hyphens as dashes. Look elsewhere for advice
on how to use dashes correctly.

## Classes of Hyphens

A major source of confusion in the use of hyphens is that hyphens actually
serve two roles in English.

People frequently misuse hyphens because they believe that certain phrases are
always hyphenated (or, conversely, are never hyphenated). But, this is
incorrect. Consider the phrase “the light-hearted girl”. This is a correct use
of a hyphen, and indicates that the girl was light of heart. The phrase “the
light hearted girl” refers to a girl who has a heart and doesn't weigh very
much.

On the other hand, the phrase “the girl was light hearted” is correct *without*
a hyphen. “The girl was light-hearted” is accepted by some style guides, but
the hyphen is certainly not needed. Why this inconsistency?

It's not inconsistency at all; rather, the hyphen is not being used here to
form a new word, but to disambiguate a surrounding phrase. “Light hearted girl”
is an adjective, an adjective, and a noun. A typical noun phrase has each
adjective describing the noun, so the natural reading of this phrase is that
both “light” and “hearted” are modifying “girl”. But, “light” is actually
modifying “heart”. In “the girl was light hearted”, there is no ambiguity,
since “is” phrases like this can't take a list of a adjectives without a
conjunction like “and”. There is nothing for “light” to modify *but* “hearted”.

Consider now the phrase “word-centric construction”. “Centric” isn't a word, so
“word centric construction” is simply meaningless; construction cannot be
“centric”, because “centric” doesn't mean anything. Instead, “centric” is a
*stem*, affixed to a word to change its meaning. Here, suffixing “centric” to
“word” produces an adjective meaning “centered around words”.

“The construction is word-centric” is correct, and “the construction is word
centric” is not. Here, the hyphen is not used to disambiguate anything, but to
construct a new word entirely.

“Light-hearted” is not a word; the hyphen here is just punctuation.
“Word-centric” is a word; the hyphen is used as part of word construction.

## Morphological Hyphen

Morphology is the study of word formation, and thus, morphological hyphens are
hyphens used to form new words.

Historically, morphological hyphens were used in an ad hoc manner. Words such
as “wildlife” arose through the ad hoc invention of the word “wild-life” from
the phrase “wild life”. This style of word formation has largely been
abandoned; in modern English, we're happy to skip the hyphenated phase
entirely, and invent conjoined words directly from their antecedent parts.
Some ad hoc hyphens remain in modern English. Use an ad hoc hyphen if it
appears in the dictionary.

Ad hoc hyphens are not the only form of morphological hyphens. Hyphens are also
used to join standard stems to words, such as “co-opt”. This use continues to
be common. In principal, this follows the same pattern: words are formed by
hyphenating stems to words, then eventually the hyphen disappears. In practice,
some words retain their hyphenated form indefinitely (such as “co-opt”) to aid
in pronunciation, and some words are abandoned before being fully synthesized.

Sometimes, morphological hyphens are inherited from distant affixes of stems.
For instance, in the word “long-hauler”, it is actually the stem “er” that
forces the hyphen. The word is to be read “(long haul)-er”, not “long
(hauler)”, so the hyphen is necessary to affix the “er” to the whole word. This
case can also arise while maintaining the hyphen on the stem, such as
“loan-word-centric”.

Some affixes happen to be identical in form and similar in meaning to words,
but don't confuse them. “Word-like” can never be spelled “word like”, because
“like” is a suffix in this context, not a word. On the other hand, “wordlike”
is probably acceptable and certainly clear.

One can always choose to use an ad hoc hyphen to invent a new word, even if it
doesn't follow modern conventions, such as “Spider-Man”™. However, overusing
such hyphens makes the writer look ignorant of how to use hyphens; don't write
a word with an ad hoc hyphen if you're not comfortable writing it with neither
a hyphen or a space. For instance, it is common to form the word “compile-time”
in works in programming languages, by analogy to “runtime”, and many authors
(including myself) add a phantom hyphen to “runtime” (“run-time”) by analogy to
“compile-time”. Since “compile-time” is a word (uses a morphological hyphen),
“at compile-time” is correct.

In addition, verb phrases are often conjoined into *nouns* using morphological
hyphens. This phenomenon will be discussed later.

## Punctuation Hyphen

The other use of hyphens is for punctuation. In this context, hyphens are
intended principally to disambiguate what word a descriptor describes.

Nouns are described by adjectives and sometimes nouns. Adjectives are described
by adverbs and rarely adjectives. Therefore, a list of adjectives followed by a
noun is unambiguous so long as the adjectives all describe the terminal noun,
and a list of adverbs followed by an adjective is unambiguous so long as the
adverbs all describe the terminal adjective.

Phrases of forms such as **adjective noun noun** are often ambiguous. The
natural reading of this phrase is with with adjective and first noun both
describing the second noun, as in “gradual type system”, and this reading does
not require any hyphens; it is normal for a list of descriptors to precede the
modified word. If the adjective describes the first noun, and the first noun
describes the second noun, then a hyphen is required (**adjective-noun noun**),
because otherwise the adjective would pair with the second noun, as in
“real-time task”. If the first noun describes the second noun, and the
adjective describes the new concept created by the pairing of these two nouns,
then it is *sometimes* acceptable to hyphenate the nouns to emphasize this, but
not standard.

Hyphens are often elided when the ambiguity they would resolve in word pairing
doesn't actually change the meaning of the phrase. For instance, “operating
system kernel” could be written as “operating-system kernel” to clarify that
what is meant is the kernel of an operating system, but “operating (system
kernel)” has the same meaning as “(operating system) kernel”, so this
disambiguation isn't actually needed.

It is misunderstanding of punctuation hyphens that most often leads to misuse
of hyphens. Punctuation hyphens are purely contextual, and do not form new
words. It is correct to write “real-time task”, but if “real time” doesn't form
a compound descriptor, then the hyphen is incorrect: “tasks run in real time”,
*not* “tasks run in real-time”.

## Other Adjoined Word Misuse

Verb phrases are almost never compounded into a single verb, but frequently
compounded into a single *noun*. This noun usually goes through the same phases
of synthesis as any other morphological hyphens: first they are hyphenated,
then they become one word. It is very common to misuse the words “login”
(“log-in”), “signin” (“sign-in”), and their converses (“logoff” and “signoff”).
These words are *nouns*, not verbs. “Log in using your login” is correct (if
tautological). “Login using your log in” is incorrect in both uses.

Similarly, words that have been formed by ad hoc hyphens have a more
restrictive meaning than their unhyphenated forms. “Run-time” (“runtime”) is a
part of a computing system, not a duration of time. It can refer to the
*period* of time during which that part of the system is in operation, but not
the *duration* of that time. “The run-time was five seconds” is incorrect,
because “run-time” does not have that meaning.

Morphological hyphens (and their eventual unhyphenated forms) form new words,
and so can drift in meaning; punctuation hyphens are just punctuation, and so
cannot.
