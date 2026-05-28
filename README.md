# Lab8


Question: How are graceful degradation and service workers related?

Graceful degredation is the practice of building an app with modern features that can also still fucntion properly on older browsers or under constrained conditions. Service workers act as a great example of this concept for networkk connectivity. We often build an app expecting strong internet connection to fetch new data, but we can implement the service worker as a fallback. If the network drops, the worker steps in to serve teh cached files ensureing the application can degrade gracefully. (instead of completely breaking).