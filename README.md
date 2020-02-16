# On Self-Replicating Sets

### John. Q Geometer

### 2020

### [link to edit page](pageeditor.html)

## 1. Computer Science and the Theory of Self-Replication

   Throughout the history of modern computing machines, people have contemplated the idea self-replicating machines.  At the dawn of the information age, John Von Neumann in particular devoted thought to the subject, creating a blueprint that people continue to use both for understanding hypothetical self replicating machines and for understanding the architecture of existing computing machines.  At the same time, Alan Turing developed a similar toy model for how generalized computing machines work, which is taught in basic computer science classes to this day.  We will not delve very deeply into these models, but will instead present a very crude sketch of them in order to discuss the assumptions made by computer scientists in the models they build to understand their world.  

The Turing model of a computer consists of an infinite tape of 1's and 0's along with a machine to both read and change the state of the numbers in the tape.  The string of numbers describes instructions for the machine, which follows those instructions by moving the tape back and forth and changing numbers from one state to another.  Turing was able to show that this toy model of an abstract computing machine could be proven mathematically to be equivalent to any other abstract toy model of any other kind of computer, including the complex machines built today(hence the continued use of this model in teaching and scholarship).  This is considered to be one of the most important results in theoretical computer science.

Before discussing this model's limitations we must say a word about the nature of scientific models.  When we investigate a thing using the scientific method we have in principle the entirety of science knowledge to call on, built up from a vast number of models in different fields and sub-fields.  For example, if we are presented with a rock to analyze, a physicist might ignore everything but the crystal structure of some prominent material in the rock and bring the modern understanding of crystals to bear on it.  The micro-biologist will only be interested in the aspects of the rock that interact with the organisms on the surface, while the ecologist will be interested in that but primarily how the rock regulates the flow of water through the ecosystem of which it is a part.  As scientists we may agree that models of surface chemistry for microbes, models of how atoms arrange in crystals, and how water flows through rocky soil are all "good science", but in any given context the model we choose to focus on depends on that context.  

It is our assertion that while the model of Turing and his contemporaries is not wrong, that it is deeply misleading because in most cases it does not describe the most relevant aspects of the machines we call "computers".  Computers do, of course, compute.  That computation is described by the mathematics of computation.  They also create heat, described by thermodynamics, and are we therefore to call them heaters?  They keep time with extremely fast clocks, do we simply call them clocks?  No.  But what actually are they? What is the model for a modern computer which is most useful when trying to understand them?  In this era, in the year 2020, the most useful model for a computer is the one that describes how they have totally changed all aspects of global society in a relatively short time.  For this we must expand the models available, and in particular we must focus on a specific shortcoming not just of mid 20th century computer scientists, but of most scientists in the "modern" era, namely our refusal to put ourselves and the societies of which we are a part into the systems which we study.  In some abstract sense, one can argue that we put ourselves into the models with the role of the observer in quantum mechanics for instance.  But we do not put the role of something like university politics into the models, even though these forces clearly influence the science we use and hence the conclusions we draw.  It is the assertion of this paper that this blindness has become so critical in the understanding of computers as to be wrong in a way that has real world consequences.   

So what is the problem with a Turing machine?  If we look at it naively as a physical thing, not as a mathematical toy, we see a number of things that are not realistic, such as the infinite tape and the lack of any meaningful human readable input or output.  But these are typical of useful scientific models: while the tape is understood to never be really infinite, the results you can get from the machine with "such a large memory that it doesn't matter" and infinite mostly don't matter, so our toy model still works.  But the critical flaw of the machine which gives us an incorrect understanding of how computers function in society is that it has no origin, no purpose, and no destiny.  Who built this machine? Why? How long can it run before it breaks?  What happens when it breaks?  When it ceases to function, what replaces it and why?  

We now live in a world where a large fraction of the computing machines that exist live on a trajectory from a mine to a landfill of less than 2 years.  During this brief journey from mine to landfill, they are mostly used for communication, and much of that communication is marketing information the primary purpose of which is to lead to further consumption of similar machines.  That is, *in their current state* the *primary* action of these machines is rapid replication.  

This is the reason we must shift the *primary* scientific model of computing machines from the Turing model to a more biological understanding.  If we seek to study a new species of life that is taking over an ecosystem rapidly, we will always try to focus on the models that allow us to understand that phenomenon because it is what affects outcome.  If a farmer asked us to evaluate a new crop blight and we came back with a deep study of how carbon chemistry works because all life contains carbon they would be very disappointed in the results even if they are technically correct.  Likewise if we are to deal with the explosive changes to our physical world caused by computing machines we must focus on the means of replication.  We will give an analysis of these means in the next section.  However before doing that we must turn to the history of self-replication as an idea in mainstream computer science.  

There are two main intellectual threads in this story: cellular automata and self-replicating robots.  Interestingly, it is the former of these that actually have a vast experimental component and the latter which is entirely theoretical.  Cellular automata are in some sense a generalization of the Turing model: they are sets of rules for multidimensional(usually 2 dimensional) grids of numbers, generally 1's and 0's, which follow some set of rules.  These systems are simulated on real computers, and as time advances in a program we can see fascinating patterns of what appear to be naturally oscillating structures moving around in a visual display of dots on a two dimensional canvas.  If the rules are created correctly, these structures can be made to replicate themselves.  The literature on cellular automata is vast and complex and continues to be a very active field. Nonetheless, it suffers the same flaw as the Turing model: it exists in a vacuum, with an assumed infinite time, and no reason to exist(at least this reason is not part of the theoretical framework used to describe them), no origin and no ultimate destiny when it breaks.  There is beautiful pure math to be found in these systems, but no illumination of how computers function as machines that copy themselves.  
 
The second thread of self-replicating machines is the study of theoretical "robots that build robots".  This has attracted some truly wild speculation.  What is generally imagined is a totally automated system without human intervention in which a computer controls robots that mine minerals which are used to build both more computers and more robots.  This is then imagined to be so self-contained that it can be used to expand out into the universe outside of Earth, eventually consuming all things into this vast, automated, technical ecosystem which does not need any living thing to grow.  Technologists have imagined these systems, then promised that they can be a fantastical utopia of free things, but also warned that they can destroy the world by consuming everything in site.  For decades, theorists have written very detailed descriptions of such systems, delving into metallurgy, synthetic chemistry and the like to try to prove that such a thing can be built.  Most recently, the work of K. Eric Drexler and Ralph Merkle in the 1990s pointed to a system like this built from precise positioning of atoms in matter--essentially treating physical matter as just another Turing machine.  These theorists constructed very detailed imaginary worlds where atomically precise machines manipulate atoms to both compute and create, replicating themselves on a global scale.  Perhaps their day will come at some future time and such machines will be built, but right now these models are of no help in understanding technology as we find it today.  The rest of this paper is devoted to developing both a theory of self replication in modern technological society and in actually *using* this theory, just as the pioneers of modern computer science used Turing's model early on, to build new things based on the new model.  


## 2. Self-Replication in Human society

   First a word on self-replication in biological systems that exist outside of human society.  "Natural" biological organisms never replicate themselves in a vacuum.  On Earth as we find it today, all living systems replicate as part of larger ecosystems, and the parameters of those ecosystems are *fundamental* to the overall replication.  No animal can live long enough to reproduce without a constant flow of oxygen from plants needed for respiration.  Conversely plants need the carbon dioxide we produce in order to live long enough to replicate.  No one would dispute that a tree is a self-replicating thing, and yet trees only replicate in collaboration with a large number of other organisms, generally other plants, fungi, animals, all working in concert to make the overall forest system replicate itself, of which the trees are only a part.  What we find in spite of this, however, is that scientists outside of biology put much more restrictive rules on self-replication, saying a thing does not "really" replicate itself if it replicates as part of a larger system. Hence the flaw in computer models: if humans replicate machines, those machines are not called "self-replicating" because for the overly restrictive definition of the "self" of the machine they do not spontaneously replicate.  But this type of isolated spontaneous replication does not exists in nature even for purely biological systems, so applying it to systems outside of biology will give results that are at odds with how the biological world works.  Again, we must distinguish between models that are "right" and models that describe the primary characteristic of a system under study.

In the pre-industrial societies, *all* technology is self-replicating.  Historically, people make technology using the materials found in their environment, generally from other organisms like trees(wood) and animals(bone) or found objects of which there is a plentiful supply. People then reproduce and teach the system of constructing such technology to the next generation, along with enough understanding of that technology that the young can in turn pass along the information when they age and are passing it along to yet another generation.  This type of self-replicating technological system can exist in stable dynamic equilibrium with existing ecosystems.  Trees can grow, be converted to boats to hunt in, which lead to cooking technology to cook the animals killed in the hunt, and trees and game animals can then re-grow as future generations replicate their technology.  

If we take this broader view of self-replication we don't even need to restrict ourselves to humans to see self-replicating technology.  The beaver dam self-replicates quite easily and indeed before the rise of modern society one can imagine the dam itself as a self-replicating entity which uses the beaver as a vector, but which transforms the landscape vastly in excess of what one might imagine possible for a single small animal.  To make sense of a landscape transformed by beavers it does not make sense to either study just beavers or just dams, we much consider the self-replicating set of dam-and-beaver as a single system.  The same is true with human technology.

Moving into the very early reaches of our history as we learn it today based on written records, the next self-replicating systems are religions and empires.  A religious text is perhaps one of the best prototypes for self-replicating technology which can shed light on the current state of affairs.  Religious texts such as the Torah or the Koran describe both a world view which gives people a "why" to what they do which includes the replication of that text.  They also include the description of "how" to replicate the text, building up complex structures of education which teach the next generation of humans what they need to know to keep replicating the next down through the generations.  The other main replicating structure is that of the military bureaucratic empire.  An empire replicates by expanding to incorporate more and more people into the actions of further replication.  This is generally done by force, which can keep growing by taking more land for more mining resources and also more people to continue to gain power to continue to expand, consuming other systems and turning them all into that one central imperial system.  

The entireity of human written history can be looked at through the lens of these self-replicating systems, where the means of replication is the primary descriptor of the systems.  The history of what used to be called "Christiandom" can be seen entirely through this light.  The Torah was replicated by Jews for thousands of years, and was limited in its replication by Jews' only replicating it to other Jews, so the growth was limited by the biological reproduction of the people who did the replication.  Then, when Christianity appeared, the same text was suddenly being replicated by the people of one of the vastest military empires every built, Rome.  Ultimately this replication consumed Rome and became the Holy Roman Empire which among other things was a vast replication machine for the scripture.  Then, due to technological advancements it became possible to replicate that scripture mechanically in bulk with the printing press, and we see another explosion of change in that world where this press and how it replicated religious scripture caused some very radical change.  As Western capitalism developed, the King James version of the Bible, printed in bulk on mechanical presses defined the beliefs of the military empires that then went on to conquer the globe(singling out the British Empire, followed by the American as the most powerful of the lot).  Nothing in our world today makes any sense without this story of evolving self-replication.  

So now this brings us at last to the discussion at hand: self-replication in regards to modern computer technology.  How do computers replicate?  Just as an analysis of beaver dam replication requires understanding the trees from which sticks are harvested and the rivers which feed the beaver ponds, this analysis must include externalities that are ignored by theorists such as investors and marketing.  Modern computers exist as creations of a combination of mass market consumerism, venture capital investment, and government research and development mostly focused on the military.  Every company that makes computer hardware and software today is the creation of a very specific process whereby an entrepreneur pitches a company to investors, who in turn pitch their fund to larger institutional funds like pensions.  After they get funding, they grow using a very specific type of worker, the modern tech worker fully indoctrinated in a certain culture.  That growth is made possible by a system of mass media that transmits the information to consume the products to the masses outside of "tech".  Those masses of people both put money into the products of this creation process and also put investment capital into the financial system that funds the venture capital that creates all this.  Nominally all this is enabled by the "money" system which used to be based entirely on mining of minerals, but is now based on some complex system of faith more loosely based on mining.  The computer systems which out-evolve their competitors are the ones that replicate the fastest.  They are the ones that convince people to consume more and faster, and put more money and time into the system.  The venture capitalist David Horowitz has explicitly said that in the future they are building everyone will either be forced to obey the media on these systems or will become one of the people building them.  And indeed this is the logic of the self-replicating machine. People like David Horowitz have to exist in order for the machines to out-replicate other machines.

This picture presented here is of course a vast over-simplification and the product of a fairly brief and superficial analysis.  It is not the purpose of this paper to create a full model of replication of modern "tech", but rather to convince the reader that *such a model is needed*, in the hopes that people will develop more accurate models that we can use to try to gain some control over this system and ultimately over our lives.  

In summary, the simplest model for computers that I think we should consider now is not that of the Turing machine but of the advertising machine which exists for the sole purpose of convincing people to consume more advertising machines.  In some cases the role of the machine is to present PowerPoint to investors, the use of the computer to train the workforce to build the technology, in other cases it's an article in Wired about some new technology and in many cases it is just direct advertising to the consumer.  But in all cases the primary characteristic which determines form is replication.  This is why evolution of machines has favored more and more of the machine being screen, with the highest possible pixel density and color contrast, rather than maximal computation power.  Pixels are what sell pixels.  

All that said, it is the assertion of this paper that the existing technological system has built a type of media(the Web) which allows for self-replication in a more benign and sustainable way, based on different mathematical and philosophical assumptions than those made by the architects of the current system.  Before setting forth this philosophical system we must examine this technological substrate and try to grasp the true power of it as it has already been built, ignoring 


  - culture in pre-industrial societies
  - religion: scripture and culture and broader society structures
  - a more accurate description of "tech" which is a more powerful descriptor for what we call "computers" than the Turing machine, including: venture capital,media, global finance,central banks, government intervention, education, culture, geography, mining(with extreme specificity), landfill, metals processing, military force, mining, oil, global materials transport
  - viral information vs. complex replicating systems

## 3. The Power of the Open Web

  What is the Web?  The Web is not the Internet.  The Internet is a network of computers that connects almost all computers in the world, both physically and with some software protocols. This network traces its origins to the network of military and academic(but military-funded) computers that emerged from ARPA back before the modern commercial Internet, going back to the end of the 1960s.  The Internet can in principle be used to exchange any information and treats information in the same abstract sense as in the models of theoretical computer science discussed above.   

The World Wide Web was the conceptual creation of one person: Tim Berners Lee.  It was initially created as a directory for the large science institution Lee worked for.  The Web works great on the Internet and the Internet is what made it huge, but it is not the same thing.  The Web is a system for encoding information for and by humans to communicate with other humans.  It includes human readable code designed to create universal documents which link to each other and can contain images  of all kinds and text in all languages, creating a sort of universal document in a universal language in which all of humanity can communicate.  While the modern Web is commercialized and increasingly not open to all users by default, this is a choice we have made that can be un-made. In principle any computer *can* be both a web server and a web browser.  If we call the "open web" the collection of all web files which are openly viewable to anyone connected to the Network, the open web can in theory physically grow to include every computer in existence using the existing physical telecommunications network.

Let us now estimate the size of this potential Open Web network.  We suppose that given the multiple billions of smart phones, laptops, servers in server farms, embedded systems, supercomputers, etc., that the total number of potential web servers is of order 100 per person.  We then round human world population up to 10 billion, and estimate that there are 1 trillion total potential servers on the Open Web.  Given that even a modest cell phone has a few gigabytes, but many servers and deep storage computers have terabytes, we can round up a little and say the average server can host 10 gigabytes of data.  If a file like this one is 100 kilobytes to 1 megabyte, let's round to 1 meg and say there are 10,000 documents like this one(they could in theory all be math papers) for each server.  So the total number of documents per person is 1,000,000.  But we as a society *share* these documents, so in some sense what we all have is not 1 million but 1 million times 10 billion or 10 quadrillion documents.  The informational universe in which we construct this new mathematics consists of this network of 10 quadrillion linked documents.

This universe of information exists on web servers which can in general be made to run code that edits and replicates the documents.  Thus *every* document in this universe of information can self-replicate and be edited in situ.  If this is all on the Open Web with code that can be edited by anyone on the Web, all users can constantly edit all documents, so potentially we have 10 billion people all simultaneously editing 10 quadrillion files all of which are able to instantly self-replicate from any node on the Network to any other Node.  This vast network effect can create power in the same what that billions of brain cells with massive interconnection, creating a document of greater power than any that has ever been possible before.  The power of such an open system will be so vast that it will make no sense to have any private data.  Without any property on the Open Web, things can replicate freely, and the increased value will be so great that it will consume private property online.  This evolution will be physical as the value to the physical caretaker of a physical web server becomes greater to participate in the Open Web than to keep it in the commercial web.  

The power of a fully self-replicating and evolving Open Web on this scale is that documents can describe the replication of *physical* things, and the replication of the documents can include replication of the things.  If things we use in our lives are replicated rather than purchased or mined, it changes the basic assumptions about what value is.  Note that like "set", "thing" is used in a maximally general sense to include things like "a feeling of awe at the largeness of a tree" or "the tendency of cats with white fur to cause a change in the appearance of black clothing".  The word "thing" is used here as a placeholder for *anything* which human language can be made to describe or point to.

In order to build these documents we must first define the idea of what exactly a self-replicating document is, and how it fits into more general concepts of self-replication.  To that end we will take an excursion into the math known as set theory.

If these documents are used to document all the things we interact with in our lives such as technology, culture, economics, philosophical ideas, art, etc, the space in which we can build a self-replicating Universe of Things which represent all things we can desire, making the Open Web a medium for exchange of self-replicating things based on our desires...


  - add up mobile phones, laptops, desktops, server farms and there are easily 10 potential web servers per person for a 10 billion person population.  Each machine can be assumed to be able to host 10 gigabytes, or 100 gigabytes per person.  If we consider the space of files like this one that can fit in under 1 megabyte or 0.001 gigabytes, there can be 100,000 text files like this one *for each person on Earth*.
  - Given that there could be easily this universe of open servers all running the same basic code, we can build a collection of 1 quadrillion(10 billion times 100 thousand) self-replicating documents like this one. 
  - If these documents are used to document all the things we interact with in our lives such as technology, culture, economics, philosophical ideas, art, etc, the space in which we can build a self-replicating Universe of Things which represent all things we can desire, making the Open Web a medium for exchange of self-replicating things based on our desires...
  - evaluation of complexity of fully networked collection of evolving documents, comparison to brain of neurons

  
## 4. Self Replicating Sets

### Motivation and definitions

[Set theory](https://en.wikipedia.org/wiki/Set_theory), is the mathematical study of sets.   Sets are, to quote Wikpedia, ["...collections of objects"](https://en.wikipedia.org/wiki/Set_theory).  The idea of a set as a collection of "objects" considers the idea of the "object" at a level of generality perhaps shocking to non-mathematicians.  "Object" here can mean *anything*.  Mathematicians generally mean by "any object" any object which a mathematician might talk about.  However in principle it can be anything that anyone might talk about(as we seek to generalize these ideas beyond mathematics).  For the purpose of this work we well define a generalized object to be anything which human language can possibly describe.  Any word, symbol, or collection of words or symbols which point to something--that something is an "object".  And a "set" is just a collection of such general objects.  

The notion of a generalized object is of course familiar to modern computer programmers who use the idea of "object oriented programming" to create generalized objects which are used to build linguistic handles in human language on computer programs.  Thus a modern programmer might define something abstract like "shopping-cart" for a e-commerce website, and then that object will have properties like "list of objects" and "total price".  We choose to take the path taken by foundational mathematics and have our basic concept from which all other concepts will be built be the collection of objects(which are themselves objects) be the fundamental idea.

In order to understand the motivation of this work it is necessary to trace very briefly the history of set theory.  Through the end of the 19th and beginning of the 20th century there was a vast effort by some of the most brilliant mathematicians in the world to construct a universal mathematical theory base on the theory of sets and symbolic logic.  Axioms were proposed, used to prove things, argued about, and re-written.  The goal was to base *all of mathematics* on the axioms of set theory, and to go from there to a universal system of truth in which statements may all be proven to be true or false.  

People like Bertrand Russel pointed out that such systems can create paradoxes that make it impossible to create a self-consistent system of logic/truth/math.  This paradox can be summarized by considering the "list of lists that do not list themselves".  The list defined here is a list of lists.  Is this list on itself?  If it is, it cannot be by the definition of itself.  If it is not, it must be by the same reason.  In spite of having publicly stated this paradox, Russel and his co-author Alfred North Whitehead wrote what is now considered a seminal work in mathematics *Principa Mathematica*(not to be confused with a book by Isaac Newton of almost the same name), which attempted to create such a universal bases of mathematics.  While the achievements of 20th century set theory, logic and analysis are fantastic and useful, they ultimately failed in their goals, and this was proven mathematically by Kurt Goedel in 1931.  


In the post-Goedel world we *should* take for granted that no universal logical construction can be built which defines truth and falsehood without contradiction.  Goedel's proof presented a fork in the road intellectually.  We could have used this as the sign to go back through mathematics, accept contradiction as part of life, and build a math based on desired outcomes.  In some sense this is what society did by mostly ignoring the work of most post war mathematics(with some very narrow exceptions like number theory for cryptography).  While professional mathematicians took the opposite fork, building increasingly complex systems based on each other, where a vast tower of ideas linked by formal logic build up from the axiomatic set theory of the early 1900s to create a bridge to nowhere.  The sole purpose of most mathematical concepts and theory today are to advance the career of working mathematicians.  We forget, both outside and inside mathematics, that people used to believe ideas in math actually *mattered*.  We also forget that mathematics has for thousands of years been one of the most powerful tools the human mind has for understanding and interacting with our world.


[naive set theory](https://en.wikipedia.org/wiki/Naive_set_theory).  sets as collections of abstract objects without the ZF axioms. sets are denoted by curly braces



The work of Russel and Whitehead. The conclusions of Goedel and the post Goedel world of mathematics.  A fork in the road: instead of building more obscure castles in the sky after Goedel we could have turned to the world and accepted that while formal math cannot describe the Universe an absolute sense that we can apply it directly to the Universe as we *experience it* through language, not as some external "true" Universe.   

Having proved that a universal truth machine cannot exist, we may now abandon the project of early 20th century mathematicians such as Russel and Whitehead and proceed to reconstruct axioms of set theory based on a *desired outcome*.  This system will not be judged on its ability to prove theorems, eliminate logical contradictions, or get tenure for math professors.  It will be judged *only* on its ability to improve the human condition.  It is time, finally, after almost a full century, to inherit the true legacy of Goedel.


self replicating sets always have an externality.  The degrees of freedom of that externality determines the degrees of freedom of the set containing it.  The more general an element is the more degrees of freedom it has.  




Right now all of humanity is locked into one giant self-replicating set which has as elements all of industrial society.  The purpose of this work is to create a set theory which enables people to construct sets which create the maximum amount of human freedom.  To that end, we seek to make sets have elements that are defined as generally as possible and also which always have the *desires* of the creator of the set as an element.  When we move forward replicating these sets in the new society we build, each act of replication involves also replicating this desire.  We therefore only replicate that which transmits a desire that we consent to and agree with for some reason.  

A self-replicating document is an example of a self-replicating set.  This document is created as itself a self-replicating document according to the prototype we propose for the whole system.  We now set forth to define the set which is this paper in theoretical terms, then to describe all the subsets which together make for a self-replicating set which can be evolved into other self-replicating sets.


### This Set

The prototype self-replicating set we define in this paper is itself this paper, and is formally defined as follows:

<pre>
On Self Replicating Sets[This Paper] = 
{
  The desire of the author to describe self-replicating sets,
  A description of self-replicating sets,
  The means to replicate this set
}
</pre>

The first of these will always be a part of the system of sets we are constructing here: desire.  All sets are defined with an element which maintains the desire of the author/creator/artist, and this is maintained as sets replicate to ensure that sets only replicate with the intent of someone.  Furthermore, we separate the thing being replicated from the means to replicate it.  Elements are generally themselves sets which are broken down into more finely defined elements. This paper is part of the "description", but what formally is "this paper"? We seek to define it as a set, or a collection of elements contained in "description of self-replicating sets".  This includes the following elements:

<pre>
Description = 
{
  narrative structure,
  definitions,
  digital text document,
  pdf document,
  references
}
</pre>


Now again we break off the replication methods from the thing being replicated.  Replication is to happen on the Open Web. That is, it must have self-contained and self-replicating code that can copy itself from any web server to any other, and be edited after being copied, then copied again from the new instance so that the information is totally decentralized and evolves naturally as it's copied and edited.  We also need this document to include instructions in human language(English for now) on how to replicate the whole system, by either buying a domain and setting up paid web hosting or building their own physically local web server to server the files.  This document will contain that information.  Furthermore, the replicator set must include the other media that are used to replicate the whole set, including content on commercial social media.

<pre>
Replication = 
{
  code replication,
  server replication,
  pdf replication,
  in-person pitches and classes and discussions,
  media: email, post cards, posters, signs, commercial social media,
  manuscript editing to evolve and fork the Document
}
</pre>


### Code and replication of code

- replicator.php
- dna.txt
- saver.php
- loader.php
- README.md
- editor.php
- index.html
- pageeditor.html

## Server replication

 - buy domain, get hosting, copy
 - raspberry pi
 - server farm
 - localhost


### Pdf document

 - print page to pdf
 - pandoc+latex
 - word(☠)
 
### Other Media

 - postcards
    - mailed
    - given away in person
 - printouts
 - posters
 - signs 
 - commercial social media
 - emails
 - elevator pitch

### Evolution and forking

 - edit, change replicator, copy, repeat
 - working with github
 - using pastebin
 - forking and the power of infinite forks

## 5. Conclusions

We create sets that all contain the means to replicate.  Sets have a "primary element" which is the object of desire of the person replicating the set.  The basic prototype for a set is to have three elements: desire, the object of desire, and the means to replicate the whole set.  Sets generally have subsets, and the elements of those sets are also considered to be elements of the superset.  Basic axioms are not the same as ZFC, and must be investigated in further research.  

*Language is how the mind parses reality.*

*From each according to their desire, to each according to their desire.*

private property: we have no need of that hypothesis

  By building a universe of self replicating things based on the desire of the author of the documents we can build a universe for our minds to live in 

The use of directing evolution with desire to create better sets. 

We examine self-replication in capitalism: how does money replicate, how does property replicate, how do mined materials replicate?  These systems have more degrees of freedom than some that came before but effectively infinitely fewer than what will come after: self-replicating sets. 

The goal of the technological complete set, with evolution to guide to that goal.  How robots built from trash can be integrated into the universe of self replicating sets to build closed loops where externalities are "sun, earth, water, trash" and nothing more.  No money, no mining, no property.  Everything is physical, everything is fractal, everything is recursive.  Look at the insects, look at the fungi, language is how the mind parses reality.

When we create self-replicating sets based on our desires we can create the ultimate power of the human mind over the Universe.  This is possible in the information as since the Universe as we experience it is made not from the products of reductionist science and math but from words, symbols and ideas in human language.  After we recognize that our worlds are primarily defined by language, and that math and symbols are a fundamental approach to manipulating this reality, we can build a power that is effectively a form of Magick: the ability to change the world according to our desires. 


This whole document/set is a specific instance of a more general "thing" which includes a more complex networking system and a language for building up symbols.  This "thing" is so general as to be not useful by itself, which is why this paper needed to be written.  The next self-replicating "thing" to be released into the Open Web will be Action Geometry, which is a system of self-replicating symbols.  Action Geometry in turn is a specific instance of Geometron, a much more general meta-language for building symbols on the Open Web.  Again, Geometron is too general to be of direct use, and so we create the specific instance of Action Geometry[AG] and build that out into a collection of media, both commercial and free, both physical and digital, which can replicate and spread these ideas while also providing tangible value(hence creating the desire for replication without which replication is impossible).  Even Action Geometry is too general to have a set replicate rapidly enough to be relevant.  For that we focus the entirety of this system of information into just the notion of the self-replicating symbol.   Symbol itself is an extremely general concept.   What will therefor be presented in the next work is an extension of Leibniz's work on what he called the *characteristica universalis* or universal symbolic language.  The full language will involve a mixture of all the techniques presented here, but to aid replication it will be focused down into single symbol sets which replicate with the minimum possible number of components and the maximum number of degrees of freedom.


A complete set is defined as a set which provides all human needs.  This is subjective and constantly evolving.  Our task is to create self-replicating sets which we have the power to evolve in such a way that they tend toward becoming complete.  Unlike the creators of axiomatic set theory of the last century, we accept that this is not a precisely defined goal which can be proven to have been achieved or failed.  Rather, it is a goal and a means to work toward that goal.  On the other hand, this is no longer a goal restricted to increasing the fame of working mathematicians but one of improving the lives of not only every human on this planet but of all other living things whose fate are now bound to ours by the global technological system.


## 6. References

[1]  Von Neumann
[2]  Merkle
[3]  Drexler
[4]  penrose
[5]  dawkins
[6]  reggia
[7]  turing...but mostly wikipedia

