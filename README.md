# python
        print('hello world') 
        print("hello world")

# Escape Sequences
        \'  single quote
        \"  double quote
        \\  backslash
        \n  new line
        \t  tab
        \b  balckspace
# Emoji 
        go to this website 
        https://unicode.org/emoji/charts/full-emoji-list.html
        copy emoji code and print in your program
        then replace + with 000 and start of emoji code add \
        emoji code: U+1F600 
        print("\U0001F600")
# Calculation
        print(2+3*4)
        print(2/4) # floating point divison
        print(4/2)
        print(4//2)  # integer divison
        print(2//4)
        print(2**3)
        print(2**0.5)
        print(round(2**0.5, 4))
        print(2**3/2*6-4*(3-4/2))
        print(3%2)
        print((2+3)/2)
        2+3 = 5 /2
        print((2+3)*5/2%6)
        5 * 5 / 2 % 6
        25 /2 % 6
        print(12.5 % 6)
        exponents
        print(2**3**2)
        (2**9)
        print(2**9)
# Variables
        Python has five standard data types −

        Numbers
        String
        List : some like arrays
                list = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
                tinylist = [123, 'john']

                print (list)          # Prints complete list
                print (list[0])       # Prints first element of the list
                print (list[1:3])     # Prints elements starting from 2nd till 3rd 
                print (list[2:])      # Prints elements starting from 3rd element
                print (tinylist * 2)  # Prints list two times
                print (list + tinylist) # Prints concatenated lists
        Tuple
                tuple = ( 'abcd', 786 , 2.23, 'john', 70.2  )
                tinytuple = (123, 'john')

                print (tuple)           # Prints complete tuple
                print (tuple[0])        # Prints first element of the tuple
                print (tuple[1:3])      # Prints elements starting from 2nd till 3rd 
                print (tuple[2:])       # Prints elements starting from 3rd element
                print (tinytuple * 2)   # Prints tuple two times
                print (tuple + tinytuple) # Prints concatenated tuple
        Dictionary
                dict = {}
                dict['one'] = "This is one"
                dict[2]     = "This is two"

                tinydict = {'name': 'john','code':6734, 'dept': 'sales'}

                print (dict['one'])       # Prints value for 'one' key
                print (dict[2])           # Prints value for 2 key
                print (tinydict)          # Prints complete dictionary
                print (tinydict.keys())   # Prints all the keys
                print (tinydict.values()) # Prints all the values
# Types of Operator
        Python language supports the following types of operators −

        Arithmetic Operators
        Comparison (Relational) Operators
        Assignment Operators
        Logical Operators
        Bitwise Operators
        Membership Operators
        Identity Operators
# Decesion Making 
        if expression1:
        statement(s)
        elif expression2:
        statement(s)
        elif expression3:
        statement(s)
        else:
        statement(s)