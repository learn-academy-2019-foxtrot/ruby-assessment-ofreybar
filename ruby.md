# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer: A lot of the logic is similar, for example if-else statements are mostly similar to each other. Syntax between ruby and javascript differ heavily, as well as ruby being a more 'logical' language. 
  
  both interperted langauges rather than compiled
  both are dynamic
  both can be programmed functionally
  
  Researched answer: JavaScript and Ruby are object-oriented, dynamic and general purpose scripting language which is interpreted rather than compile during runtime. JavaScript can be used as front-end and back-end language using the same language whereas Ruby is used as back-end programming language
  
  dif: JS is optimized for browser
  dif: Speed during certain task (JS can be faster depending on server)
  dif: JS has const, let, var


2. What is a hash?

  Your answer: Key value pairs, used to store collection of grouped information. 
  represents objects

  Researched answer: It is similar to an Array, except that indexing is done via arbitrary keys of any object type, not an integer index.



3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer: rspec - 
  gem install rspec 
  (in rails)rails generate repec:install.
  get install rspec-rails

  Researched answer: It allows writing tests, checking results and automated testing in Ruby. 



4. Name three possible relationships between objects?

  Your answer: is a, has a, and part of
  has_many, belongs_to

  Researched answer: Object oriented programming generally support 4 types of relationships that are: inheritance , association, composition and aggregation. All these relationship is based on "is a" relationship, "has-a" relationship and "part-of" relationship.



5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer: 

  Researched answer: An instance variable has a name beginning with @, and its scope is confined to whatever object self refers to. Two different objects, even if they belong to the same class, are allowed to have different values for their instance variables



6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) When programs are made, it's made for people to read since we read code much more often than we write code.

2) A style guide is important because it keeps code consistent. Sometimes inconsistancy can be key, but keeping things consistant helps with future versions of the language.

3) Spacing is very important in a language like ruby and is crucial that it is done correctly.

4) __FILE__ . refers to file it is executed in 


7. STRETCH: What are blocks, procs, and lambdas?

  Your answer:

  Researched answer: By using the yield keyword, a block can be implicitly passed without having to convert it to a proc. Procs behave like blocks, but they can be stored in a variable. Lambdas are procs that behave like methods, meaning they enforce arity and return as methods instead of in their parent scope
