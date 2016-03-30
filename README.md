Create a Ruby cheatsheet to help you remember all the new syntax you've learned in the past few days!

+ How do you define variables, instances, constants?
    Variable - def variable
    instance - @variable
    constant - VARIABLE
+ How do you write conditionals?
    == 	equal
    != 	not equal to
    > 	greater than
    < 	less than
    >= 	greater than or equal to
    <= 	less than or equal to 
    elsif = Instead of JS "else if"
    
    if city == "Toronto"
        drinking_age = 19
    else
        drinking_age = 21
    end    
    
+ How do you write arrays, hashes and blocks?
    array = [1,2,3,4]
    
    Hash eg:
    student_ages = {
    "Jack" => 10,
    "Jill" => 12,
    "Bob" => 14
    }
    
    block = Any code surrounded by curly braces, eg:  
    { |x,y| x + y }
    
+ How do you get values from an array?
    ary = [1,2,3,4,5,6]
    ary.include?(3)
+ How do you put values into an array?
    ary = [1,2,3,4,5,6]
    ary.push(7,8,"bob")
+ How do you get values from a hash?
    hash = { "key1" => "value1", "key2" => "value2" }
    hash["key1"]
+ How do you add key-values to a hash?
    h = {}
    h.merge!(key: "bar")
+ How do you get values from a hash that is inside an array?
    array = [
  {
     :standard =>1
     :pass=>{:tamil=>30,:eng=>25,:math=>35},
     :fail=>{:tamil=>10,:eng=>15,:maths=>20}
  },
  {
    :standard =>2,
    :pass=>{:tamil=>40,:eng=>35,:math=>45},
    :fail=>{:tamil=>20,:eng=>25,:maths=>30}
  }
]
    array[0][:pass][:eng]
    array.values
    
+ How do you get values from an array that is a value in a hash?
    stegosaurous = MINES[0][:specimens][1]
    
+ How do you loop through an array?
    arr = [1, 2, 3, 4, 5]
    arr.each { |a| print a -= 10, " " }
    # prints: -9 -8 -7 -6 -5
    #=> [1, 2, 3, 4, 5]

+ How do you loop through a hash?
    hash.each do |key, array|
        puts array
+ How do you create a block?
     # Use for one-liners
    (1..3).each { |i| puts i }
    # 1
    # 2
    # 3

    # Use for multi-line blocks
    (1..3).each do |i|
    a = 2*i
    puts a
    end
    # 2
    # 4
    # 6

+ How do you create a class?
    class ThisIsAClass
+ How do you create methods in a class?
    Class Example
        def move
            @move
        end
        
+ How do initialize constants in a class?
    class Example
        VAR1 = 200
        VAR2 = 100
+ How do you add setters and getters in a class?
    attr_reader :name
    attr_writer :name
    attr_accessor :name
+ How do you create an object from a class?
    eg = Example.new
If you have to hesitate on any of the syntax for these questions, create a cheatsheet!
