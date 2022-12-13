## 7:88

- safeareaview renders content only within the device that is deemed "safe"
- hey fill your parent, make sure you always fill the parent (flex: 1)
- fragments allow to render two elements side by side w/o having to wrap in a specific other container

## 7:89

- SAV only for ios
- status bar from react native is android only
- status bar from expo is ios only
- currentHeight android status bar

## 7:90

- cmd + m android : element inspector
- cmd + control + z ios : inspector
- performance monitor debug tools

## 7:95

- adding eslint, prettier

## 7:97

- adding react native paper, safe area context

## 7:109

- styled components use css to react native in the background
- converts css text to react native stylesheet objects

## 7:111

- theme provider acts like a global state
- react context is a way to pass data through components, w/o having to pass props down manually at every level

## 7:120

- implementing spacers within the restaurant info card to give space between the icons

## 7:125

- consistency: want to create componenets that last the test of time, hence why we created the spacer, the spacers component has a an actual purpose to add margin, size, want to create components that can be used across the code base

## 7:130

- `contentContainerStyle` is not applied to each item individually rather it is applied to the holistic content inside the container

- that is why we need to wrap the `Spacer` component around the rendered item.

## 7:140

- cloud <---> services layer <---> application

## 7:140

- our phone has an application, have to leverage context, service layer consisting of context and service, context serves to share the data globally within the application, service itself stems to determine what methods we want in order to get data from the external service, act between context and the external api

## 7:143

- promise is like a binding contract, promising that you're getting something back in the future, function internally - resolve and reject, if we hit resolve, we'll return local promise result
- function in the .then returns us the result that we were promissed to get back
- fetch is an interface around promises that wraps the ability to talk to exernal apis, have to parse json, then another .then where we get our actual response then console log the response
