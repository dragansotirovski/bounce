Solution for the BouncyBall exercise

Spec:
    https://github.com/hfour/exercises/tree/master/bouncing-balls


Run & Test:
    1. NodeJs is installed 
        If nodejs is installed on the machine, simply run `node app` in the root folder of the app
        Go to `<LOCALHOST>:3000` in the browser and enjoy.
    
    2. NodeJs not installed, Docker available
        If nodejs is NOT installed on the machine(or you simply want to run the app in a Docker container), you can 
        build the image by runnng `docker build -t <IMAGE_NAME> .` in the root folder of the app.
        You can than spin up a container with `docker run -p <PORT>:3000 [-d] <IMAGE_NAME>`.
        Go to `<LOCALHOST>:<PORT>` in the browser and enjoy.

