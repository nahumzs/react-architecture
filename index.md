## Motivation

I have been working as a UX-Developer at ACL Services using React for almost 3 years now, during this journey I had experiences different perception of what it is React and how one should build interfaces using it.

Ideas and phylosopies were from using only controlled components and nothing more to not use react state and let redux controls the entire application state to don't use redux and the only thing you need is React state. 

Throught all these experience I have came with an architecture that is suitable for the majority of scenarios for a react App or feature. The architecture is based on layers that deals with a specific concerns of the App. Allowing the developer to reason and care only about one specific concept at the time while developing or maintaining it. 

## Audicence
The intendend audience are developers which might has previous experience working with React or developer which are trying to explore a way to organize their app in what I consider a more meaninful way. 

## Goal

My goal for sharing this is to help other new comers and current react developers to understand how to apply better the different patterns that exist on the react ecosystem.

To help me to explain better these concepts, I will use only react and nothing else, keep in mind that these concept can easily be extrapolated for tools like Redux or any other state manager. 

Also I would like to add that some of the concept that I will use in my examples are inspired by Redux.


## Table of Contents
### EL Diagrama and Separation of concerns
### Introduction
### Services
### Providers
#### Provider Provider
#### Provider Render Props
### The Bridge
### Containers
### Building the UI
#### Stateles components
#### Compound Components by Extending Children
#### Render Props Components
#### Context base Components
#### High Order Component
