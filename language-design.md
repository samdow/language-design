_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates 
are:

   + Something you agreed with / resonates with your own experience
   + Something you disagree with
   + Something that is interesting, a new idea or perspective you'd like to remember
   + Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**
> "These stereotypes come about because programmers confuse their strong views about 
> languages with their views about the users of the languages. Consider, for instance, 
> this anonymous Reddit comment: “Node.js is not popular because of its non-blocking features. 
> It is popular because now dumb javascript devs can write server code. Earlier they had to 
> learn real languages like Perl/Java/Python etc. to do that.
> Our commenter assumes that using JavaScript, as opposed to a “real” language, is a sign of 
> incapacity. But in technical terms, JavaScript, Perl, and Python are fairly similar (they are
> all interpreted, dynamically typed, multi-paradigm languages). The only difference is that 
> our commenter has ideas about who uses each language–and about the languages that “real 
> programmers” use"
[Yang and Rabkin, 2015].

This is quite true to both of our experiences. People stereotype languages based on the users,
for example, in the article, it is mentioned that Python and Ruby are considered "girly." Both of
these are used a lot in web development. Web development tends to have a large UI and design
component, which causes some people to assume web development is "girlier," which they equate to
strong creativity. On the other hand, C or C++ are seen as manly because it does not have the
creative elements, and are often used to solve back-end problems, or find the "right" answer.
In this way, C and C++ programmers are considered objective in their search for the solution,
while web development and UI are seen as much more subjective. This gendered differentiation
hurts everyone who does not conform to these stereotypes.

> "PL/I has not grown much. It is, for the most part, just as it was when it first came
> out. It may be that this is just from lack of use. The flip side is that the lack of use may
> have two causes. Number one: PL/I was not designed to grow—it was designed to be all
> things to all who program right from the start. Number two: for its time, it started out
> large. No one knew all of PL/I; some said that no one could know all of PL/I"
[Steele, 1998].

This contrasts with the ideas that we discussed in class, specifically that languages cycle
through developing into a DSL, then into a general purpose language, and then back and through
the cycle. PL/I was designed to not grow, which is a different philosophy from the other
languages. It would be interesting to discover what drove the design philosophy for PL/I because
it is such a large, immutable language.

> "A language design can no longer be a thing. It must be a pattern—a pattern for growth—a 
> pattern for growing the pattern for defining the patterns that programmers can use for 
> their real work and their main goal"
[Steele, 1998].

By thinking of language as a pattern, Steele turns the focus from the programmer to the user.
By understanding the pattern, users can expand the language, which Steele calls "a pattern for
growth." At the very least, users feel like they are contributing to an ongoing project as
opposed to using the results of a finished project. As a bonus, user feedback and suggestions 
can facilitate a language's growth.

---
**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**
A well-designed language can grow into your project. If you have an idea, a well-designed 
language will have a way to help you achieve that vision, while a 
poorly-designed language forces you to significantly change your idea to adapt to what the
language can accomplish. One thing we disagree on is whether a well-designed language must 
always have a large, helpful community. Sam thinks that such a community can help languages 
grow since they should please the users. But Tiffany thinks that a large community only 
reflects how widespread a language is. For example, JavaScript has a large community, but 
many people claim it is poorly designed. 

On the other hand, the community can be an indicator of how well or poorly designed a language is. 
Tiffany found an article named ["The Python documentation is bad, and you should feel bad"](http://cryto.net/~joepie91/blog/2013/02/19/the-python-documentation-is-bad-and-you-should-feel-bad/). 
According to the article, while the Python community is rather large, it does encourage a 
"Just read the source" mentality over meaningful documentation (and the author continues on  
saying how bad Python's documentation is). Although Python can grow, its user base encourages 
poor practices, especially telling people to look at poor documentation instead of helping them 
with their specific problems. With these users controlling the online feedback to Python, 
we cannot expect Python to grow into an easy-to-read, easy-to-learn, and well-documented language, 
which are signs of a good language design.

---

**Question**

How do the themes of _Growing a Language_ relate to the "sound lab" we did this week?

**Response**
Steele discusses the importance of programmers building "a working vocabulary" and a working grammar
to go along with it. In the "sound lab" we did, we focused on restructuring the solution code so
it was easier to read and understand, even for a non-programmer. In doing this, we built a working
vocabulary because it was clearer how everything fit together.


---
 
**Question**


In what way is an API a language? 

**Response**
The notion of "when in doubt, leave it out" is very linked to DSLs and languages in general 
[Bloch, 2006]. In terms of DSLs, we discussed in class how DSLs should support the 
bare minimum required to run the programs they want to run. Otherwise, they risk 
becoming a general purpose language and losing the specificity of a DSL. Additionally, in 
English, students are taught to be concise and focus on one topic. Similarly, APIs
need to leave out anything that takes focus away from its main purpose.

---

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**
The greyscale post offers four options for functions that produce shades of grey. At
the end, it includes a poll that asks readers to vote on the most intuitive one
and also encourages users to leave a comment justifying their opinions [Verou, 2014].
This shows that API design is very influenced by user feedback and is very concerned
with how intuitive their functions are. Although some of the comments are not
constructive, the comments section allows for a large set of users to give 
quick feedback. In this way, a blog post is the best medium to help the API design
process because it allows for a large user base to give feedback, hopefully
leading to improvements in the API.

This particular example also emphasizes how there might not be a correct answer to some 
problems. Clearly there are many differing views in the comments, and even the final result 
might not "feel right" to some users. But at least there is some documentation explaining why 
someone would name the greyscale in a particular way.

---

**Question**

The Yang and Rabkin article talks mainly about general-purpose languages. In 
what ways do the themes apply to the study and creation of DSLs?

**Response**
DSLs develop their own hierarchy because of the wide range of uses for DSLs, in
some ways even more pronounced than the hierarchy in general-purpose languages
discussed in Yang and Rabkin. Some DSLs are made for people who have limited or
no programming experience. It's easy to stereotype these languages as easier and
lesser programming languages than some more intense DSLs that are difficult to learn 
without extensive programming experience. This develops a hierarchy amongst DSLs, 
where the languages that require more programming knowledge are considered objectively 
better than those that are made for artists, web developers, and other less technical users.
Instead of choosing the best language for a project, programmers may be attached
to a DSL.

Moreover, if DSLs are internal, they carry the stereotypes of their host language. 
For instance, if people think Python is "for noobs" then the internal DSL in Python
would also be "for noobs" [Yang and Rabkin, 2015].

---

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other 
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:


> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
[[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**
We believe that there should be a balance in designing programming languages
between natural language and structured technical terms.

The reason we cannot go to a full natural language is because there are so many
grammars to the same language. For instance, in English, one stereotype is that
a person from the South says "Y'all" while a person from the North says "You guys."
Both words mean the same thing, and there are millions of variations of this,
especially for a language as widespread as English.
Additionally, one word can mean different things in different contexts. For
example, in England, a rubber is an eraser while, in American slang, a rubber
is a condom. This leads to confusion between humans who speak the same language,
so it is extremely difficult to expect an artificial machine to understand the nuances.

On the other hand, Pavlus' article explains the problems with too many
technical terms. He mentions the steep learning curve involved with Perl and
how it creates a very selective community of those can program [Pavlus, 2012].

In the design of a DSL, we would want structured natural language, similar to
what we were talking about in the sound lab. In that example, we chose to move
to object oriented programming because it is closer to reading natural language.
It reads as a noun (the object) doing verbs in order (the first method listed
is the first one that is called). However, it must still have the shape
of object.method(). This way, method calls fall into a certain pattern, while
still allowing for them to read like a sentence.

---

**Question**

Briefly describe how you split up the work for this assignment.

**Response**
We read all the articles separately and came together to write the responses.
Both of us talked about our ideas before writing each response. Sam typed up
the responses, while Tiffany focused on the wording of responses and the big
picture ideas we wanted to get across.

Tiffany also proofreaded and added to some responses on her own.


---
