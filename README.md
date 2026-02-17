primes=[]
for num in range(2,50):
    for i in range(2,num):
        if num%i==0:
            break
    else:
        primes.append(num)
print(primes)
Output
[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]
