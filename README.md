# RubyPractice
*************************************************************************** 

Hello Ruby Outline: 

  

1.1 Introduction to Ruby 

What is Ruby 

Features 

Ruby Gems 

Help on Ruby 

  

-> Ruby i an Object Oriented, Interpreted Scripting Language 

->Dynamic, Opensourse Programming Language 

->It has an Elegant syntax 

->Natural to read and  

->Easy to write 

 

Features 

->Highly portable 

->Runs in any operating syatem 

->Variables have no datatype 

->Automatic memory management  

->Free format language 

->Used for developing Internet and Intra-net applications 

  

Ruby Gems 

->A package manager for Ruby Programming Language 

->A standard format for distributing Ruby programs and libraries 

->Create and publish your own gems 

->For more Information on RubyGems, Visit http://rubygems.org 

  

Help on Ruby 

->For more help or Ruby you can visit 

-> http://www.ruby-forum.com 

-> http://rubyusergroups.org  

-> http://www.ruby-lang.org 

-> http://rubyforge.org 

 

1.2 Installation 

Installation of Ruby through Ubuntu Software Center 

Other Methods to install Ruby 

RVM (Ruby Version Manager) 

Rbenv 

  

  

1.3 Running Ruby Code 

Three ways to Execute Ruby Code 

Example : Hello Word 

From Command line 

->$ruby -e 'puts "Hello World"' 

->$ruby -e 'puts 1+2' 

  

Interractive Ruby 

Allows the execution of Ruby commands with immediate response 

Run Ruby Statements  

Examine the output and return values 

For older version of Ruby, Install irb separately 

$irb 

0>puts "Hello World" 

0>puts 22+33 

0>exit 

 

As a file 

write your code in any text editor 

save as .rb 

brouse the location through terminal  

ruby <filename>.rb 

  

############################Difference between puts and print 

  

puts 'HelloWorld' 

puts "Hello Shiva Rama Krishna" 

  

#commenting Single lines 

puts 'HelloWorld' 

#puts "Hello Shiva Rama Krishna" 

  

#puts 'HelloWorld' 

puts "Hello Shiva Rama Krishna" 

  

  

#commenting multiple lines 

=begin 

puts 'HelloWorld' 

puts "Hello Shiva Rama Krishna" 

=end 

  

*************************************************************************** 

  

2.1 Introduction 

->Ruby and variable Dynamic typing 

->Declaring a variable 

->Changing variable type 

->Converting the var value i.e, to float, string binary etc 

What is variable? 

variable is used to store value 

variable is a reference that can be assigned 

ruby variables are case sensitive 

variable name should be meaningful 

variable name may contain  

Lower case letters 

numbers 

Underscores 

Ex : first_name 

 

Dynamic typing in ruby 

Ruby is a dynamic typed language 

Dont need to declare the data type while creating a variable 

Ruby interpreter determines the datatype at the time of assignment 

 

Declaring a variable 

open terminal 

$irb 

var1=10 

var1.kind_of?integer 

var2 = "shiva" 

 

Converting variable types 

Ruby variable classses have methods to convert their value to a different type  

to_i converts vaiable to Integer 

to_f converts vaiable to float 

to_s converts vaiable to string 

2.7.0 :001 > y=20 

 => 20  

2.7.0 :002 > y.to_f 

 => 20.0  

2.7.0 :003 > y.to_s 

 => "20"  

2.7.0 :004 > y.to_s(2) 

 => "10100"  

2.7.0 :005 > y.to_s(8) 

 => "24"  

2.7.0 :006 > y.to_s(16) 

 => "14"  

2.7.0 :007 >  

  

2.2 Scope of variables 

What is variable scope? 

scope defines where in a program a variable is accessible 

ruby has 4 types of variable scopes 

->Types of variables 

->Global var - begin with $ 

->local var - begin with any alphaabet or _ 

->class var - begin with @@ 

->Instance var - begin with @ 

->constant var - begin with any alphabet 

  

  

  

->What is the variable scope 

2.2 Scope of Variables         

    -What is variable scope 

    -Types of variables 

        Global var 

        local var 

        class var 

        instance var 

        constant var  

  

         

Ruby Methods Outline: 

  

3.1 What is method 

What is method? ->A method is a self contained program executing a specific task 

->Ruby method is similar to functions in any other programming language 

Syntax for method 

->method name should begin with a lower case letter 

->methods should be defined before calling them 

Working  with methods 

Declaring and Calling a method 

#######################method with arguements 

def method_name(arguements) #method definition, arguement = values to be processed 

rubycode 		#body of the method 

end 				#end of the method 

#######################method without arguements 

def method_name() #method definition, arguement = values to be processed 

rubycode 		#body of the method 

end 				#end of the method 

  

#######################some Examples 

############################Addition Without Arguments 

def method1() 

puts"Enter the First number" 

a=gets.chomp.to_i 

puts"Enter the Second number" 

b=gets.chomp.to_i 

sum=a+b 

p sum 

end 

method1() 

  

###############################Addition With Arguments 

  

def add(a,b) 

return a+b 

end 

puts"Enter the First number" 

a=gets.chomp.to_i 

puts"Enter the Second number" 

b=gets.chomp.to_i 

c=add(a,b) 

p c 

######################################################### 

3.2 Passing arguments to a method         

      Explaining the arguments and syntax with example. 

  

3.3 Passing value to a method         

       Explaining the syntax with example. 

  

3.4 Returning value from a method         

        Explaining the syntax with example 

 

 

 

Page Break 

Arithmatic Operators 

Ruby has the following Arithmatic Operators 

+ 	Addition 		ex: a+b 

- 	Subtraction 		ex: a-b 

* 	Multiplication 		ex: a*b 

/ 	Division 		ex: a/b 

** 	Exponent 		ex: a**b 

% 	Modulus 		ex: a%b 

 

Relational operators 

== 	Equals to				ex: a==b 

.eql? 	Equals to 				ex: a.eql?b 

!= 	not equal to				ex: a!=b 

> 	Greater than				ex: a>b 

< 	Less than				ex: a<b 

<= 	Lessthan or equal to			ex: a%b 

>= 	Greater than or equal to		ex: a%b 

<=> 	Combined Comparision 			ex: a<=>b 

The combined comparision operator returns 0 when a = b 

The combined comparision operator returns 1 when a > b 

The combined comparision operator returns -1 when a < b 

 

Operator Precedence  

{ }      (  )		1st(Highest Priority) 

* /  % 			second priority 

+ - 			third priority 

<, <=, >, >=		forth priority 

=, ==, != 		fifth priority 

 

 
