# Real time Sign Language translation using Tensorflow.js
Real time ASL video to text

## Running the code
To use the code, first install the JavaScript dependencies by running  

```
npm install
```

Then start the local budo web server by running 

```
npm start
```

This will start a web server on [`localhost:9966`](http://localhost:9966). 

1. Allow permission to your webcam and microphone. 

2. Add some words you want to train on. 

## Reference
To learn more about the classifier used in this repo go to [KNN Image Classifier](https://github.com/PAIR-code/deeplearnjs/tree/master/models/knn_image_classifier)

There is a newer version of this classifier released in the new [tensorflow.js](https://js.tensorflow.org) which can be found [here](https://github.com/tensorflow/tfjs-models/tree/master/knn-classifier)

## Credit where credit is due:

This project is based on a popular project for Alexa Sign Language Translation: https://github.com/shekit/alexa-sign-language-translator.
 
You can find more info about that in [social media](https://twitter.com/shekitup/status/1017072947624857605), and covered in the press: [BBC](https://www.bbc.com/news/technology-44891054), [Verge](https://www.theverge.com/2018/7/24/17606614/amazon-alexa-echo-mod-sign-language-gestures-ai), [Mashable](https://mashable.com/video/amazon-alexa-sign-language/), [Fast Co](https://www.fastcompany.com/90202730/this-clever-app-lets-amazon-alexa-read-sign-language), [Kottke](https://kottke.org/18/07/making-amazon-alexa-respond-to-sign-language-using-ai), [VentureBeat](https://venturebeat.com/2018/07/24/amazon-alexa-mod-turns-sign-language-into-voice-commands/) and [NowThis](https://www.facebook.com/NowThisFuture/videos/alexa-can-now-understand-sign/2221206704587164/)
