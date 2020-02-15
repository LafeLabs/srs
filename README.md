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

The entirity of human written history can be looked at through the lens of these self-replicating systems, where the means of replication is the primary descriptor of the systems.  The history of what used to be called "Christiandom" can be seen entirely through this light.  The Torah was replicated by Jews for thousands of years, and was limited in its replication by Jews' only replicating it to other Jews, so the growth was limited by the biological reproduction of the people who did the replication.  Then, when Christianity appeared, the same text was suddenly being replicated by the people of one of the vastest military empires every built, Rome.  Ultimately this replication consumed Rome and became the Holy Roman Empire which among other things was a vast replication machine for the scripture.  Then, due to technological advancements it became possible to replicate that scripture mechanically in bulk with the printing press, and we see another explosion of change in that world where this press and how it replicated religious scripture caused some very radical change.  As Western capitalism developed, the King James version of the Bible, printed in bulk on mechanical presses defined the beliefs of the military empires that then went on to conquer the globe(singling out the British Empire, followed by the American as the most powerful of the lot).  Nothing in our world today makes any sense without this story of evolving self-replication.  


  - culture in pre-industrial societies
  - religion: scripture and culture and broader society structures
  - a more accurate description of "tech" which is a more powerful descriptor for what we call "computers" than the Turing machine, including: venture capital,media, global finance,central banks, government intervention, education, culture, geography, mining(with extreme specificity), landfill, metals processing, military force, mining, oil, global materials transport
  - viral information vs. complex replicating systems

## 3. The Power of the Open Web

  - add up mobile phones, laptops, desktops, server farms and there are easily 10 potential web servers per person for a 10 billion person population.  Each machine can be assumed to be able to host 10 gigabytes, or 100 gigabytes per person.  If we consider the space of files like this one that can fit in under 1 megabyte or 0.001 gigabytes, there can be 100,000 text files like this one *for each person on Earth*.
  - Given that there could be easily this universe of open servers all running the same basic code, we can build a collection of 1 quadrillion(10 billion times 100 thousand) self-replicating documents like this one. 
  - If these documents are used to document all the things we interact with in our lives such as technology, culture, economics, philosophical ideas, art, etc, the space in which we can build a self-replicating Universe of Things which represent all things we can desire, making the Open Web a medium for exchange of self-replicating things based on our desires...
  - evaluation of complexity of fully networked collection of evolving documents, comparison to brain of neurons

  

## 4. Self Replicating Sets

### Motivation and definitions

naive set theory.  sets as collections of abstract objects without the ZF axioms. sets are denoted by curly braces

self replicating sets always have an externality.  The degrees of freedom of that externality determines the degrees of freedom of the set containing it.  The more general an element is the more degrees of freedom it has.  

### This Set

<pre>
On Self Replicating Sets = 
{
  The desire of the author to describe self-replicating sets,
  A description of self-replicating sets,
  The means to replicate this set
}
</pre>

<pre>
Desire = 
{
  Desire to share beautiful mathematics with other people,
  Desire to create ideas which can empower people to change society with their will
}
</pre>

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

<pre>
Replication = 
{
  code replication,
  server replication,
  pdf replication,
  media: email, post cards, posters, signs, commercial social media,
  manuscript editing to evolve and fork the Document
}
</pre>


## 5. Implications

*Language is how the mind parses reality.*

*From each according to their desire, to each according to their desire.*

  By building a universe of self replicating things based on the desire of the author of the documents we can build a universe for our minds to live in 

The use of directing evolution with desire to create better sets. 

The goal of the technological complete set, with evolution to guide to that goal.  How robots built from trash can be integrated into the universe of self replicating sets to build closed loops where externalities are "sun, earth, water, trash" and nothing more.  No money, no mining, no property.  Everything is physical, everything is fractal, everything is recursive.  Look at the insects, look at the fungi, language is how the mind parses reality.

## 6. References

[1]  Von Neumann
[2]  Merkle
[3]  Drexler
[4]  penrose
[5]  dawkins
[6]  reggia
[7]  turing...but mostly wikipedia

