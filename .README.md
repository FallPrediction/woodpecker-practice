This is a practice of Woodpecker CI.

In this repository, I use the example codes from [swaggo](https://github.com/swaggo/swag/tree/master/example/basic) to show how to checksum the swagger files using Woodpecker CI.

The penultimate commit will not pass the pipeline because the codes in the main method are only available on GO versions above 1.22.

The last commit will not pass the pipeline because the swagger files haven't been changed along with the swagger comments.

For see more information, please visit my blog post.
