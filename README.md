# Python-02
# Easy Quiz Game
print("Welcome to the quiz game!\n)
score = 0
# Question 1
print("1. what is the capital of India ?")
print("a) Delhi")
print("b) Paris")
print("c) Tokyo")
answer1 =input ("enter your answer(a/b/c): ")
if answer1.lower()=="a":
   print("Correct🎉!\n")
   score +=1
else:
  print("Wrong👎!the correct answer is a) Delhi\n")
# Question 2
print("2. what is square of 15?")
print("a) 256")
print("b) 252")
print("c) 225")
answer2= input ("enter your answer(a/b/c): ")
if answer2.lower()==:"c":
    print("Correct🎉!\n")
    score +=1
else:
    print("Wrong👎! the correct answer is c) 225")
# Question 3
print("3. Which animal is known as 'ship of desert'?")
print("a) lion")
print("b) camel")
print("c) cheetah")
answer3= input("enter your answer(a/b/c): ")
if answer3.lower()==:"b":
    print("Correct🎉!\n")
    score +=1
else:
    print("Wrong👎! the correct answer is b) camel")
# final result
print("Your final score is:", score,"/3")
    
