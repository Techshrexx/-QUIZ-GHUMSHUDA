/*so here we are going to develop a quiz game using the python.*/ 
print('Welcome to the quiz')
answer = input(" Are you ready to play the quiz ? yes/no  ”)
total_score=0
total_questions =5

if answer=='yes' :
print('Lets start playing')
else: 

print('thank you for participating')
if answer =='yes':
answer= input('What is the national capital of INDIA?') 
if answer=='new delhi':
print('correct answer')
total_score += 1
else:
print('Wrong Answer')

answer = input("On which date the CHANDRAYAAN 3 mission has been launched ?”,)

if answer=='14 july, 2023':

print('correct answer')
total_score +=1
else:
print('OOPS! ! Wrong answer') 
answer = input('Which is the most known and used language in field of AIML?',)

if answer=='python':
print('Correct answer')
total_score+=1
else:
print('OOPS!! Wronng answer')
answer = input('In which year the python language has been developed?',) 40
if answer=='1989':
print('Good job , Correct answer')
total_score +=1
else:
print('Sorry Wrong answer') 46

answer= input('From which famous show THE PYTHON got its name?',) 49
if answer=='monty python flying circus':
print('Great job , You answered it right')
total_score = total_score + 1
else:
print('OOPS! ! Wrong answer')




print(“Thank you for answering the question and for being a part of this quiz“)
total_mark =	(total_score/total_questions)*100

print('The total marks you obtained is',total_mark)
print('BYE')





















