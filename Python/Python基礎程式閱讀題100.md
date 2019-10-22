# 數值計算
```
底下程式執行後, z之值為何?
x = 3
y = 5
z = (x + y) / 2
```
```
答案是:4
```
```
底下程式執行後, 其值為何?
3 / 2
3 // 2
-1 // 2

51 + 122 - 33*42-(44*3)/5
3000000000*3.0
3000000000*3

int(200.2)
int(2e2)
float(200)
```
```
答案是:1.5
1
-1
-1239.4
9000000000.0
9000000000
200
200
200.0
```
### 複數運算
```
3 + 2j - (4 + 4j)
1j*1j
(1 + 2j) * (3 + 4j)

z = 3+5j
z.real
z.imag

import cmath
cmath.sqrt(-1)
```
```
答案是:(-1-2j)
(-1+0j)
(-5+10j)
3.0
5.0
1j
```


```

```


```

```


```

```


```

```




# 字串

```
1.print("3*2*(17-2)")會印出甚麼結果:
(A)0   (B)90  (C)出現錯誤,無法印出  (D)3*2*(17-2)
```
```
答案是(D)
```
```
2.print(3*2*(17-2))會印出甚麼結果:
(A)0   (B)90  (C)出現錯誤,無法印出  (D)3*2*(17-2)
```
```
答案是(B)
```
```
3.print("abc""+""def")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)abc+def  (C)abc""+""def  (D)abcdef
```
```
答案是(B)
```
```
4.print("abc"+"def")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)abc+def  (C)abc""+""def  (D)abcdef
```
```
答案是(D)
```
```
5.底下程式執行後結果為何? 
word = "arttarataaa"
print(word.replace("a", "z",3))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz
```
```
答案是(C)
```
```
6.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z"))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz
```
```
答案是(D)
```
```
7.底下各行輸出為何?
sentence = 'To Be or NOT to Be: that is the question:
print(sentence.upper())
print(sentence.lower())
print(sentence.capitalize())
print(sentence.count('o'))
```
```
答案是:TO BE OR NOT TO BE: THAT IS THE QUESTION: 
      to be or not to be: that is the question: 
      To be or not to be: that is the question: 
      4
```
# while loop
```
7根據底下程式,下列敘述何者為非?[複選題]

names = ['龍', '聖']
index = 0

while index < len(names):
    name = names[index]
    print(name)
    index = index + 1
    
(A)len(names)=2  
(B)names[1]是 龍 
(C)程式執行完後,index最後為2
(D)如果把條件改成 index > len(names),中index最後為2
```
```
答案是(B,D)
```
