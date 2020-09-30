## 會產生無窮迴圈
```
i=1
while i < 3:
 print(i)
i+=1 #這裡在做 i=i+_1

print("abc")
```
會出現無限的數字1，因為只執行到 print(i) 那行，然後又回到 while 那行，稱無窮迴圈


## 
```
i=1
while i < 3:
 print(i)
i+=1 #這裡在做 i=i+_1

print("abc")
