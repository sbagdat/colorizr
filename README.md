# colorizr

Colorizr is a String class extension of Ruby. It provides some methods to make
command line outputs colorful and sweet.

## Installation

Add this line to your application's Gemfile:

`gem 'colorizr'`

And then execute:

`$ bundle install`

Or install it yourself as:

`$ gem install colorizr`

## Usage

Firstly you need to require it

```rb
require 'colorizr'
``

Then you can start to produce colorful strings in the command line:

```rb
"This is a blue text".blue
"This is a red text".red
"This is a green text".green
"This is a pink text".pink
"This is a light grey text".light_grey
"This is a light blue text".light_blue
```

It also provides two class methods:

```rb
String.colors # return all possible colors as an array
# => [:red, :green, :yellow, :blue, :pink, :light_blue, :white, :black, :light_grey]

String.sample_colors # outputs all color variations
# This is  red
# This is  green
# This is  yellow
# This is  blue
# This is  pink
# This is  light_blue
# This is  white
# This is  black
# This is  light_grey
```

