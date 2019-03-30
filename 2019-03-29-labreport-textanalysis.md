---
layout: post
title: "Text Analysis"
subheadline: "lab report "
categories:
    - classprep
author: Maura Intemann
comments: false
---

In one of the exciting tales featured in *The Thrilling Adventures of Lovelace and Babbage*, Marian Evans (aka George Elliot) gets caught up with the two inventors, her manuscript serving as a sacrifice to the fictionalized "Analytical Engine." Marian looks on, horrified, as the machine destroys her work as it translates it into data. Ada tries to comfort her, to convince her of the incredible uses of the data, saying: 

>"Despair not! Your words are not destroyed! On the contrary, they are shedding their earthly form! They have become transcendent! They have become data! Liberated from the static shell of the material, transliterated to the purely symbological , sublimated into a state entirely new! It can be filed, indexed, converted, replicated, searched, shared, shuffled, linked, mixed, recombined, archived, analyticated...resurected!" (192)
>

When symbolisms from "the human world," as Ada puts it, are translated into the languge "the natural world," or mathematics, we can start to look at those works of literature in a deeper, quantifiable way. 

Even though the Analytical Machine never came to be, in the 21th century, we *can* turn stories into data. Using R, we can mine works on Project Gutenberg, where thousands of classic books are available online for free.  

This line of code downloads all of Jane Austen's works from Project Gutenberg. 

![](https://i.imgur.com/P7Cf9cz.png)

And by running this line of code, we can begin to break down the text into data by isolating the words and getting rid of the filler -- common words like "the" and "and."

![](https://i.imgur.com/TBL7MmG.png)

Here is a table that orders the words in all of Jane Austen's works on Project Gutenberg by frequency. 

![](https://i.imgur.com/Y2gBNxt.png)

You can also plot this data in tables. These representations range from the uninteresting to the enlightening. For example, here are tables that show word frequencies in each book.

![](https://i.imgur.com/wsHt7nl.png)

They're all very similar. But this one shows the actual frequent, significant words and how many times they appear in each novel. 

![](https://i.imgur.com/S1uLX0D.png)

What can we do with all this information? Having this data can help researchers to compare works across the archive in a more quantifiable way, and can help scholars find new meaning in old works. Just looking at some of the most frequent words in Jane Austen novels, like "miss," "lady," "dear," and "sir," can help us evaluate common themes of Austen's books, like gender and relationships between men and women. 

Above all, technology like this allows us to do work that simply would not be possible for a human being. Contraints like time and inaccuracy can be virtually done away with. 

A recent [Vox Video](https://www.vox.com/videos/2019/3/20/18274427/cat-always-lands-on-feet-marey-falling) explained a different kind of technology called chronophotography, a technique invented by scientist Étienne-Jules Marey in 1894. The process allows multiple stages of motion to be photographed onto a single glass plate. 

![](https://i.imgur.com/XTJXT2o.png)

Marta Braun, a professor at Ryerson University, described how this breakthrough changed the way we analyze the world. 
 
>"What does photography do for science? It records something and makes it permanent, so you can analyze it later, or so you could share it.  But what Marey did, was show something that they eye could not possibly see, ever."

Just as chronophotography allowed scientists to see and record things they never could with the human eye, R and text analysis technology allow scholars to make connections they never before could. Technology like this lets us look under the hood, so to speak, giving us a glance into processes and trends that where once mysteries. 

As we translate text into data, we gain deeper understandings of language, how it lives and grows. But through this process, it's hard not to take in the horrified view of Marian Evans, as her work is mutated from its original state. What do we miss when we take literature and make it data? Perhaps the information is decontextualized, removed from its author and its original cultural moment. Perhaps also we remove a kind fo unquantifiable human factor that simply cannot be translated.





 
