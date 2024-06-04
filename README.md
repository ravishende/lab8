# Lab8 - Ravi Shende

Github Pages link: [https://ravishende.github.io/lab8/](https://ravishende.github.io/lab8/)

1. Graceful degredation relates to service workers in that service workers are the next step in graceful degredation from a fully functionaly network. When the network connection is unreliable or slow, we use service workers to act as a next step to fall back on without making our site crash. This way, we have the network as our first step and the service workers as our next fall back. Alternatively, we could do the opposite and fall back onto the network if there's nothing in the service worker cache. Either way though, graceful degredation and service workers in our app are both working to provide a usable application even when there are less than ideal conditions. They help us by creating something to fall back upon when we meet suboptimal conditions.
