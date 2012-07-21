# Cloud Layout

Based on a [Wordle](http://www.wordle.net/)-inspired word cloud layout written
in JavaScript. In progress: extending to work with shapes (like rectangles), not just words.

![Example cloud of Twitter search results for “amazing”](http://www.jasondavies.com/wordcloud/amazing.png)

## Usage

See the samples in `examples/`.

This layout requires [D3](http://mbostock.github.com/d3/).  It’s similar to
[d3.layout.force](https://github.com/mbostock/d3/wiki/Force-Layout), in that
it’s **asynchronous** and **stateful**.
