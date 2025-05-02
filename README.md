Higher Order Logical Truth
========================

This repo is divoted to those aspects of support for the representation of knowledge in a particular variant of Higher Order Logic which precede its applications beyond the _a priori_, despite much of the motivation for undertaking this work being more borfly construed.

I will present the changes which I have in mind as coming in layers or stages, though it is not necessarily the intention that they be implemented in that way.
In this, one might consider the departure as taking place from the kind of support we now see in systems such as Cambridge HOL or ProofPower (for historical reasons I think primarily in terms of the latter).

- A Retreat from Concrete to Abstract

The first element of transformation is intended to decouple the logic implemented in the core systems from any concrete syntax or stored representation, expecting that different observers may view the same logical fundamentals, possibly intermediated by LLMs or similar technology, in whatever form they find most readily intelligible, which for many would not be formal at all but through informal discursion or more graphical presentations.
Decoupling the stored forms will pave the way to the merging of respositories which have diverse origin, including the content of heritage data sources, given conformant interfaces presenting these data sources as coherent content through the APIs and protocols which will be defined for this paradigm in due course.

The retreat from concrete in to abstract logic is a means to a pluralism of the concrete, and removes from the core reasoning matters extraneous to the underlying pure content and logical structure.

- The Hierarchy of Contexts

The first element of this part of the enterprise is to decide the logical structure of the abstract repository, to provide an API for local access to that structure, a protocol for remote access, and to prototype support for both of those.
It intended that it be possible to combine collections of such repositories into a single repository in a coherent manner, which will be achived by a heirarchical naming system which permits the names in each separate component to be made distinct from those in all the others merged together.

Each repository WORM store holding a hierarchy of contexts.
Each context is an extension of the core logic; most of them will be conservative extensions.
An extension introduces a finite set of new names, together with one or more contraints, and thereby creates a new `context'.
To enable free choice of names, each context in a repository has a heirarchical name relative to a top node in the repository,

