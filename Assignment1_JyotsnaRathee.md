

```python
Num_Q1=[]
for x in range(2000, 3200):
    if (x%7==0) and (x%5!=0):
        Num_Q1.append(str(x))
print (','.join(Num_Q1))
```

    2002,2009,2016,2023,2037,2044,2051,2058,2072,2079,2086,2093,2107,2114,2121,2128,2142,2149,2156,2163,2177,2184,2191,2198,2212,2219,2226,2233,2247,2254,2261,2268,2282,2289,2296,2303,2317,2324,2331,2338,2352,2359,2366,2373,2387,2394,2401,2408,2422,2429,2436,2443,2457,2464,2471,2478,2492,2499,2506,2513,2527,2534,2541,2548,2562,2569,2576,2583,2597,2604,2611,2618,2632,2639,2646,2653,2667,2674,2681,2688,2702,2709,2716,2723,2737,2744,2751,2758,2772,2779,2786,2793,2807,2814,2821,2828,2842,2849,2856,2863,2877,2884,2891,2898,2912,2919,2926,2933,2947,2954,2961,2968,2982,2989,2996,3003,3017,3024,3031,3038,3052,3059,3066,3073,3087,3094,3101,3108,3122,3129,3136,3143,3157,3164,3171,3178,3192,3199



```python
first_name = input("Enter your First Name : ")
last_name = input("Enter your Last Name : ")
print ("Hello  " + last_name + " " + first_name)
```

    Enter your First Name :  Jyotsna
    Enter your Last Name :  Rathee


    Hello  Rathee Jyotsna



```python
pi = 3.1415926535897931
diameter=12
radius= diameter/2
Volume= 4.0/3.0*pi* radius**3
print('The volume of the sphere is: ',Volume)
```

    The volume of the sphere is:  904.7786842338603



```python
valuesForList = input("Enter some comma seprated numbers : ")
list = valuesForList.split(",")
print('List : ',list)
```

    Enter some comma seprated numbers :  23,34,45,56,67,7889,90,12


    List :  ['23', '34', '45', '56', '67', '7889', '90', '12']



```python
n=5;
for i in range(n):
    for j in range(i):
        print ('* ', end="")
    print('')
for i in range(n,0,-1):
    for j in range(i):
        print('* ', end="")
    print('')

```

    
    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    * * * * 
    * * * 
    * * 
    * 



```python
wordToBeReversed = input("Input a word to reverse: ")

for char in range(len(wordToBeReversed) - 1, -1, -1):
  print(wordToBeReversed[char], end="")
print("\n")
```

    Input a word to reverse:  AcadGild


    dliGdacA
    



```python
print("WE, THE PEOPLE OF INDIA, \n\thaving solemnly resolved to constitute India into a SOVEREIGN, ! \n\t\tSOCIALIST, SECULAR, DEMOCRATIC REPUBLIC \n\t\t and to secure to all its citizens ")
```

    WE, THE PEOPLE OF INDIA, 
    	having solemnly resolved to constitute India into a SOVEREIGN, ! 
    		SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC 
    		 and to secure to all its citizens 



```python

```
