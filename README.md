# Ogilvy_Assignment

## Question 1:

## Question 2:

def find_second_largest(input_list):
    # Reverse sorting.
    input_list.sort(reverse=True)
    maxnum = input_list[0]
    
    for i in input_list:
        if i == maxnum:
            continue
        else:
            secondmax = i
            return secondmax
            break


input_list = [10, 20, 30, 40, 40]
result = find_second_largest(input_list)
print(result)

## Question 3:


