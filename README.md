# program-to-check-whether-the-given-integer-is-a-prime-number-or-not
num = int(input(&quot;Enter an integer: &quot;))
isprime = 1 #assuming that num is prime
for i in range(2,num//2):
if (num%i==0):
isprime = 0
break
if(isprime==1):
print(num, &quot;is a prime number&quot;)
else:
print(num, &quot;is not a prime number&quot;)
