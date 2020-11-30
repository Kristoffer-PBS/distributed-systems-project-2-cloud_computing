<!--![logo](images/fortune_cookies_logo.png) -->

![simpler_logo](images/simpler_logo.png)

# distributed-systems-project-2-cloud_computing
repo for project 2 in distributed systems 2020 about cloud computing, using docker and kubernetes.


## Ideas

Host a static webpage (the server will serve a single html document), with a button, that has 
an attached event handler. When clicked the embedded javascript file, will be called and make
a http FETCH request to a server pod, to generate a random number, and use that to index its 
dababase (aka a text file), and return the chosen string to the requester, which will update
the DOM (Document Object Model), and display the generated fortune cookie.


## TODOS

- [  ] Create dockerfile
- [  ] Create deployment manifest for kubernetes cluster.
- [  ] Unit test, and test API service endpoint.

## Rapport:
https://www.overleaf.com/3736124467bfjtxxjtrbgg
