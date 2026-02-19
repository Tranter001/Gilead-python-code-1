#This is the game designed to predict an answer correctly based on the questions asked.

x1=input('Hello, I am Gilead\'s game, designed to predict your thinking, hope you will enjoy the game. Press Enter to continue: ')

def execute():
    x2=input('For starting, please guess any positive number (not zero) on your mind and do not tell me or anyone, keep it a secret, if ready press Enter: ')
    x3=input('Take that number and add it by itself, example if you guessed 1, now take 1+1, if you guessed 2, take 2+2, e.t.c..., keep the answer a secret in your head, If ready Press Enter: ')
    x=eval(input('Now tell me any number of your favourite, like number of people in your family, your age etc... :'))
    x4=input('Now take that number of your favourite, multiply by the previous latest answer after adding your guessed number by itself, still keep a secret in your mind, press enter when done: ')
    x4=input('After doing so, take your last answer divide it with the number you guessed at first step, remember to keep it still a secret in your mind press enter when done: ')
    x5=input('Here comes magic of this game, I will predict your last answer, press enter if ready: ')
    print('Your answer is ', 2*x)
execute()

def choice():
    response = input('I hope I guessed right, and I am correct, \'yes\' or \'no :')
    if response == 'yes':
        print('Thanks for enjoying the game. Goodbye')
    elif response == 'no':
        x6=input('There is some place in your calculation you were wrong, lets do again press enter to start again: ')
        execute()
        print('I guess I\'m right, if wrong again, there is problem with your arithmetics, or you guessed negative interger or zero, Thanks for trying me, Goodbye..!!')
    else:
        print('GAME OVER..!!, make sure your answer is in lowcase later only, type Either \'yes\' or \'no , now restart the game.')

choice()
