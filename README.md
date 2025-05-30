# Lab8 - Alex Tatoian
# [Pages Link](https://balexdalex42.github.io/cse110_lab8/)
## Graceful Degradation and Service Workers
Graceful degradation is the idea that a website/app should have a capacity to run and work (albeit at potentially a lower performance) if certain services fail. Typically this is described in the frame of an app/website running on different versions, where features are only supported on newer versions, yet older versions still have a working app/website with just less features. In this case, service workers are not a part of newer versions of browsers. Thus all this offline caching and network request handling done by service workers would not be possible in older versions. Graceful degradation would make sure that if service workers are not available, it does not break the website/app, rather maybe it only allows for online use.
## [Image](./pwa.jpg)
![PWA Image](./pwa.jpg)

