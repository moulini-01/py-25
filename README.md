# py-25
printing DNA shaped pattern
n=5
for k in range (n):
    for i in range(n):       
        for j in range(n):
          if(i==j or j==n-i-1):
             print("*",end=" ")    
          else:
            print(" ",end=" ")
        print()
