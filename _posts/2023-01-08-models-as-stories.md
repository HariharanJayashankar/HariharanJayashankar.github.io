---
tags: computation, story
---
# Models as Stories

> I'm not sure whether you will take this as a confession or a boast, but we are basically story tellers, creators of make-believe economic systems. - Robert Lucas in [What Economists Do](http://home.uchicago.edu/~vlima/courses/econ203/fall01/Lucas_wedo.pdf)

Look at an economic model which claims to describe human behavior and you'll be greeted with constrained maximization problems, utility levels of individuals, calculus and many more things which most people in the real world have only a vague recollection of from their high school maths coursework.

People don't actually compute stuff like their "first order conditions", but we think of utility maximization as simply being a story of what people do. It is *as if* people solve the maximization problem. This is the "models as stories" view. Its like a good work of science fiction teaching us something about human behavior.

I think this idea is pervasive across academic economics (Also see [Economic Fables]("https://archive.org/details/a5e6aa48-02ba-48e4-887f-1c100a532de8") by Rubenstein for example). 

But why even invoke this principle? Shouldn't we just be picking the model which the data suggests?

## The Data

An economy is a complex system and for whatever reason it doesn't seem keen on being well described by closed form formulas. When we do get neat looking approximations we usually run into identification issues. What do I mean by that? Without getting too technical here is the 
game of identification:

- I give you 5 models to simulate data from (nothing magical about the number 5 here)
- You choose one of these models without telling me and simulate data from that model and draw 2 relevant figures (nothing magical about 2 either)
- Based on the 2 figures you give me I need to recognize which of the 5 models you chose

If I can reliably tell you which of the models the data was generated from the problem is deemed as identified. 

If we think of nature as the one choosing which model to simulate the real world with you might see how this identification process is relevant to applying models to the real world. In brief: we want *one* model which is consistent with real world data. If we have multiple models consistent with the real world then we don't know which one is true.

(And if we have no models that are consistent then we are in a really bad spot but usually that doesn't happen. Some person usually comes up with *some* way to explain the data.)

## Restrictions

This is where I believe the "models as stories" view fits in in my view. It basically filters out useless models on step 1 of the identification process so that we end up with fewer models that are consistent with the data.

I don't think you'll get a natural scientist to say that their models are just stories, but there are ideas that are core to scientists which captures the spirit of "models as stories":
- Models are always wrong but are useful in the right setting. Newtonian physics is *wrong* fundamentally in that it isn't a 100% accurate description of reality, Einstein's relativity does better in this regard (orders of magnitude better). But that does not mean Newtonian physics is useless - it is useful given the right context. Similar to how a story is a useful lesson given a particular setting. 
- Scientists famously look for beauty in their models. As Poincare said: "The Scientist does not study nature because it is useful to do so. He studies it because he takes pleasure in it, and he takes pleasure in it because it is beautiful". And off the bat that seems inconsistent with a "truth finding mission" of science but it may not necessarily be. We may find theories beautiful due some way in which it identifies something true but in a way we can't quite articulate. [^3]

[^3]: Hermann Weyl is quoted as having said "My work always tried to unite the true with the beautiful, when I had to choose one or the other, I usually chose the beautiful." An example Weyl gave was his gauge theory of gravitation, which he had worked out in his *Raum-Zeit-Matarie*.  Apparently Weyl became convinced that this theory was not true as a theory of gravitation but still it was so beautiful he did not wish to abandon it. Much later it did turn out that Weyl's instinct was right after all, when the formalism of gauge invariance was incorporated into quantum electrodynamics.[^1] 

So a "models as stories" view can be summarized as the two above points - being useful in the right settings, and being aesthetic.[^2]

[^2]: The first point might seem to intersect with the identification step but it actually precedes it, before testing models against the data we must think about which models are appropriate to the setting at hand  independent of what the data says.

# Stories and data

So ideally the two conditions listed above should reduce the number of models we consider and then going back to the identifcation problem we should be able identify more easily which model generates the data (the 5 models in the first step would now become 3 for example).

My view is that this also doesn't pose enough restrictions for the problem we have at hand.
Physics models have an incredibly high degree of accuracy for reasons I'm not sure of Newtonian theory is deemed unsatisfactory to explain the motion of mercury because the slow revolution of the orbit as a whole at a rate which is in excess of the Newtonian prediction by *42 seconds of arc per century* [^1]. This level of accuracy can only be dreamt of in economic theory today. As a result physics may be able to more successfully filter out useless models at the identification stage compared to economics and hence needs fewer restrictions to be able to choose the right models. 

[^1]: Taken from S Chandrasekhar's [Truth and Beauty - Aesthetics and Motivations in Science]("https://press.uchicago.edu/ucp/books/book/chicago/T/bo4432943.html"), from the essay *The Scientist*)

I'm not smart enough to figure out what the path forward is and it is unclear whether we need a "solution" in the first place. As I see it we have some options:

- We just continue as is and wait for our models to get better. It may be that even though our models aren't as great as they could be right now, they will get better in the future and more models will be filtered out in the identification step
- We add more restrictions to the models-as-stories view but depending on your appetite you may not be able to swallow more restrictions
- We look to a different set of restrictions entirely although I'm not sure how these will look.
