# Ruby Debugging

Welcome to the Ruby Debugging repository. The goal of this repository is to get
you familiar with common debugging tools and idioms. At the end of it I hope you
will have a better understanding of Ruby itself.

Each exercise will present new idioms or reinforce existing ones.

Topics covered:

* [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug)
* ancestors
* singleton_class.ancestors
* methods
* methods.grep
* instance_variables
* instance_methods
* public_methods
* private_methods
* method(:method_name).source_location
* method(:method_name).super_method.source_location
* backtrace
* caller

## Requirements

* Ruby version `2.3` or higher
* `gem install pry-byebug`

## Instructions

1. Clone this repository
2. Work your way through each level, for example:
    * `cd 01/`
    * `ruby main.rb`

## Expected Output

Every solved exercise should include the following output.

```
Framework: Ruby
Version: 2.6.2
Workshop: Ruby debugging
```

## Reading Material

* [Metaprogramming Ruby](https://pragprog.com/book/ppmetr2/metaprogramming-ruby-2)
* [I am a puts debuggerer](https://tenderlovemaking.com/2016/02/05/i-am-a-puts-debuggerer.html)
* [Ruby Debugging Magic Cheat Sheet](https://www.schneems.com/2016/01/25/ruby-debugging-magic-cheat-sheet.html)
* [Debugging Rails Applications](https://edgeguides.rubyonrails.org/debugging_rails_applications.html)

## Contributing

* Open an Issue or Pull Request
* Reach out [@bernardo_amc](https://twitter.com/bernardo_amc) on Twitter
