### StyleTransfer

#### What it does
Ever wondered a photo would be look like if it was painted by some famous artist. Well the state of the art deep pearning algorithms has made it possible to achieve these tasks.
This deep learning software does the same.

#### How it works
It takes two input images one is the content image and another one is the style image. The style image is the famous painting and the content image is the picture which we want to convert.
Now to achieve this task I first created a random noise image which is somewhat similar to my original image. 
Now my task is to match the style of the style image but while doing so we have to take care that we also preserve the content of the content image and dont lose it.
Now to do so, I would define two cost functions one will be for the style image and another will be for the content image.
Now I will create the final cost function as the sum of these two cost functions with two hyper parameteres alpha and beta. Alpha and beta will control the amount of style I want in my image.
Now the main task is to reduce this cost function, so we will use optimization algorithm and after few iterations our image will start to transform.
And we will get beautiful results.
Fantastics isn't it.

