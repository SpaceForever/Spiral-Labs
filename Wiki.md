# Wiki

## Host: Foam

## Questions
- Space: @rajlego which terms do you want to use for the two minds? Feeling Brain and Thinking Brain? Higher Mind and Primative Mind? Rational Brain and Emotional Brain?

## Consistency

## Always Sharing
- Ask on Foam
- Wait for Raj's answer

- Try out other random extensions?
- Ask in uofb?
- Auto Commit (https://marketplace.visualstudio.com/items?itemName=zeitnergmbh.auto-git)

## Problems
- Incremental Writing
  - Write a proposal
    - [[Priorities]]
    - Intervals
    - 

- Private vs Public







I reccomend using Obsidian Publish as something that is quick and effective. Can ralley obsidian to push collaboration to the top of their priority list. Until then we can screenshare on one person doing it, which can be me. 


- Obsidian publish
- mediawiki
- supermemo.wiki


woz talks about wikis here in email between us:

I think wikis are the answer to all collective brainwork. e-mail is more like signaling: reminder, creative burst, link, etc. if it does not get hammered into a wiki, it is just chat [btw: this line is important, and shows how your e-mail, signals an important problem that, in the future, should be somewhere included in the semantic net of a wiki]

# Importance
- Publishing
- ease of adding ideas
- ease of intervalling
- obsidian-level backlinking

Supermemo.guru - knowledge is assumed because everything is interlinked

[[obsidian + google docs]]
 

 



Notes with TiddlyWiki
Note taking systems seem to be the current productivity hype in the last months. It inspired me to change my system from journal-text-files-in-vim to a TiddlyWiki-Zettelkasten-inspired one. At 667 notes, I consider it a successful habit now. Here is how it looks today:

TiddlyWiki note taking

My approach is inspired by Zettelkasten which is currently popular. Maybe because of the book How to Take Smart Notes by Sönke Ahrens. I have not read it, but it gets mentioned a lot. Zettelkasten fans glorify Niklas Luhmann, a prolific sociologist. He wrote an impressive amount of books and attributes a lot of that to his Zettelkasten with 90000 notes.

Again, my approach is inspired by this Zettelkasten system but I don't claim it is true implementation. I haven't found a good definition and maybe there is not even a consensus. The reddit community has a wiki which describes the difference to other systems like this:

The Types of Notes you include within it. You may be used to writing by topic, or in a linear fashion. In Zettelkasten, the notes are ‘atomic’, making them useable in various categories or topics.
The way you write the notes. The focus is on making high-quality notes that are future-proof.
The emphasis on Linking notes/ideas together. Linking ties the notes together so they become more useful.
Here are my guidelines or at least the ones I follow in practice.

Note titles should be sentences rather than words
A note should describe a belief but not define a term. Thanks to Andy Matuschak, where I got this from. Here is an example:

victory comes from avoiding mistakes

You see the title at the top which is the atomic belief documented here. Then two short paragraphs arguing about this belief. Then two quotes on this topic. In the end, a short reference to a similar note although I should rework that so it fits better. At the bottom is also one backlink from another note titled Crossing the Chasm.

I do not create notes for single words or tags. For definitions there is Wikipedia. Here are a few more example titles:

Poker teaches valuable life lessons
predictions are hard
it's all about the right goals
obedience should be a result of trust
systems must be optimized as a whole
Link! Link! Link!
Whenever I create a new note I think extra about other notes to link to. Searching for keywords became a habit. The goal is increased serendipity later. Sometimes the same belief is confirmed by multiple books.

My user interface encourages short notes and thus hyperlinking. This is why I prefer it over Obsidian and other tools.

Andy Matuschak in this video uses Bear. Multiple notes side by side but all using the full screen height. He writes quite long notes and I believe partly because this UI suggests that.

In contrast, TiddlyWiki places notes vertically and thus suggests to keep them short. Short notes in turn encourage more hyperlinking.

A separate note for every book and article I read.
It makes references more terse and enables backtracing to all mentions. While reading, I add quotes to the note. Eventually, all the quotes are moved to other notes representing the beliefs independent of the publication. Those beliefs are where thoughts get mingled. In the screenshot, you see I'm currently reading Racing for the Bomb. The list with greek letters are backlinks, so many beliefs are extracted already and they reference the book.

No fear to add half-opinions.
My notes are not a clean collection. They are a messy hodge-podge and never final. This is an advantage of a digital solution compared to the physical notes of Luhmann. I can delete and rewrite easily. So I don't even try to make anything perfect.

One goal is serendipity by new associations. Restricting myself to beliefs I'm very confident about would have a negative effect. An opinion must be worked out over time.

I never allow myself to have an opinion on anything that I don’t know the other side’s argument better than they do. —Charlie Munger

Anyways, beliefs do not need to be true to work. The pragmatic theory of truth might sound weird, but here is an example: My readers probably agree that the belief "the Earth is flat" is wrong. However, if you are trying to score a goal in a soccer match, that belief works perfectly fine. The more accurate belief "Earth is round" would not be helpful.

Sometimes, I even add "false" notes. For example, I have a note "set unrealistic goals" which is contrary to what I belief in general. However, the note contains examples where it seems to work. Over time the note shall collect more influences until my tension is resolved. Maybe it only works in certain fields? Maybe it works by a side-effect (e.g. focus) which can be achieved more effectively?

The Zettelkasten system distinguishes between "literature" and "permanent" notes. Some say only permanent notes are stored in the Zettelkasten. Literature notes are made while reading something and are later used to create permanent notes from them. I don't see a point to differ in a digital system since storage space is no issue.

Journaling
Keeping a journal is worthwhile for some in its own. I never managed to keep this habit going for long. Now I mostly try to put current stuff into some context in belief-notes but sometimes it does not fit anywhere. So I appreciate that my software comes with a journal button which creates a new note with a timestamp as title. I even made it slightly bigger in mine as you can see in the screenshot on the right.

Sometimes I later expand the title with something topical, so I can identify it better when it turns up in a list of backlinks. As an example, in the screenshot, you can find "2020-09-28 23:26:26 promotion". It contains a quote from this article. Partly insightful observation and partly satirical hyperbole and I'm not sure how to file it. No links to anywhere, but maybe I will find it again via search in the future and link it with something appropriate.

How serendipity ensues
When I read through this discussion I found the thought "efficiency erodes resilience" worth noting down. I created a Zettel with this title and a link to the discussion.

Then I searched for other notes about efficiency. It came back with "competitions lowers efficiency" which is a snippet from this book review of mine.

As these two thought collided, I first considered a transitive relation "competition lowers efficiency which increases resilience". Then I realized that resilience and competition are actually quite the same. So both notes make kind of the same statement.

This is an interesting insight because it seems to be a valid argument against Deming. In his book lowering efficiency is always bad. However, increasing resilience would be good. I did not think of this when I read the book, so my notes helped to create this association. I did not think deeper about it. Maybe another trigger will bring me back with additional input.

TiddlyWiki
There are many possible tools to implement this system. I started with an empty TiddlyWiki which is a personal wiki software running in any web browser. For storage I made myself a little Python server which stores it in my SyncThing folder. SyncThing replicates it to my phone, where I can access it via Tiddloid. I added two plugins:

Relink, so when I change a title all references are updated instead of broken.
Stories out of Stroll because I like that two-column user interface.
TiddlyWiki does not show backlinks on a note. At least not prominently. If you click into info and references, the information is available. To fix that, I created a note with the following content and tagged it $:/tags/ViewTemplate.

<ol class="backlinks">
<$list filter="[all[current]backlinks[]sort[title]]" emptyMessage="">
<li><$link to={{!!title}}><$view field="title"/></$link></li>
</$list>
</ol>
TiddlyWiki is not perfect. For example, its markup language is custom instead of something standard like Markdown (there is a plugin for that though). Also, a browser text field is not really a great editor. At least, I'm very sure the technology is pretty future-proof and will still be useable in a few years.

I will not publish my notes. It might even be illegal to publish a few of the notes in there. I checked the screenshot a few times because I worry what I'm leaking here. By keeping it private, I can be more careless when entering information.

© 2020-10-04

Describing my note taking system inspired by Zettelkasten

Share page on
Twitter
Facebook
artikel (ältere) articles (older)
homepage friend blogs publications
portrait image
Andreas Zwinkau appreciates email to zwinkau@mailbox.org, if you have a comment.

You can get updates via Twitter @azwinkau.

search this site with DuckDuckGo
 

datenschutz

 




[//begin]: # "Autogenerated link references for markdown compatibility"
[Priorities]: priorities "Priorities"
[//end]: # "Autogenerated link references"