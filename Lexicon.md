# Lexicon

* __Bit__: A boolean variable $$ b \in \{ 0, 1 \} $$. Represents the answer to a yes/no question.
* __Bit String__: A sequence of __Bits__ of arbitrary length $$ B^n := (b_k)_{k=0}^n , \  k \in \mathbb{N} $$.
* __Vulcan Set__: The set of all __Bit Strings__ of infinite length $$ \mathbb{V} := \{ B_0^{\infty}, B_1^{\infty}, \dots, B_{\infty}^{\infty} \} , \ B_i^{\infty} \neq B_j^{\infty} $$.
* __Information__: Anything that can be encoded into a __Bit String__.
* __Environment__: __Information__ that is defined relative to a particular __Agent__. It is seperated from an __Agent__ by an __Agent Boundary__, and encompasses all content needed to process any relevant __Actions__ and __Observations__.
* __Agent__: A __System__ that interacts with an __Environment__. It can consume zero or more __Observations__, and perform zero or more __Actions__. The decision of which __Actions__ to perform is made based on the __Agent's__ beliefs.
* __Agent Boundary__: The surface that separates an __Agent__ from its __Environment__.
* __Observation__: __Information__ that crosses the __Agent Boundary__, entering the __Agent__.
* __Object__: A set of correlated __Observations__.
* __System__: An __Object__ composed of correlated member __Objects__.
* __Action__: __Information__ that crosses the __Agent Boundary__, exiting the __Agent__.
* [__Reasonable__/__Unreasonable__](Reasonable.md)
