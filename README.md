# waj_test

from operations import addition

def main(user_input,first_number,second_number):


    if user_input==1:
        response=addition(first_number,second_number)
    return response

if __name__ == "__main__": 
    user_input=int(input('Choose the option\n1.Addition'))
    first_number=int(input('\nPlease enter first number '))
    second_number=int(input('\nPlease enter second number '))

    result=main(user_input,first_number,second_number) 
    print('\n\nThe result is ',result)
    
def addition(a,b):
  return a+b
  
