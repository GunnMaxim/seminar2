def new_line():
    print ('☼')
def three_lines():
    new_line()
    new_line()
    new_line()
def nine_lines():
    three_lines()
    three_lines()
    three_lines()
def clear_screen():
    nine_lines()
    nine_lines()
    three_lines()
    three_lines()
    new_line()


message1 = '9 lines are printed'
message2 = 'Clearing the screen to print 25 more'
message3 = "25 lines printed"


def main():   
    print(nine_lines(), message1)
    print(message2)
    clear_screen()
    print(message3)
if __name__ == '__main__':
    main()