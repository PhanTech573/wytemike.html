<html></html>
<html>
  <body>
  <p>@@ -1,2 +0,0 @@

--format documentation

--color

 5  

.rspec.json

@@ -0,0 +1,5 @@

$ bundle--format--documentation.json

--"color"

_-$./"" 

"patch-1_gem"

'vitruvius', github: "JoelQ/vitruvius"

 4  

.travis.yml

@@ -1,4 +0,0 @@

language: ruby

rvm:

  - 2.2.3

before_install: gem install bundler -v 1.10.6

 18  

.travis.yml-json.json

@@ -0,0 +1,18 @@

# Installation

Add this line to your application's Gemfile:

gem 'vitruvius', github: "JoelQ/vitruvius"

And then execute:

$ bundle

Usage

require "vitruvius"

require "vitruvius/parser/json_schema"

parser = Vitruvius::Parser::JSONSchema.new(path_to_schema)

app = Vitruvius::App.new(parser).build

# => returns a Sinatra application

language: ruby

rvm:

  - 2.2.3

before_install: gem install bundler -v 1.10.6

 2  

Rakefile → Rakefile.json

@@ -1,4 +1,4 @@

require "bundler/gem_tasks"

patch-1_require"bundler/gem_tasks"

require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec)

 22  

bin/console → bin/console.json

@@ -1,14 +1,22 @@

#!/usr/bin/env ruby

require "bundler/setup"

require "vitruvius"

_-$./""

"usr"

/" "

  bin/" " 

  env ruby_

_

./"require" 

"bundler/setup"

"require" 

#"vitruvius"///***

----#

# You can add fixtures and/or initialization code here to make experimenting

# with your gem easier. You can also use a different console, if you like.

*_-$./"patch-1_"

# (If you use this, don't forget to add pry to your Gemfile!)

# require "pry"

# Pry.start

----$

require "pry"

Pry.start

echo 

test echo build config.json run test echo test

 5  

lib/vitruvius.rb

@@ -1,5 +0,0 @@

require "vitruvius/version"

require "vitruvius/app"

module Vitruvius

end

 13  

lib/vitruvius.rb.json

@@ -0,0 +1,13 @@

patch-1_"require" 

"vitruvius/version_-$./""

"require" 

_-$./"vitruvius"

app-module_patch-1_"/"

./"app"

_-$./

"Vitruvius"

1_"module" 

patch_1""

"end"

"end" returns "end" return #

# => returns a Sinatra application  
    
    
  </p>
  </body>
</html></html>
</html>