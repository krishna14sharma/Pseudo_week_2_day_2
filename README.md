Q21. What is printed? 
 
function show() 
    print(x) 
    x = 20 
 
show() 
 
Q31. Predict the result: 
function increment(x) 
    x = x + 1 
    return x 
 
a = increment(2) 
b = increment(a) 
print(b) 
 
Q32. What’s the final value of x? 
 
x = 10 
function change() 
    x = x + 5 
 
change() 
print(x) 
 
Q33. Trace this code: 
 
val = 2 
 
function mul() 
    val = val * 2 
    return val 
 
print(mul()) 

Q34. Output of this recursive update: 
 
function recUpdate(a) 
    if a > 10 
        return a 
    return recUpdate(a + 2) 
 
print(recUpdate(4)) 

Q35. What is printed? 
function f(a, b) 
    a = a + b 
    b = a - b 
    a = a - b 
    print(a, b) 
 
x = 3 
y = 5 
f(x, y) 
print(x, y)
