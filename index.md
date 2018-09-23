## Motivation

I have been working as a UX-Developer at ACL Services using React for almost 3 years now, during this journey I had experiences different approaches of what it is React and how one should build interfaces using it.

I have been exposed to different ideas and phylosopies like exlusively building interfaces using controlled components without react state at all, to be exposed to Redux as the only source of true for the app state and finally 
to uses React state and the context api as provider and state manager.

After trying these approaches and coding in different ways large modules, I have seen that our apps had faced one or some of the following problems: 

- Developers doubting about where to make the requests for fetching the data in the app.
- The creation of UI Components that dependent of the app data, which make them hard to reuse.
- Receiving raw data as a props or how I called it, reciving a blackbox `object/array` as a props.
- Hard wire Redux state into the app, which make harder to see the line between where React starts and where Redux ends.
- Mixing *layout* componenets code `<div />` `<span />` with *UI* components
- Ending with large files using multiple `RenderSomething` methods which *returns* a bunch of processed `jsx` code.
- and other subtle issues.

All these problems adds to easines or reading the code and as well maintainability and a clear separation of concerns.

To mitigate all these issues, I would like to share with you an an architecture with a solid pattern and clear separation of concerns which can be used for most react applications.

This architecture is based on layers that deals with a specific concerns of the App. Allowing the developer to reason and care only about one specific concept at the time. 

Worth noting that these architecture is not base in any tools so the idea and core concepts can be translate to any state manager, either React State or Redux. 

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
