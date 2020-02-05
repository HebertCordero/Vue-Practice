# Vue Practive 1

Here we are encountering something new. The v-bind attribute you are seeing is called a directive.

Directives are prefixed with v- to indicate that they are special attributes provided by Vue.
They apply special reactive behavior to the rendered DOM.
Here, it is basically saying “keep this element’s title attribute up-to-date with the message property on the Vue instance.”

If you open up your JavaScript console again and enter app2.message = 'some new message', you’ll once again see that the bound HTML - in this case the title attribute - has been updated.
