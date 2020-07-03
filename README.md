o=int(input())                                                                                                                                                            
l=[1]                                                                                                                                                                
q=[2]                                                                                                                                           
b=[]                                                                                                                                                                   
n=1                                                                                                                                                                       
m=2                                                                                                                                                                       
p=[1,3,5,7,13]                                                                                                                                                               
for i in range(1,109):                                                                                                                                                    
    n=n+6                                                                                                                                                       
    l.append(n)                                                                                                                                                       
for i in range(2,109):                                                                                                                                          
    m=m+3                                                                                                                                                             
    q.append(m)                                                                                                                                         
for i in range(1,109):                                                                                                                                   
    if (i%6==0):                                                                                                                                                     
      b.append(i)                                                                                                                                                
for i in range(o):                                                                                                                                                        
    k=int(input())                                                                                                                                                        
    if k in b:                                                                                                                                                            
        a=b.index(k)                                                                                                                                                   
        if (a%2==0):                                                                                                                                                
          print(k+1,'WS')                                                                                                                                         
        else:                                                                                                                                                           
          print(k+11,'WS')                                                                                                                                              
        elif k in q:                                                                                                                                                           
        if (k%2==0):                                                                                                                                              
            print(k+9,'MS')                                                                                                                                      
        else:                                                                                                                                                     
            print(k+3,'MS')                                                                                                                                          
        else:                                                                                                                                                          
        if (k%2==0):                                                                                                                                                       
            print(k+5,'AS')                                                                                                                                                 
            else:                                                                                                                                                          
            print(k+7,'AS')                                                                                                                                           
#print(q)                                                                                                                                                            
#print(l)                                                                                                                                                       
#print(b)                                                                                                                                                                                                                                                                                                                                           
OUTPUT:                                                                                                                                                                 
2 ws
