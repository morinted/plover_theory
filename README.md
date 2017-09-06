# Plover Theory: Learn Stenography

### What is Stenography?

Stenography is the fastest way to input text. Court reporters have used machine stenography since the early 1900s to take down spoken word in realtime.

Nowadays, stenography is used for:

* live TV captioning
* realtime transcription of conferences and lectures
* court reporting, especially in high profile cases where accuracy and turnaround time are important
* coding, writing prose, chatting online, and other indirect places you would use a keyboard
* a fun hobby

This book is part of the [Open Steno Project](http://openstenoproject.org), which seeks to get stenography into everyone's hands through free learning materials, drilling tools, cheap hardware, and free software.

### What is Plover?

[Plover](http://openstenoproject.org/plover) is an open source application that lets you control your computer with a steno machine. It also lets you use an NKRO \(n-key rollover\) keyboard _as a steno machine_. It brings the barrier of entry for steno hardware from thousands of dollars to potentially free, as many gamers already own an NKRO keyboard.

Thanks to Plover, there are hundreds of people who have self-taught themselves stenography with free resources online and now use stenography for different purposes at different speeds. You don't need to reach 225WPM, the certified court reporter speed in the United States, to get a speed and ergonomics boost over a conventional keyboard.

The purpose of this book is to teach you Plover's steno theory. There are many different theories you can use and learn, but Plover comes with a perfectly competent dictionary for free that evolves over time. Plover theory is built on top of the personal dictionary of Mirabai Knight, the inventor of Plover

### What is a Theory?

Before I take a stab at defining what a theory is, let's take a step back and look at some of the history of stenography. Stenography is the art and study of shorthand. The Open Steno Project and Plover are specifically concerned with _machine stenography_, also known as machine shorthand. You might have heard of pen shorthand before, like Gregg, Pitman, or Teeline. Journalists and court reporters used to use pen shorthand to take notes at high speeds, and then would later convert from shorthand to text. There were many different systems that were used, particularly in different countries. Gregg was popular in the States, Pitman and Teeline in the UK. These different systems tend to look very different from each other, but they are all based in phonetics, because English is a much simpler language sounded-out than written.

Machine shorthand came about in the early 1900s, created by Ward Stone Ireland. Using many of the same principles as written shorthand, Ireland was able to create a machine that could produce shorthand notes at a greater speed than written shorthand. Machine stenography compared with written shorthand is similar to how typing is faster than writing. The layout that Ward Stone Ireland came up with is still used today in modern stenography. Like Gregg and Pitman, there are other "systems" used world-wide, as Ireland's was very focused on English. There are different layouts \(sometimes just a renaming of letters on the stenotype\) for different languages, and there are also different physical machines. The UK has the [Palantype](http://www.openstenoproject.org/palantype/tutorial/2016/08/21/learn-palantype.html) as well as the [Velotype](http://www.velotype.com/en/), which are very different from Ireland's steno machine.

None of these things are _theories_, though. A theory refers to the different ways one could use a given system. In Gregg shorthand writing, there are different editions, revisions, or ways to write certain words and sounds. These could be thought of as different theories, where [Centennial](https://www.amazon.com/Gregg-Shorthand-College-Book-Centennial/dp/0070736618) differs from the later [Simplified](https://www.amazon.com/GREGG-Shorthand-Manual-Simplified/dp/0070245487) theory. Writers of each would have a hard time making sense of each other's notes, despite them both writing "Gregg". In the same way, stenography has many, many different theories.

The fact is, with most modern steno theories \(called realtime theories, a dated term referring to the fact that stenographers now write on computers instantly instead of manually transcribing from their notes\), the foundations are mostly the same. All popular theories write most of the alphabet the same way, and might differ on how to write less common letters like Z. The real power of theories, and what people will spend hours debating over, is their balance between consistency and speed. On one end, you have a theory like [Phoenix](http://www.phoenixtheory.com/). Phoenix is a theory that takes the phonetic aspect of stenography very seriously, and sacrifices some speed in order to have a very predictable, memorable, and consistent theory. Writers of Phoenix rarely encounter a word they can't figure out how to write with their theory, at the cost of sometimes having to use more keys and time to write words and phrases. On the total opposite of the spectrum, you have theories like [Magnum Steno](http://www.magnumsteno.com/). Magnum throws consistency out in exchange for a large amount of memorization. The trade-off? Writing really, really quickly and often pumping out two, three, and four word phrases where other theories get one word at a time. The big con is that if you get stuck on a word you can't figure out, you might have to take time to look it up in the dictionary.

Phoenix and Magnum were born out of moving away from the center; a decent mix of phonetic theory with some spelling disambiguators, plus a good dose of phrasing and shortcuts to still maintain fast writing. This middle-ground theory came first, and is called [StenEd](http://www.stened.com/). StenEd is still the most popular theory nowadays, mainly because of momentum and market share, as well as the fact that teachers tend to teach what they themselves have learned.

### What is Plover Theory?

Plover theory, the subject of this book, is most similar to StenEd, but probably leans ever-so-slightly more towards the Magnum side of things in terms of trying to write quickly. The big difference between Plover and the other theories is that it's 100% free and doesn't require purchasing a learning materials or the dictionary itself. The first time you open Plover, the dictionary is already loaded. Plain and simple.

Theories manifest, often, as a dictionary and a textbook. The textbook explains the mapping from sounds and spelling to machine shorthand, and the dictionary is where all the mappings are stored. Changing the theory you write with is as simple as loading the dictionary into Plover, and likewise you can move Plover's dictionary into paid steno software if that is ever necessary. Dictionaries tend to be in the range of 100,000 to 500,000 mappings, in order to cover the entire English language. Don't worry, you don't need to memorize that much, as most of these entries are just realization of the rules covered in the textbook.

In addition to your theory dictionary, you, as a stenographer, will always be defining your own personal theory and building your own dictionary. Everybody's mind works slightly differently and sometimes you'll have a mnemonic or perspective that suits you better than what your theory provides. It's encouraged to build on top of a theory and come up with better ways to write words and add new vocabulary. With Plover's dictionary, you can [suggest changes and improvements](https://github.com/openstenoproject/plover/issues/400).

As mentioned earlier, the theories are still quite similar at the core. Many students find it easy enough to switch to a different theory even after a year of learning. Don't beat yourself up trying to choose a theory, just start learning stenography and you'll organically find what does and doesn't work for you. Many Plover users have switched to Magnum and Phoenix, but most do stick with Plover's own theory as it's very capable.

### Why This Book?

I'm a self-taught hobbyist stenographer. I learned everything I know from the Internet, including websites like [QWERTYSteno](http://QWERTYSteno.com), [Learn Plover!](https://sites.google.com/site/ploverdoc/home), as well as many other [learning resources](https://github.com/openstenoproject/plover/wiki/Learning-Stenography). However, the lessons I found online felt dense and lacked real-world utility for me. I read through Learn Plover! three or four times, trying to grasp every subtle line, but while it teaches core theory very well, it just dumps on a bunch of briefs for common words, punctuation, and affixes as an afterthought. You don't end up writing coherent sentences in Learn Plover! until the end of the book. In this book, you are writing sentences as soon as you learn your first set of keys.

My goal is to make a textbook that can be read cover to cover, with or without steno hardware or Plover running, that teaches you everything from where the keys are on the steno keyboard, to basic theory and word forming, to real-world briefs, to advanced techniques to help you squeeze the most out of stenography.

The book is incomplete; I'm writing it and reworking it all the time. I'm not an author, I'm a software developer, so feedback and corrections are appreciated, though I might not get back to you as I'm reworking the format of the lessons over and over again. You can mail me at [morinted@gmail.com](mailto:morinted@gmail.com)

I'm writing this entire book exclusively using stenography.

All the best,

Ted Morin

