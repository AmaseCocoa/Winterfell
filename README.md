# Winterfell
Experiment with creating a Vue-like web framework in Python.
## Why does this exist?
* (As far as I am aware) most of the web frameworks currently available in Python are integrated with the web server, which is great, but they cannot be separated from the backend.
* I want to write in a Vue.js-like syntax using Python, a language I am familiar with.
## Current Problem
* Backend must also be integrated to run Python code
  * This cannot be avoided even with the current Winterfell implementation.
  * But, if it is written in Python, it is not much of a problem (it occupies a specific websocket endpoint, but can basically be integrated in any framework).
