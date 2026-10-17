# Typed Context Protocol, a W3C Community Group

**Specification (Draft Community Group Report, in progress)**
- [https://typed-context-protocol.github.io/specification/](https://typed-context-protocol.github.io/specification/)

**W3C Community Group Home Page**
- [W3C Typed Context Protocol Community Group](https://www.w3.org/community/typed-context-protocol/)

**Charter**:
- [https://github.com/typed-context-protocol/charter](https://github.com/typed-context-protocol/charter)

**Notebook Example (in progress)**
- [https://gist.github.com/RonItelman/c6284e385dd21964896f89135b005ab1](https://gist.github.com/RonItelman/c6284e385dd21964896f89135b005ab1)

## Introducing the Typed Context Object

The purpose of a Typed Context Object is that *Context* has mathematical guarantees of certain the rules to be _invariant_, meaning that you can communicate a concept to many different systems, and what and how that concept is defined is not the task of a Context Object, the task of a Context Object is to measure and calibrate perspectives with a shared set of rules and measures. That way, you have a precise instrument with which you can calibrate your shared understanding of concepts as they effect decisions.

*Regret Uncertainty Unawareness* happens when a decision is affected by a property the Context Object captures, but the decision is unaware of the connection. For example, `What were my trades yesterday?` is simple, except for a stock broker who trades in the UK, office is in NY, data systems are in San Francisco, and client on whose behalf the trader is trading is in Singapore. Yesterday could literally be two different days, and a misinterpretation by the AI would be unnoticed, because it would return an answer, and there was no verification if a human and an LLM are intended and interpreting the same concept. This URI based approach, of representing a dynamic URI registered as changing state in an array is meant to efficiently capture reasoning processe so that you can efficiently create optimal training data, of compounding effects of context on decisions.

## Why a Protocol and File Format

A universal approach to calibrating ground truth to observations in decision-making requires the ability to encode Typed Context Object both in static documents and dynamic communication streams. As a protocol, tcxp is written as tcxp: addresses; as a file format, it is a .tcxp document

- TCXP is registered as a provisional URI scheme at: [https://www.iana.org/assignments/uri-schemes](https://www.iana.org/assignments/uri-schemes)
- The media type text/tcxp, for .tcxp documents, is being requested through W3C

## Name Change: From "Context Graph" to "Typed Context Protocol"
The previous group name was "Context Graph" Community Group. The name change was due to industry overlap in terminology, where Knowledge Graphs and Ontologies were becoming a more popular term to describe Context. The Typed Context Protocol takes a significantly different approach, and a distinct name became important to highlight the difference.
