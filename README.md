# Video Doorbell, Lab 7

*A lab report by John Q. Student*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**  
[video](https://youtu.be/zES3uVOEIlo)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**  
add *takePicture();* to the code.

**b. Include a video of your working video doorbell**  
I forgot to shot a video for this, but it can be seen from the part C video.[video](https://youtu.be/2JrgU8yCLsE)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**  
I try to use google cloud vision api[https://www.npmjs.com/package/@google-cloud/vision] to add tag to identify object in an image. When I install libraryies, I tried a lot, but lots of them failed, maybe because they cannot work with the raspberey pie well. 

**b. Upload a video of your working modified project**
[video](https://youtu.be/2JrgU8yCLsE)
