# Useless talk

This are the slides for my talk on Esoteric languages.

## Usage

The slides are ment to be used with the gem vimdeck:

first install vindeck with:

`bundle`

them to genrate the slides: 

`bundle exec vimdeck generate slides.md`

and to strat the presentation:

`bundle exec vimdeck open`

## Demos

The talk have two demo file:

`demo_01` an example of polyglot file containing three valid programs in `ante`, `brainfuck` and `whitespace` to test each of them:

 * `ruby ante/ante.rb demo_01`
 * `ruby brainfint/src/brainfuck.rb demo_01`
 * `ruby whitespacers/ruby/whitespace.rb demo_01`

`demo_02.js` contains an example of esotreric Javascript and can be executed with:

 * `node demo_02.js`

## Clone the repo

To clone the repo with the submodules:

`git clone --recurse-submodules git@github.com:internetblacksmith/useless_talk.git `

## Usefull Links:

[Esolang Wiki](https://esolangs.org/wiki/Language_list)
[Make JS esoteric](http://patriciopalladino.com/blog/2012/08/09/non-alphanumeric-javascript.html)
[Rockstar Language](https://www.youtube.com/watch?v=uNjp0gS8x_k)