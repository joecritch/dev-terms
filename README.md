# Dev Terms

*Here's an [incomplete](https://github.com/joecritch/dev-terms/pulls) list of generic terms that I've heard developers use. Users of these terms often take them for granted, but they can sometimes increase the barrier of entry for others (especially if non-native English speakers).*

***Note:** I'm not condoning the use of all these terms. (Some might even be slightly cringing.) It's just an attempt to get them all written down and explained.*

## ahead of time

When something is performed "ahead of time", it means that something is done before it's actually needed. Prefetching or eager-loading are equivalents. It can also refer to the compilation phase — i.e. *ahead* of runtime.

## bikeshed

Over-discussing a certain aspect of code which is trivial, such as code formatting. http://bikeshed.com/

## brownfield

A brownfield project is project where you've got to add new features on top of an old, possibly outdated technically, codebase. Opposite of [greenfield](#greenfield).

## deep dive

When a developer explains some source code, line-by-line. Often on a video or during a talk.

## dogfooding

Working out glitches in an app, often by using the product itself or a related product. Comes from "eat your own dogfood".

## for free

When you get something "for free", this often means that something works automatically, without you having to write some code.

## greenfield

A greenfield project is a project from scratch, where you get much more free reign on the technical choices. Not impeded by existing code. Opposite of [brownfield](#brownfield).

## implementation detail

This is when the actual code written for a particular behaviour is irrelevant. It's often just its input and output that you should be concerned with.

## nit

Not the "National Invitation Tournament" in this case. This is just a developer shortening the term "nit-pick", where they're picking up on the small things, and are potentially being quite subjective. Often found in a pull request, and can often be classed as [bikeshed](#bikeshed)ding.

## reason about

If something is "easy to reason about", it essentially means it's easy to understand how its parts behave together; and generally being able to keep on top of your codebase.

## rubber ducking

Explaining a problem out loud to someone else, or an actual rubber duck, to help think of a solution.

## ship

Developers like to "ship" things. This means to actually release/deploy it.

## single source of truth

This refers to the practice of persisting the data representation of an entity in only one place. This helps avoid ambiguity and avoid bugs that are caused because different states of the same entity are persisted to and retrieved from different places.

## tech debt

Extra work arising from when the quickest or easiest to implement solution is used, instead of the best or most optimal solution.
