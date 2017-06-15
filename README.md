
speech-to-text-websockets-python updated to python 3 

Adapted from https://github.com/watson-developer-cloud/speech-to-text-websockets-python 

This project consists of a python client that interacts with the IBM Watson Speech To Text service through its WebSockets interface. The client streams audio to the STT service and receives recognition hypotheses in real time. 
It can run N simultaneous recognition sessions. 

**The original sample connection script provided by the Watson team only worked in Python 2. This simply updates that script for Python 3. No other changes were made.**

Check out the [Read Me](https://github.com/watson-developer-cloud/speech-to-text-websockets-python) in the original repo for documentation.

If you are looking for an example of a websocket connection for Python 3 that you can run as a function call from within a script or in an IDE like Jupyter Notebook, try this: https://gist.github.com/kstohr/a1dee0e88e8587576e03804194c7f7df
