import random
import quotes_for_students
import quotes_for_teachers


print("Welcome to ReDI Quotes Maker")
print("Are you a ReDI Student or a ReDI Teacher?")
print("Type 'bye' to exit")
print("")
while True:
  answer = input("Your answer is: ") 
  answer = answer.lower()
  answer_words = answer.split()
  if answer == "bye":
   print("Bye bye bye")
   break

  if "student" in answer_words:
     from quotes_for_students import quotes_student
     print("")
     print(random.choice(quotes_student))
  elif "teacher" in answer_words:
    from quotes_for_teachers import quotes_teacher
    print("")
    print(random.choice(quotes_teacher))
  elif answer != "bye":
     print("Please type 'teacher', 'student' or 'bye'")
