# Lexicon

* __Bit__: A boolean variable $$ b \in \{ 0, 1 \} $$. Represents the answer to a yes/no question.
* __Bit String__: A sequence of __Bits__ of arbitrary length $$ B^n := (b_k)_{k=0}^n , \  k \in \mathbb{N} $$.
* __Vulcan Set__: The set of all __Bit Strings__ of infinite length $$ \mathbb{V} := \{ B_0^{\infty}, B_1^{\infty}, \dots, B_{\infty}^{\infty} \} , \ B_i^{\infty} \neq B_j^{\infty} $$.
* __Information__: Anything that can be encoded into a __Bit String__.
* __Environment__: An __Object__ that is defined relative to a particular __Actor__. It is seperated from an __Actor__ by an __Actor Boundary__, and encompasses all content needed to process any relevant __Events__.
* __World__: Synonymous with __Environment__.
* __Actor__: An __Object__ that interacts with an __Environment__ through __Events__. The difference between an __Actor__ and an __Object__ lies in its relevancy to a particular __Event__ (__Actors__ being relevant). The interpretation of the __Event__ crystallizes what is considered an __Actor__.
* __Actor Boundary__: The surface that separates an __Actor__ from its __Environment__.
* __Event__: __Information__ that crosses the __Actor Boundary__.
* __Observation__: An __Event__ in which __Information__ enters an Agent.
* __Observation Space__: The set of all __Observations__ that a particular Agent may observe. All __Observations__ perceived by an Agent are sampled from its __Observation Space__.
* __Object__: A set of correlated __Observations__.
* __System__: An __Object__ composed of correlated member __Objects__.
* __Model__: A __System__ that represents another __System__. It can be assigned a truth value (measurement) which expresses the accuracy of the representation. Examples of __Models__ include maps, blueprints, simulations, mathematical models, beliefs and claims.
* __World State__: Given that the __Information__ in an __Environment__ may change with respect to some parameter (for example, time), __World State__ defines a static snapshot of the __Information__ within an __Environment__. In other words, a __World State__ is an __Environment__ where all __Information__ is held constant.
* __World Model__: An Agent's internal __Model__ of its __World__. 
* __Action__: An __Event__ in which __Information__ exits an Agent.
* __Action Space__: The set of all __Actions__ that a particular Agent may perform. All __Actions__ performed by an Agent are sampled from its __Action Space__.
* __Value__: An Agent's expression of preference between two __World States__. __Value__ may favour either __State__, or may reflect indifference. __Value__ is not intrinsic, and cannot be specified in the absence of an __Actor__.
* __Valuation__: The process of assigning a __Value__.
* [__Reasonable__/__Unreasonable__](Reasonable.md)
