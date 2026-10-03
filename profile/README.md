## Typed Context Object

The purpose of a Typed Context Object is that *Context* has mathematical guarantees of certain the rules to be _invariant_, meaning that you can communicate a concept to many different systems, and what and how that concept is defined is not the task of a Context Object, the task of a Context Object is to measure and calibrate perspectives with a shared set of rules and measures. That way, you have a precise instrument with which you can calibrate your shared understanding of concepts as they effect decisions.

*Regret Uncertainty Unawareness* happens when a decision is affected by a property the Context Object captures, but the decision is unaware of the connection. For example, `What were my trades yesterday?` is simple, except for a stock broker who trades in the UK, office is in NY, data systems are in San Francisco, and client on whose behalf the trader is trading is in Singapore. Yesterday could literally be two different days, and a misinterpretation by the AI would be unnoticed, because it would return an answer, and there was no verification if a human and an LLM are intended and interpreting the same concept. This URI based approach, of representing a dynamic URI registered as changing state in an array is meant to efficiently capture reasoning processe so that you can efficiently create optimal training data, of compounding effects of context on decisions.

**Key Definitions:**
- *`OBSERVATRON:`* Think of it like a programmable smoke detector on software that can use both deterministic and probabilistic choices
- *`CONTEXT OBJECT:`* Meaning, Structure, and Environment are the three primary Context Facets, anchored to the Data Facet, which is the observed, or sensed signal that triggered a rule in an *intent-map*, or a simple instruction of what to look for, and what to do if it is observed.
- *`REGRET:`* A sub-optimal decision that is propagating in networks silently until the bill comes due.
- *`FAILURE:`* A known error that can be fixed in a pipeline
- *`UNCERTAINTY UNAWARENESS:`* Becase `yesterday` could be interpreted in multiple ways, and has no error in the return, anything downstream that trusts the info will be unaware whether it is right or wrong, and that is simply a propability given the possible choices which may or may not be mapped out.


observatron/
  |- context-object
      |-observe
        |-intent-map[] //every entry is an object with these two child objects
          |-triggers //what to sense
          |-rules //what to do, when a signal has been detected
        |-spikes[] // each observation spikes Context Facets
          |-Data //the anchor facet, what was sensed
          |-Structure //schema, constraints, validation, generator for simulators of environments and itself
          |-Environment //a message to the reader of this data, to help them with their deceision, if relevant
      |-reason
        |-reasoning-cards[]
          |-core[]
      |-decide
        |-essential[]
        |-inert[]
        |-governor[]
      |-trace[]

## Protocol
- `tcxp://` is a network address
- `!tcxp:/` is **NOT** a network address, but an **in-memory address**
- `@tcxp.get({position-start,position-end}) is a prefix to retrieve the character position in a URI, this is an operation against the **in-memory URI**
- `@tcxp.set({position-start,position-end,string}) is a prefix to edit the character position in a URI, an operation on the **in-memory URI String** allowing updates
- `@tcxp.match({string-1, string-2, result}) // this would result in the URI updating state so &string1=<string1>&string2=<string2>&result=<result>  ← this is what updates in real time in the URI to show state

## Resources
- [W3C Typed Context Protocol Community Group Python Notebook - tcxp:// Typed ConteXt Protocol](https://www.w3.org/community/typed-context-protocol/)
- [https://github.com/typed-context-protocol/charter](https://github.com/typed-context-protocol/charter)

