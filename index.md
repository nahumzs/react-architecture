## Motivation

I have been working as a UX-Developer at ACL Services using React for almost 3 years now, during this journey I had experiences different perception of what it is React and how one should build interfaces using it.

I have been exposed to different ideas and phylosopies. From using only controlled components, to not use react state at all, totally let Redux controls the state of the entire application and to the oppostie which is to not use redux instead take advantage of the state that React provides. 

Throught all these experience I have came with an architecture which is a solid starting point for the majority of scenarios in a react App. 

This architecture is based on layers that deals with a specific concerns of the App. Allowing the developer to reason and care only about one specific concept at the time while developing or maintaining it. Worth noting that these architecture is not base in any tools so the idea and core concept can be translate to any state manager, either React State or Redux. 

For the purpose of this Document I will be using the React State as my primary state manager.

## Audicence
The intendend audience are developers which might has previous experience working with React or developers which are trying to explore a way to organize their app in what I consider a more meaninful way. 

## Perfsonal Goal

My personal goal is to document the way I learned to architect react applications and hoping that doing it can help other react developers to be exposed to this experience.

### The Architecture and The Separation of Concerns
<img width="550" src="https://github.com/nahumzs/react-architecture/blob/master/assets/El_Diagrama.png" alt="React Architecture Diagram" />

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
