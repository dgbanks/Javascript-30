### data-*
* forms a class of attributes called **custom data attributes** that allow proprietary information to be exchanged between the HTML and its DOM representation that may be used by scripts
* all custom data are available via the element's HTMLElement interface
  * the HTMLElement interface inherits from Element (which inherits from Node, EventTarget)
  * the .dataset property allows access (reading and writing) to all custom data attributes set on the element

### attribute selectors
* in our code: `const audio = document.querySelector(`audio[data-key='${e.keyCode}']`);`
  * `audio[data-key='${e.keyCode}']`
  * use brackets to read an elements attributes

### audio elements
* `<audio>` tag
* embeds sound content in documents using `src` attribute
* using DOM selectors to save as JavaScript object, responds to build-in methods:
  * addTextTrack(), canPlayType(), load(), play(), pause()
  * see also huge lists of HTML Audio/Video DOM Reference events and properties on w3schools.com


### Element.classList
* a read-only property that provides a live DOMTokenList collection of the class attributes of the element
* `element.classList.add('class')`
* `element.classList.remove('class')`
* `element.classList.toggle('class')`
* `'transitionend'` fires when a CSS transition has completed
