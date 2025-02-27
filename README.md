# Pre-trained TensorFlow.js models

**Used for Microduino mDesigner**

This repository hosts a set of pre-trained models that have been ported to
TensorFlow.js.

The models are hosted on NPM and unpkg so they can be used in any project out of the box. They can be used directly or used in a transfer learning
setting with TensorFlow.js.

To find out about APIs for models, look at the README in each of the respective
directories. In general, we try to hide tensors so the API can be used by
non-machine learning experts.

For those interested in contributing a model, please file a [GitHub issue on tfjs](https://github.com/tensorflow/tfjs/issues) to gauge
interest. We are trying to add models that complement the existing set of models
and can be used as building blocks in other apps.

## Models

<table style="max-width:100%;table-layout:auto;">
  <tr style="text-align:center;">
    <th>Type</th>
    <th>Model</th>
    <th>Demo</th>
    <th>Details</th>
    <th>Install</th>
  </tr>
  <!-- Images -->
  <!-- ** MobileNet -->
  <tr>
    <td rowspan="10"><b>Images</b></td>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./mobilenet"><div style='vertical-align:middle; display:inline;'>MobileNet</div></a></b></td>
    <td><a href=""></a></td>
    <td rowspan="2">Classify images with labels from the <a href="http://www.image-net.org/">ImageNet database</a>.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/mobilenet</code></td>
  </tr>
  <tr>
    <td><a href="./mobilenet/demo/index.html">source</a></td>
  </tr>
  <!-- ** PoseNet -->
  <tr>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./posenet"><div style='vertical-align:middle; display:inline;'>PoseNet</div></a></b></td>
    <td><a href="https://storage.googleapis.com/tfjs-models/demos/posenet/camera.html">live</a></td>
    <td rowspan="2">A machine learning model which allows for real-time human pose estimation in the browser. See a detailed description <a href="https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5">here</a>.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/posenet</code></td>
  </tr>
  <tr>
    <td><a href="./posenet/demos/camera.html">source</a></td>
  </tr>
  <!-- ** Coco SSD -->
  <tr>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./coco-ssd"><div style='vertical-align:middle; display:inline;'>Coco SSD</div></a></b></td>
    <td><a href=""></a></td>
    <td rowspan="2">Object detection model that aims to localize and identify multiple objects in a single image. Based on the <a href="https://github.com/tensorflow/models/blob/master/research/object_detection/README.md">TensorFlow object detection API</a>.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/coco-ssd</code></td>
  </tr>
  <tr>
    <td><a href="./coco-ssd/demo">source</a></td>
  </tr>
  <!-- ** BodyPix -->
  <tr>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./body-pix"><div style='vertical-align:middle; display:inline;'>BodyPix</div></a></b></td>
    <td><a href="https://storage.googleapis.com/tfjs-models/demos/body-pix/index.html">live</a></td>
    <td rowspan="2">Real-time person and body part segmentation in the browser using TensorFlow.js.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/body-pix</code></td>
  </tr>
  <tr>
    <td><a href="./body-pix/demos/index.html">source</a></td>
  </tr>
    <!-- ** DeepLab -->
  <tr>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./deeplab"><div style='vertical-align:middle; display:inline;'>DeepLab v3</div></a></b></td>
    <td><a href=""></a></td>
    <td rowspan="2">Semantic segmentation</td>
    <td rowspan="2"><code>npm i @tensorflow-models/deeplab</code></td>
  </tr>
  <tr>
    <td><a href="./deeplab/demo/index.html">source</a></td>
  </tr>
  <!-- * Audio -->
  <!-- ** Speech Commands -->
  <tr>
    <td rowspan="2"><b>Audio</b></td>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./speech-commands"><div style='vertical-align:middle; display:inline;'>Speech Commands</div></a></b></td>
    <td><a href="https://storage.googleapis.com/tfjs-speech-model-test/2019-01-03a/dist/index.html">live</a></td>
    <td rowspan="2">Classify 1 second audio snippets from the <a href="https://www.tensorflow.org/tutorials/sequences/audio_recognition">speech commands dataset</a>.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/speech-commands</code></td>
  </tr>
  <tr>
    <td><a href="./speech-commands/demo/index.html">source</a></td>
  </tr>
  <!-- * Text -->
  <!-- ** Universal Sentence Encoder -->
  <tr>
    <td rowspan="4"><b>Text</b></td>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./universal-sentence-encoder"><div style='vertical-align:middle; display:inline;'>Universal Sentence Encoder</div></a></b></td>
    <td><a href=""></a></td>
    <td rowspan="2">Encode text into a 512-dimensional embedding to be used as inputs to natural language processing tasks such as sentiment classification and textual similarity.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/universal-sentence-encoder</code></td>
  </tr>
  <tr>
    <td><a href="./universal-sentence-encoder/demo">source</a></td>
  </tr>
  <!-- ** Text Toxicity -->
  <tr>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./toxicity"><div style='vertical-align:middle; display:inline;'>Text Toxicity</div></a></b></td>
    <td><a href="https://storage.googleapis.com/tfjs-models/demos/toxicity/index.html">live</a></td>
    <td rowspan="2">Score the perceived impact a comment might have on a conversation, from "Very toxic" to "Very healthy".</td>
    <td rowspan="2"><code>npm i @tensorflow-models/toxicity</code></td>
  </tr>
  <tr>
    <td><a href="./toxicity/demo/index.html">source</a></td>
  </tr>
  <!-- * General Utilities -->
  <tr>
    <td rowspan="2"><b>General Utilities</b></td>
  <!-- ** KNN Classifier -->
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./knn-classifier"><div style='vertical-align:middle; display:inline;'>KNN Classifier</div></a></b></td>
    <td><a href=""></a></td>
    <td rowspan="2">This package provides a utility for creating a classifier using the K-Nearest Neighbors algorithm. Can be used for transfer learning.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/knn-classifier</code></td>
  </tr>
  <tr>
    <td><a href="./knn-classifier/demo">source</a></td>
  </tr>
</table>

## Development

You can run the unit tests for any of the models by running the following
inside a directory:

`yarn test`

New models should have a test NPM script (see [this](./mobilenet/package.json) `package.json` and `run_tests.ts` [helper](./mobilenet/run_tests.ts) for reference).

To run all of the tests, you can run the following command from the root of this
repo:

`yarn presubmit`
