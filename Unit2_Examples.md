#Sum of n numbers using recursive function
sum = 0
def sumofn(limit):
    if(limit == 0):
        return sum
    else:
        return (limit + sumofn(limit-1))
    
print (sumofn(1))
