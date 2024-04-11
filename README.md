# Sacred Harp in TEI

Mostly for learning TEI :)

Questions:

- Do we repeat title/author/composer in the metadata and in the text?
- Does having each song be a separate document make sense?
- How to say we normally don't want to attempt to syllable check choruses, but sometimes do? Ans: By adding a `met` attribution on chroruses we want to check
- What to do about Lenox's meter, which includes the chorus. Ans: It's not a chorus :)
- Best practice for numbering?
- Better to use numeric meters, or names, or some entity?
- How to enforce values of an attribute? (e.g., don't use "stanza", use "verse")
- I think I want to declare some sections of a `l` element as "interrupting". I think I can do this with `seg`
- What if I want to use author entities?
- How do I enforce a sub-schema? body/div=author,title,lg* eg?
