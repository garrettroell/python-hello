# Proof of Concept for running on LSF

Based on [https://github.com/DChandlerP/python-hello](https://github.com/DChandlerP/python-hello)

1. One can change version of Python to the one they desire. Just look at Python's official dockerhub page and change the version accordingly
1. No additional dependencies were added via apt-get nor pip but examples are in the Dockerfile of how this could be done. 
1. Using Conda adds a great deal of extra size to the image. But, it's easier to manage dependencies with Conda. Consider using pip if you want an optimized image that is >Python3
