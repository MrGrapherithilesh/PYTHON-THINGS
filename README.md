# PYTHON-THINGS
These are the python codes I have built myself without any AI involvement based on my ideas 


******** first code it is a casual health rating thingh go check it out ********
print("Welcome!!!");

name = input("Enter your name:");


while True:
    password = input("Enter your password:")

    if password==name: 
        print("welcome back",name);
        break
    else:
        print("incorrect password");

#...............................................................................
while True:
    height = float(input("Enter your height(in feets 1-11):"))
    
    if 1 <= height <= 11:
       weight = float(input("Enter your weight (in kilograms): "))
       print("Your weight is:", weight)
       break
   
    else:
        human = input("Aren't you a human? (Yes/No): ")
        
    if human.lower()=="yes":
        continue
    else:
                print("I know you are a dog");
                exit()
        

        
#...............................................................................     
  
while True:
    age = float(input("Enter your age:"))
    
    if 0 <= age <= 100:
       #age = float(input("Enter your age: "))
       print("Good your age is:", age);
       break
   
    else:
        print("I know you are eternal for no use")
        exit()

#...............................................................................



  
while True:
    gender = input("Enter your gender:")
    
    if gender in ["male","female"]:
       print("Good:", gender);
       break
   
    else:
        print("Hoo my god your a part of lgbtq+")
        exit()


#...............................................................................


print("Im your online doctor slept during classes so dont relay on me for critical situations");
print("What do you want me to do",name);

#...............................................................................'''

print("===== HEALTH TRACKER ======")
print("1. Symptoms Analyzer"      )
print("2. Calculate BMI"          )
print("3. Health rating"          )
print("4. Exit"                   )

choice = input("Choose an option: ")



if choice == "1":
    SymptomsAnalyzer=input("Enter your symptmos:");
    print("Symptoms entered:",symptoms)


elif choice == "2":
     weight = float(input("Enter your weight (kg):"))
     height = float(input("Enter your height (m):"))

     bmi = weight/(height ** 2);
     print("Your calculated bmi is",bmi)
#...............................................................................
elif choice == "3":
    print("Your age is:",age);
    print("Your gender is:",gender);
    print("Your weight is:",weight);
    print("Your height is:",height);
    
    print("Your health rating is (out of 10):")
    
#...............................................................................  

#...............................................................................
print("Your health rating is:", rating, "/10")
#...............................................................................

elif choice == "4":
    print("Goodbye!")

