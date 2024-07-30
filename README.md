# recsys23-tutorial
Welcome to the page of our tutorial on Recommendender systems in the Wild. 

# Abstract
Building a recommender system, from the initial idea, implementation, and offline evaluation to running a system where users will receive quality recommendations, is a long process with many practical considerations. A recommender model that produces close to state-of-the-art metrics in an offline evaluation is only a small step in creating a recommender system and often not the most important. This gap between training a recommender model and having a recommender system in production is a topic often neglected and will be the focus of this tutorial.

We will start looking at the goal of recommender systems from the perspective of different use cases and see how those correspond with the traditional evaluation metrics. Using those and others beyond accuracy metrics and the data, we will look into how we can develop the best candidates for online testing. During this process, we will also discuss good experimental practices.

The second part of this tutorial will look at how to take those model/system candidates and test them in production using A/B testing, Bayesian A/B testing, and Bayesian bandits. We will also provide some considerations on the cost of applying one model compared to the other. For these practical steps, we will further provide simple, applicable code in notebooks as part of the tutorial.

##OUTLINE
Part 1:
* What is a recommender in the wild
* Developing the Recommender
* Business considerations when deploying a recommender
* Beyond accuracy – what metrics are interesting
* Personalisation and the Myth of Long Sessions
* RecSysOps
Part 2:
* A/B testing
* Bayesian AB-testing
* Bayesian Bandits for AB-testing
* Handling recommenders in production

Slides:
* part 1: [link](https://www.dropbox.com/scl/fi/2a3zlqetpb5tujcw6173a/kim-falk-at-recsys23.pdf?rlkey=hp7gbz3vdt8jvu689uxddui9v&st=wlesix4m&dl=0)
* part 2: [link](https://github.com/Arngren/bayesian-ab-test/blob/main/pdf/Tutorial%20-%20Bayesian%20AB-testing.pdf) (have a look at Mortens Bayesian A/B-testing repo [link](https://github.com/Arngren/bayesian-ab-test/tree/main))

Link to a video of the presentation will be added as soon as it is available. 

