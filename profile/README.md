Open Engineering Story

Stories are assembled, not built from scratch.

Welcome to Open Engineering Story, the home of individual stories created using the Open Engineering composable storytelling architecture.

We believe that stories, like software, can be composed from reusable elements without sacrificing originality, creativity, or emotional impact.

Characters, conflicts, events, scenes, investigations, and decisions become identifiable narrative elements. These elements are organized into capabilities, composed into coherent stories, and delivered as narrative products.

Every story is unique. Its underlying narrative capabilities can be reused.

⸻

Our Mission

To make storytelling composable, traceable, reusable, and expressive.

Open Engineering Story provides a home for individual narrative works, preserving their original content while connecting them to the reusable foundations of the Open Engineering ecosystem.

Our approach is inspired by Robert McKee’s Story: Substance, Structure, Style, and the Principles of Screenwriting, extended with principles from software architecture, systems thinking, and compositional design.

We aim to enable stories that can be:

* Authored — written with creative freedom.
* Decomposed — understood through their constituent narrative elements.
* Assembled — composed from reusable narrative capabilities.
* Inspected — explored through relationships, evidence, and structure.
* Adapted — delivered across different media and experiences.
* Reused — shared without duplicating their underlying definitions.

⸻

The Open Engineering Story Architecture

Every story can be described through six complementary concerns.

Concern	Responsibility
Story Ontologies	Define what narrative concepts mean.
Story Conventions	Define how narrative elements and compositions are represented and validated.
Story Bricks	Define reusable narrative elements.
Story Capsules	Encapsulate reusable narrative capabilities.
Story Assemblies	Compose capabilities into coherent narrative structures.
Story Products	Define how complete narratives are delivered and experienced.

An individual story repository brings these concerns together through references and story-specific content.

flowchart TD
    O["Story Ontologies"] -.-> C["Story Conventions"]
    C -.-> B["Story Bricks"]
    C -.-> P["Story Capsules"]
    C -.-> A["Story Assemblies"]
    C -.-> PR["Story Products"]
    B --> P
    P --> A
    A --> PR
    PR --> S["Individual Story"]
    O -.-> B
    O -.-> P
    O -.-> A
    O -.-> PR

Ontologies define meaning. Conventions define contracts. Bricks provide elements. Capsules provide capabilities. Assemblies compose narratives. Products deliver experiences.

Individual stories retain ownership of their original narrative content.

⸻

From Narrative Elements to Story Products

Consider a detective story.

1. Story Bricks

The smallest reusable narrative elements might include:

* A detective
* A witness
* A crime
* A piece of evidence
* A conflict
* A decision
* A verdict
* A recommendation

Each Brick represents an identifiable narrative element.

2. Story Capsules

Bricks can participate in reusable narrative capabilities:

* Character Capsule
* Conflict Capsule
* Scene Capsule
* Story Value Capsule
* Narrative Analysis Capsule

A detective story may additionally require Investigation, Evidence, Testimony, or Verdict capabilities.

These specialized capabilities are candidates for reusable extensions where existing Capsules do not suffice.

3. Story Assemblies

Capsules can be composed into narrative structures:

* Case Opening
* Witness Testimony
* Forensic Investigation
* Trial and Verdict
* Rehabilitation and Resolution
* Complete Story

An Assembly describes how narrative capabilities work together.

4. Story Products

The resulting story can be delivered as:

* A written detective story
* An interactive investigation
* An educational experience
* An audio drama
* An animated film
* A narrative game

The same underlying Story Assembly may support multiple products.

⸻

Our Stories

Code Smell Detectives

The Case of the Malodorous Methods

Explore the story repository

A detective-noir investigation into software quality, technical debt, and the consequences of poor engineering decisions.

The story follows the Code Smell Detective through the Agility Game Enterprise Pentagon, where deployment failures lead to witness interviews, forensic code analysis, a courtroom verdict, and a refactoring sentence.

The narrative introduces:

* The Code Smell Detective
* Sarah from DevOps
* Marcus from QA
* Jenkins, the digital witness
* Evidence of software design problems
* Findings, verdicts, and remediation recommendations

The story demonstrates how software engineering concepts can be explained through narrative.

It also serves as a proposed reference implementation of the Open Engineering Story architecture.

Its original prose remains authoritative. The architectural model references its elements rather than rewriting them.

⸻

One Story, Multiple Experiences

A central ambition of Open Engineering Story is to separate narrative composition from its presentation.

flowchart TD
    S["Complete Story Assembly"]
    S --> W["Written Story"]
    S --> I["Interactive Fiction"]
    S --> G["Narrative Game"]
    S --> E["Educational Experience"]
    S --> AU["Audio Drama"]
    S --> V["Animated Film"]

Each product may have different presentation, interaction, and distribution requirements.

However, the underlying narrative concepts, characters, events, and relationships can remain shared.

This makes it possible to adapt stories without unnecessarily duplicating their narrative foundations.

⸻

Repository Ecosystem

Open Engineering Story participates in a larger ecosystem of reusable definitions and capabilities.

Repository	Purpose
Story Ontologies	Narrative concepts and semantic relationships
Story Conventions	Narrative contracts, schemas, and validation
Story Bricks	Reusable narrative elements
Story Capsules	Reusable narrative capabilities
Story Assemblies	Reusable narrative compositions
Story Products	Reusable narrative product definitions
Open Engineering Assembly	Generic assembly resolution and lifecycle
Open Engineering Story	Individual story instances

Definitions Versus Instances

The distinction between reusable definitions and concrete story instances is fundamental.

For example:

Definition	Story instance
Character	Sarah from DevOps
Evidence	A God Object code excerpt
Investigation	The Malodorous Methods investigation
Verdict	Guilty on the charges presented in the case
Story Assembly	The complete detective-case composition
Written Narrative Product	The published detective story

Reusable definitions belong to their respective Open Engineering repositories.

Individual story repositories own the actual characters, events, evidence, narrative content, and story-specific compositions.

⸻

Story Integrity and Traceability

We want stories to remain creative works, not become collections of disconnected technical objects.

Our guiding principles are:

Preserve the original story. Narrative prose remains authoritative unless its author explicitly revises it.

Reference rather than duplicate. Story repositories reference reusable definitions and capabilities.

Maintain provenance. Distinguish original content, narrative interpretation, and architectural extensions.

Preserve creative freedom. Structural validation should not dictate artistic choices.

Make relationships inspectable. Characters, events, evidence, findings, and outcomes should be traceable where relevant.

Support adaptation. A story should be reusable across media without losing its identity.

Version the composition. Dependencies and released artifacts should be identifiable and reproducible.

These principles follow the Open Engineering Rule of Existing Gravity: inspect and respect existing structures before introducing new ones.

⸻

Storytelling Meets Software Engineering

Open Engineering Story connects storytelling with several other Open Engineering initiatives.

Open Engineering Architecture

Stories can explain architecture through narrated walkthroughs, characters, scenarios, and interactive environments.

Agility Games

Stories can give meaning to missions, board spaces, enterprise decisions, and their consequences.

Code Smell Detective

Detective narratives can transform technical investigations into engaging learning experiences.

Open Engineering Academy

Narrative experiences can support education through scenarios, decisions, consequences, and reflection.

PixStars

A narrative can become a live performance combining human creativity, artificial intelligence, music, robotics, lighting, and narration.

These integrations illustrate a broader principle:

Storytelling is not limited to books or films. It can become a reusable capability within software products and interactive experiences.

⸻

Contributing

We welcome contributions that strengthen the Open Engineering storytelling approach.

Contributions may include:

* Original stories
* Story-specific architectural mappings
* Reusable narrative patterns
* Story composition examples
* Validation and traceability improvements
* Educational narrative experiences
* Cross-media adaptations

Before introducing new narrative definitions, inspect the existing Story Ontologies, Conventions, Bricks, Capsules, Assemblies, and Products.

Where possible, extend reusable definitions in their owning repositories rather than duplicating them inside individual stories.

Each story should retain clear attribution, provenance, and ownership of its original content.

⸻

Inspiration and References

Our narrative approach draws inspiration from:

Robert McKee — Story: Substance, Structure, Style, and the Principles of Screenwriting (1997)

https://openlibrary.org/works/OL273896W/Story

McKee’s work informs our understanding of dramatic structure, conflict, character, scene design, and narrative meaning.

The Open Engineering decomposition into Ontologies, Conventions, Bricks, Capsules, Assemblies, and Products is our own architectural extension.

Additional technical references:

* JSON Schema
* Semantic Versioning
* Open Engineering Stories

⸻

Our Philosophy

We believe that a story is more than a sequence of words.

It is a composition of characters, desires, conflicts, decisions, events, consequences, and meaning.

By making these elements identifiable and reusable, we can explore new ways of authoring, understanding, and experiencing stories.

But the architecture should always serve the storyteller.

Preserve the story. Reference the parts. Compose the capabilities. Deliver the experience.

⸻

Open Engineering Story — Assembling stories from reusable narrative elements, without losing the art of storytelling.
