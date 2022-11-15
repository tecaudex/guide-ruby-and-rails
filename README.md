# Ruby and Rails guide.

[![N|Solid](https://tecaudex.com/wp-content/uploads/2021/06/logo-tecaudex-02.svg)](https://tecaudex.com)

This guide contains basic to advance level topics required by ruby on rails developer.

## Get to know Ruby 
- What is ruby? 
- How does it get interpreted?
- Ruby code compiled into what?
- What is the IRB (Interactive Ruby)?
- What are RVM  and  RBENV?

## Ruby Essentials

- Variables (local, constant, class, instance, global)
- [Ruby Symbols]( https://medium.com/rubycademy/symbol-in-ruby-daca5abd4ab2) How ruby uses them?
- Strings (:hellow and “hellow” difference)
- String concatenation
- Arrays (operators like +, *, Union, and concat)
- Hashes (Default values, rescue for not find key, keys, values) 
- Loops (For, While)
- Ranges
- Iterators (map, each, reject, select, pick) 
- Enums (prefix and postfix usages)
- Random Numbers (SecureRandom)
- Scope resolution operator
- What are Instance and class methods?
- Instance and class methods (scope)
- Difference b/w self and super
- Different Attributes declaration statements of class and purpose(attr_accessor, attr_reader etc.)
- Typecasting, how is it done in ruby? Methods liks(to_s, to_a ….)
- Difference between kind_of? Instance_of and is_a?
- Mixins --Modules (Extend from self)
- Different between Require, Include, extend and < keyword
- Methods, objects, classes
- Abstraction
- Inheritance
- Method overloading
- method overriding
- polymorphism
- Exception handling (begin, rescue, force method to through exception)
- Uses of ! and ? operators in different places
- Procs
- Lambdas
- Yield, blocks (custom defined blocks, blocks as parameters)

## Advance Ruby
- Freezing an array
- Anonymous classes (initiated by self)
- Meta-Programming (send, public_send, private_send, Method creation, Runtime classes, module, variables declarations)
- Ruby method lookup path
- Regular expressions
- Ruby gems structure
- How to bundle the gem
- How to access different models of the gem
- Require Gem into ruby file
- Parsing Html/Xml with Nokogiri gem


| Ruby Resources |
| ------ |
[https://ruby-doc.org][PlDb] |
[https://www.techotopia.com/index.php/Ruby_Essentials][PlGh] |
[https://rubular.com/][PlGd] |

[Ruby Style Guide](https://rubystyle.guide)

## Web Fundamentals
- What is www?
- What is HTTP?
- What are the sessions (What why and how, storage, access)
- What are the cookies (What why and how, storage, access)
- What is s in HTTP(s)?
- What is encryption? Basic types of encryptions and standard ciphers used by modern web browsers.
- How does a 3-way handshake work?
- How is cypher decided for traffic encryption?
- What is a http request?
- What are the headers?
- Common headers and their use, sending custom headers?
- What are the query parameters, how to send arrays and hashes, strings through these?
- What are the different request variants available by http?
- What are the response formats?
- How can we instruct api to send a particular response which we will accept?


## Hellow to Rails
- What is design Pattern?
- Indepth understanding of how MVC design pattern works?
- What is a rake?
- The difference between API and Web application is rails?
- What are the environments of rails?
- How different environments are bound with resources? (couldn’t find any solution on google)
- Get familiar with the Structure of App folder.
- What are the controllers?
- How controllers, models and views are structured in a rails app?
- Thin controller fat model, and look at ways to reduce the model weights
- Use of namespacing in controllers respecting routing
- Learn about inside out routing



## Concerns
- What are the concerns?
- Difference between model and controller concerns?
- What are the services? 
- How to use custom modules(mixins) and best practices for defining utils like common functions etc..

## Callbacks and ORM

- What is an active record?
- [What are the callbacks?](https://guides.rubyonrails.org/active_record_callbacks.html)
- Difference between model and controller callbacks?
- Can we define custom callbacks?
- Purpose of initializers, config, and lib folders?
- What is an asset pipeline?
- The purpose for assets folders in-app, public and vendor folders?
- What is ORM?
- Active Record Basics
- Learn about Rails database connectivity and respective configurations
- Different DB connectors?
- [Rails migrations?](https://guides.rubyonrails.org/active_record_migrations.html)
- Rails and rake command difference?
- Rails db:setup, create, rollback, migrate, drop etc. commands
- [Rails Query interface](https://guides.rubyonrails.org/active_record_querying.html)
- [Rails relationships](https://guides.rubyonrails.org/association_basics.html)
- [Rails validations](https://guides.rubyonrails.org/active_record_validations.html)

## Routing
- What are the routes?
- What are the restful routes?
- How to define routes with namespaces?
- How to define custom routes with slugs?
- How to define nested routes?
- Difference between member and collection blocks?
- Difference between resource and resources?

## Views and Layouts
- What are the partials?
- What are Rails layouts?
- How many layouts can we define and how?
- How does yield work in views?
- How to render a layout from the controller, different actions, different layout?
- Use of Content_tag, content_for, meta tags
- How to render partials from the controller?
- How to render js from rails?
- How remote: true works on rails?
- Use of Rails cache, and their types?
- How to render different response formats from controller action?

## Background Jobs
- How to write rake tasks?
- Where are these tasks stored?
- How to initiate these tasks?
- What are the delayed jobs?
- How do these jobs get called?
- How does rails manage these jobs?
- How to use Sidekiq
- Introduction to Redis

