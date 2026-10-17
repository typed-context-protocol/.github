# Typed Context Protocol, a W3C Community Group

**Draft of Specification (in progress, not yet reported)**
- [https://typed-context-protocol.github.io/specification/](https://typed-context-protocol.github.io/specification/)

**W3C Community Group Home Page**
- [W3C Typed Context Protocol Community Group](https://www.w3.org/community/typed-context-protocol/)

**Charter**:
- [https://github.com/typed-context-protocol/charter](https://github.com/typed-context-protocol/charter)

**Notebook Example**
- [Python notebook code examples](https://github.com/typed-context-protocol/charter/blob/main/typed-context-protocol-1.ipynb)

## Introducing the Typed Context Object

The purpose of a Typed Context Object is that *Context* has mathematical guarantees of certain the rules to be _invariant_, meaning that you can communicate a concept to many different systems, and what and how that concept is defined is not the task of a Context Object, the task of a Context Object is to measure and calibrate perspectives with a shared set of rules and measures. That way, you have a precise instrument with which you can calibrate your shared understanding of concepts as they effect decisions.

*Regret Uncertainty Unawareness* happens when a decision is affected by a property the Context Object captures, but the decision is unaware of the connection. For example, `What were my trades yesterday?` is simple, except for a stock broker who trades in the UK, office is in NY, data systems are in San Francisco, and client on whose behalf the trader is trading is in Singapore. Yesterday could literally be two different days, and a misinterpretation by the AI would be unnoticed, because it would return an answer, and there was no verification if a human and an LLM are intended and interpreting the same concept. This URI based approach, of representing a dynamic URI registered as changing state in an array is meant to efficiently capture reasoning processe so that you can efficiently create optimal training data, of compounding effects of context on decisions.

## Why a Protocol and File Format

A universal approach to calibrating ground truth to observations in decision-making requires the ability to encode Typed Context Object both in static documents and dynamic communication streams. TCXP as a protocol is referenced as tcxp://, TCXP as a file format is referenced as .tcxp.

- TCXP is currently registered as a provisional URI scheme at: [https://www.iana.org/assignments/uri-schemes](https://www.iana.org/assignments/uri-schemes)
- .tcxp as a file format application is currently under application preparations.
