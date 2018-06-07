# Ruby

0. ####  개요

    1. #####  루비는 순수 객체 지향 언어이다.

    2. ##### 모든것이 객체이다.

    3. ##### Ruby  on Rails 덕분에 유명해짐.

1. #### puts VS print

   ```ruby
   3.times {print "hello"} # -> hellohellohello => 3 
   3.times {puts "hello"} # -> hello
   					   #	hello
   					   #	hello
    					   #	=> 3 
   
   ```





2. #### P vs Puts

```ruby
a="hello"
puts a #->hello
p a #->"hello"

```

3. #### Naming conventions

   1. 변수
      1. snake_case
      2. 상수
         1.  canstant
      3. 클래스 
         1. camelcase

4. #### pry

   설치

   ​	`gem install pry`

   실행

   ​	pry

5. #### Inline statement

   ```ruby
   # if 문
   puts "a=0" if a==0 #"a=0"
   puts "a=0" if a==1 # 결과 없음
   #while 문
   c=0
   c +=2 while c<50 # 50
       
   false / nil을 제외한 모두는 true    
   ```

   

6. case

7. 

   ```ruby
   
case name
       when "chang2" then puts "hi chang2"
           when "tak" then puts "hi tak"
           else put "hi"
           end
       
   ```

   

7. 





