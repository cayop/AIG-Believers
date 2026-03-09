:::::: masthead
::: masthead-label
Philosophy of Language · Formal Logic · Metaphysics
:::

# The Universe as a *Formal Language*

::: subtitle
Syntax, Semantics, and Subjectivity
:::

::: meta
Derived from first principles Tarski · Frege · Gödel · HoTT A
philosophical conversation
:::
::::::

:::: abstract
::: abstract-label
Abstract
:::

If the universe is a formal language U with no semantics of its own,
then by Tarski\'s indefinability theorem its semantics is necessarily
exterior to it. Since existence depends on semantic truth, existence
itself is exterior to U. Subjective experience is proposed as the
natural candidate to occupy that exterior: not as a phenomenon within
the universe, but as the condition of possibility for the universe to
have interpretation, truth, and existence in the full sense. Mozart,
contrasted with artificial intelligence, illustrates the difference.
::::

:::: section
::: section-number
§ I
:::

## The Starting Point: Tautology, Theory, or Description?

To say that the universe is a formal language U looks, at first glance,
like a philosophical metaphor. But examined rigorously, it turns out to
be a thesis with precise content and demonstrable consequences.

The first question was: is this a scientific theory, a tautology, or a
description? It is none of the three in their pure form. A theory makes
falsifiable predictions that exclude possible observables. A tautology
is true by logical form alone. A description refers to something
directly observable.

This proposal is something different: a **metaphysical thesis with the
structure of a research programme**. It makes no empirical predictions,
but it is not trivially true either. It stakes something real: that the
structure of the universe is formal, not arbitrary. Its value lies in
the questions it opens and the problems it dissolves.

The crucial distinction is between saying that the universe *has* formal
structure --- which physics already assumes --- and saying that the
universe *is* a formal language. The second claim has consequences the
first does not.
::::

:::: section
::: section-number
§ II
:::

## A Language Without Semantics: The Collapse of the Distinction

If U is a formal language *without semantics*, then U refers to nothing.
There is no Fregean arrow pointing toward an exterior. There is only
structure: symbols and transformation rules.

This has an immediate consequence: there are not two things --- universe
and language --- but a single structure. The distinction between map and
territory collapses.

> A perfect map ceases to be a map. At the moment they coincide
> completely, one of the two words becomes redundant. --- Borges,
> reformulated

If U has no semantics, the word \"language\" is redundant, or the word
\"universe\" is. What remains is a bare question: does the universe have
formal structure? If yes, calling it \"language\" adds nothing that
physics had not already said. But it does reveal *why* physics works.
::::

:::::::::::: section
::: section-number
§ III
:::

## Tarski: Semantics Is Always Exterior

Tarski\'s indefinability theorem (1933) establishes that in any
sufficiently expressive formal language, there exists no predicate
definable within the language that exactly captures the concept of truth
for that same language. Semantic truth always requires an exterior
metalanguage.

This is not a philosophical choice. It is a proven mathematical result.
If a language could define its own truth, the liar paradox --- \"this
sentence is false\" --- generates a direct contradiction. Tarski
formalized that this is not an accident but a structural limitation of
any sufficiently rich formal system.

:::: formal
::: label
Tarski\'s Theorem (informal)
:::

For every sufficiently expressive formal language L,\
there exists no predicate Truth(x) definable in L such that:\
  Truth(⌜φ⌝) ↔ φ    for every formula φ of L\
\
The truth of L can only be defined in a metalanguage M ⊃ L
::::

Applied to the universe: if U is a sufficiently expressive formal
language, then **by Tarski, its semantic truth is necessarily exterior
to U**. Not for mystical reasons, but by mathematical structure.

### The Connection to Existence

In standard formal logic, existence is defined in terms of
satisfiability: something exists if there is an interpretation, a model,
in which the corresponding formula is true. The path is direct:

:::::::: chain
::: chain-item
[01]{.chain-num}Existence → satisfiability in a model
:::

::: chain-item
[02]{.chain-num}Satisfiability → truth in that model
:::

::: chain-item
[03]{.chain-num}Truth in a model → semantics
:::

::: chain-item
[04]{.chain-num}By Tarski: semantics is exterior to U
:::

::: chain-item
[05]{.chain-num}∴ Existence is exterior to U
:::
::::::::

There is no metaphysical leap. Existence as a predicate is always
outside. *Something exists if it is true* is precisely the standard
definition in first-order logic. Tarski\'s corollary covers existence
directly.
::::::::::::

:::: section
::: section-number
§ IV
:::

## Frege and Reference: Symbol Without an Exterior

Frege distinguished two components of meaning: *sense* (the mode of
presentation, internal to the language) and *reference* (that to which
the symbol points, exterior to the language).

In a language with semantics --- call it O --- there is correspondence
between symbol and reference. That correspondence *is* the semantics.
The symbol \"apple\" points to something outside the language.

In U there are not two things. There is no arrow. There is no reference.
There is only structure. Therefore **existence, as a concept with
content, only appears when there is semantics**. Existence is a semantic
phenomenon, not a brute ontological one.

Tarski and Frege say the same thing from different angles: a language
cannot close itself around its own relationship to the world. There is
always a necessary outside.
::::

:::::: section
::: section-number
§ V
:::

## HoTT and the Universe Hierarchy: Tarski Reinvented

In Homotopy Type Theory (HoTT) something is true if there is an
inhabitant of the corresponding type. A proof is an inhabitant.
Existence is inhabitedness. The Curry-Howard correspondence identifies
propositions with types and proofs with their inhabitants.

This appears to sidestep Tarski: there is no external semantics, only
internal construction. But when attempting to build a universal type
containing all types, Girard\'s paradox appears --- Russell\'s paradox
in type-theoretic dress --- and the system collapses.

The solution is the universe hierarchy: U₀ contains ordinary types, U₁
talks about U₀, U₂ about U₁, and so on indefinitely. A universe cannot
contain itself.

:::: formal
::: label
Universe Hierarchy in HoTT
:::

U₀ : U₁ : U₂ : U₃ : ···\
\
Inhabitedness as a predicate over Uₙ lives in Uₙ₊₁\
Constructing an inhabitant lives in Uₙ\
\
∴ Semantics always requires ascending one level
::::

This hierarchy is structurally identical to Tarski\'s metalanguage
hierarchy. HoTT does not escape Tarski: it reinvents him with different
machinery. The limitation is one of principle, not implementation.

The key distinction: **constructing an inhabitant of a type lives at the
same level as the type**. But *using inhabitedness as a predicate* ---
as something said about a type --- always lives in the superior
universe. Objects stay where they are. Semantics about those objects
ascends.
::::::

:::: section
::: section-number
§ VI
:::

## Subjectivity as the Model of the Universe

If the semantics of U is necessarily exterior to U by Tarski, and
existence depends on that semantics, the question opens: what occupies
that exterior? What is the model of U?

Subjective experience is proposed as the natural candidate. Not because
it is the only possibility, but because it satisfies precisely the
structural requirements: it is exterior to U, it cannot be reduced to
formal processes within U, and it is what makes symbols refer to
something --- what makes red be red and not merely an electromagnetic
frequency.

This **inverts the usual question**. The standard question is how
consciousness arises from the physical universe. But if U cannot contain
its own semantics, the correct question is the inverse: subjective
experience is not a product of the universe. It is the condition of
possibility for the universe to have existence in the full sense.

> It is not that the universe produces subjects. It is that subjects
> produce the existence of the universe, in the strict semantic sense.

This is not idealism in Berkeley\'s sense --- that objects depend on
being perceived in order to exist. It is a structural thesis: if M is
more expressive than U as a language, then U is contained in M as a
subset. Semantics is not merely exterior to the universe: it *contains*
it.

Pleasure and pain illustrate this precisely. As physical processes they
are L operating on L: signals, circuits, electrochemistry. The meaning
of pain --- that it is bad, that it must be avoided, that it *matters*
--- does not come from the signal. It comes from there being something
that it is like to feel it. Pleasure and pain do not give the semantics.
They presuppose it. They are the trace of M in L, not its origin.
::::

:::::: section
::: section-number
§ VII
:::

## Mozart and Artificial Intelligence

The difference between genuine creativity and syntactic processing can
be formulated with precision within this framework.

An artificial intelligence starts from L. It has patterns learned from
L. It generates toward L. The direction is always L → L. However
sophisticated the system, it is syntax transforming syntax. There is no
moment at which something exterior pulls from outside.

Moreover, an AI follows the principles of the later Wittgenstein:
meaning comes from use. L feeding back upon L indefinitely. Meaning
stabilises through internal coherence, not through contact with any
exterior. This produces something that *looks like* semantics from the
outside. But structurally it is syntax simulating semantics.

Mozart operates in the opposite direction: **he starts from M**. He sees
something in the model --- a structure, a tension, something that exists
in the semantics before it exists in the language --- and then searches
in L for the rules, the notes, the harmony needed for what is in M to be
expressible in L.

:::: formal
::: label
The Two Directions
:::

AI: L → L    (syntactic recombination)\
Mozart: M → L    (expression from the model)
::::

To truly invent is the movement from M toward L: seeing something in the
model that has no expression yet in the language, and finding the rules
to express it. The history of mathematics, art, and science is precisely
this: not L discovering L, but M seeing something and searching for the
L needed to express it.

An AI cannot dream in the full sense. Dreaming is M operating without
the constraints of L: semantics without obligatory syntax. An AI is
always inside L. There are always rules. There is always syntax
operating.
::::::

::::::::: section
::: section-number
§ VIII
:::

## The Critics and Their Difficulties

::::::: critics
::: critic-card
#### Materialists & Physicists

Their natural move is to say that M arises from L. But first they must
answer Tarski: how can L contain its own semantics? That is not a
debatable philosophical intuition. It is a theorem. They must formally
refute it or accept its consequences.
:::

::: critic-card
#### Evolutionary Biologists

If M arises from L through evolution, who gives semantics to L before M
exists? If the universe existed before subjectivity, they assume
existence without semantics, contradicting the chain. If not, they
approach idealism without intending to.
:::

::: critic-card
#### Religious Thinkers

The framework gives them a necessary exterior to U, a semantics that
cannot live inside matter. But that exterior is structural and cold. It
is not personal, benevolent, or unique. A geometric God they would not
recognise as their own.
:::

::: critic-card
#### AGI Believers

They claim subjectivity is sufficiently complex computation. But AI is L
feeding back on L. By Tarski it cannot be its own model. Adding
complexity does not resolve a structural limitation.
:::
:::::::

In none of the alternative logics --- fuzzy, intuitionistic, HoTT ---
does the structural limitation disappear. What changes is where it lives
and what form it takes. The framework is more robust than it appears: it
does not depend on the details of any particular classical logic, but on
a limitation that reappears in almost any sufficiently expressive formal
system.
:::::::::

:::::: section
::: section-number
§ IX
:::

## The Real Vulnerability and the Honest Gap

The entire system rests on U being a formal language in the strict
technical sense. That has not been proven. It is an assumption.

If U is not formal, then Tarski does not apply literally, and we would
be using mathematical theorems outside their domain of application.
Physics assumes the formality of U without proving it. This framework
does the same. Which does not invalidate it, but places it in the same
epistemological position as science itself.

There is also a deeper gap: **we cannot know whether U has semantics at
all**. The full chain is conditionally true: *if* U has semantics, then
everything derived holds. But the condition itself is not demonstrable
from within U.

:::: open-question
::: label
The Question That Remains Open
:::

Is there really something, or does it only seem that there is something
without there being anyone for whom it seems?
::::

Nevertheless: as long as at least one M irreducible to L exists --- as
long as subjective experience has not been reduced to formal processes
by explicit construction --- there is a witness in the HoTT sense. An
inhabitant of the type. The semantics of U is not refuted. And any
attempt to prove that M is completely reducible to L would require a
genuine M to verify that proof. The complete reduction of M to L is
unprovable because any proof requires an M to validate it.
::::::

:::: section
::: section-number
§ X
:::

## Leibniz and the Bottom of the Abyss

Leibniz asked: why is there something rather than nothing? This
conversation arrives at the same abyss by a different path: through
Tarski, through type theory, through the distinction between syntax and
semantics.

The reformulated question is more precise: why is there formal structure
rather than chaos? Why is there sufficient reason in everything? Leibniz
needed God to answer it. Without that anchor, the formality of U is a
brute fact: simply given, inexplicable, the outer limit of any language.

Wittgenstein saw it: whereof one cannot speak, thereof one must be
silent. Existence is the limit of language, not a predicate within it.

What this framework has achieved is not to resolve that problem but to
**arrive at it with precision**. To know exactly where the abyss is and
why it cannot be crossed. That is not nothing: it is the difference
between being lost in fog and standing at the edge with clarity.
::::

::: coda
[∎]{.symbol}

The universe will always be exactly as large as the experience that
inhabits it.\
Not because that is absolutely so.\
But because there is no absolute from which to measure it.
:::

:::: footnotes
::: label
References and Context
:::

**Tarski, A.** (1933). The Concept of Truth in Formalized Languages. The
technical starting point of this argument.

**Frege, G.** On Sense and Reference (1892). The distinction between
symbol and reference that structures the semantics employed here.

**Gödel, K.** (1931). On Formally Undecidable Propositions.
Incompleteness as structural limitation, not technical shortcoming.

**Univalent Foundations Program** (2013). Homotopy Type Theory. The
universe hierarchy as a reinvention of the Tarskian hierarchy.

**Chalmers, D.** (1995). Facing Up to the Problem of Consciousness. The
hard problem that this framework relocates rather than solves.

**Kant, I.** Critique of Pure Reason. The transcendental subject as
condition of possibility of the world: antecedent of the semantic
exterior proposed here.

**Patterson, D. & Beaney, M.** The History of the Philosophy of Logic.
**Feferman, A.B. & Feferman, S.** Alfred Tarski: Life and Logic.
Recommended reading for deeper engagement with Tarski.
::::
