# starterkit-mustache-acidtest
Acid test patterns for [Pattern Lab](http://patternlab.io/).

This project started out as a way of reproducing combinations of PatternLab features that, when processed with [Pattern Lab / Node](https://github.com/pattern-lab/patternlab-node) were leading to unexpected results.

The official PatternLab docs didn't categorically specify what should happen in those scenarios, so it wasn't clear if these were bugs or correct behaviour. To aid discussion and investigation, it was useful to create some patterns that reproduce these situations as simply as possible and thus this project was born.

As these issues are clarified or fixed, this project can be updated accordingly and serve as a regression test to ensure they don't recur. Similarly, this project could be used as a compatibility test for the various Pattern Lab ports. Ideally, they should all produce the same results from the same input patterns.

The Pattern Lab maintainers liked this idea and [have voted on creating an "acid test" starter kit](https://github.com/pattern-lab/the-spec/issues/23) for that very purpose. :-)


## Setup
You should be able to install this starter kit via your preferred Pattern Lab / Node Edition. For instance, with the [Gulp edition](https://github.com/pattern-lab/edition-node-gulp), you can do:

* `npm install c1rrus/starterkit-mustache-acidtest`
* `gulp patternlab:loadstarterkit --kit=starterkit-mustache-acidtest`

