# python-2.01-data-types

  1. Fork this repository
  2. Check out your fork
  3. Make a branch and switch to it
  4. Add your answers to this file, each one surrounded by triple backquotes, like so:
    ```
    This is my answer
    ```
  5. Commit your answers to your branch
  6. Push your branch to origin
  7. Do a Pull Request against `master` in your repository
  8. Merge the pull request.
  9. Paste the link to your repository in your assignment in online.theironyard.com

## Answers go below
```
1. taxRate = .0825
```
```
2.  taxRate * 34.50
```
```
3. totalamount=(30+24+15)*taxRate
```
```
4.  name = "scott"
```
```
 5. greeting = "dia duit, conas ata tu "
 ```
 ```
6. In [16]: greeting + name
   Out[16]: 'Dia duit, conas ata tu, scott'
```
```
7. In [26]: greeting+name+pleasepay+str(totalamount)
   Out[26]: 'Dia duit, conas ata tu,  scottTotal amount due:5.3625'
```
---------------------------------------------------------------------------------------

```
1. In [2]: namesOfFriends = ['Zachary Soliz','Xwan Lim','Arin Jeager','Scott Pilgrim','James Bond']
```
```
2. In [6]: states = {'Tx': 'Texas', 'Ar': 'Arizona', 'Fl': 'Florida', 'Ny': 'New York', 'Ca': 'California'}
 In [7]: states
 Out[7]:
{'Ar': 'Arizona',
 'Ca': 'California',
 'Fl': 'Florida',
 'Ny': 'New York',
 'Tx': 'Texas'}
 ```
 ```
3. In [9]: population = {'78259': 9342,'78264':7641,'78232':33726}
 ```
 ```
4. censusData = {"1980": {'78259': 7222,'78264':5008,'78232':25000},"1990":{'78259': 8722, '78264':6708, '78232':28000},"2000":{'78259':9222, '78264':8008, '78232':30000}}

 In [13]: censusData
 Out[13]:
 {'1980': {'78232': 25000, '78259': 7222, '78264': 5008},
 '1990': {'78232': 28000, '78259': 8722, '78264': 6708},
 '2000': {'78232': 30000, '78259': 9222, '78264': 8008}}
```
```
5. In [17]: Date = ["April", 18, 2016]
```
```
6. I decided to put my friends in a list. I decided to use full names.
  If had two friends named "john", it would not affect anything because I used full names.
  If I had two friends with the same name would have to receive a marker like John1 and john2.
```
```
7.Rather than choosing one over the other I would create a dictionary and use the abbreviation as the Key and the proper name as the value.
The data structure would look like this:  
In [6]: states = {'Tx': 'Texas', 'Ar': 'Arizona', 'Fl': 'Florida', 'Ny': 'New York', 'Ca': 'California'}
{'Ar': 'Arizona',
 'Ca': 'California',
 'Fl': 'Florida',
 'Ny': 'New York',
 'Tx': 'Texas'}
 ```
 ```
8. I used a string for the zipcode and an interger for the population. Strings are immutable(I dont want the zipcode to change)and Intergers are mutabale (I may want to change the population later)
```
```
9. I used a String. The data structure is set up to allow for the search of the popultion of a specific zipcode based on the census year.
```
```
10. the Iso standard is to Display dates as "YYYY-MM-DD, YYYYMMDD
YYYY-MM" I used (april,18,2016) which is probably really bad.
```

------------------------------------------------------------------------------------------------------------------------

```
1. Library= {'fiction':{'Stephen King': ["Tommyknockers", "IT", "Carrie", "The Gunslinger"],'Ray Bradbury':["Farenheit 141","Cellar of Death"]},'nonfiction':{"Stephen Hawking":["A Brief Histroy of Time", "On the Event Horizons of Black Holes"],"Richard Dawkins":["The God Delusion", "This is a book"]}
```
```
2. In [1]: coords = [[2,4],[3,4],[5,6],[3,5]]
```
```
3. Profile = {'info':{"Name": 'Scott Mccann',"b-day":'08031993'},"friends":{'bffs': ['joe','zack','james'],'new':['liza','jane','rose']}}
```
```
4. In [18]: board = [[0,1,2,3,4,5,6,7,8],[1,0,0,0,0,0,0,0,0],[2,0,0,0,0,0,0,0,0],[3,0,0,0,0,0,0,0,0],[4,0,0,0,0,0,0,0,0],[5,0,0,0,0,0,0,0,0],[6,0,0,0,0,0,0,0,0],[7,0,0,0,0,0,0,0,0],[8,0,0,0,0,0,0,0,0]]

In [19]: board
Out[19]:
[[0, 1, 2, 3, 4, 5, 6, 7, 8],
 [1, 0, 0, 0, 0, 0, 0, 0, 0],
 [2, 0, 0, 0, 0, 0, 0, 0, 0],
 [3, 0, 0, 0, 0, 0, 0, 0, 0],
 [4, 0, 0, 0, 0, 0, 0, 0, 0],
 [5, 0, 0, 0, 0, 0, 0, 0, 0],
 [6, 0, 0, 0, 0, 0, 0, 0, 0],
 [7, 0, 0, 0, 0, 0, 0, 0, 0],
 [8, 0, 0, 0, 0, 0, 0, 0, 0]]
```
```
5. In [21]: prison =  {'cellBlock':{'a':{1101:['#6444','#6523'],1102:['#6723','#6734']},'b':{2103:['#6984','#8523'],2104:['#5723','#7734']}}
   ....: }

In [22]: prison
Out[22]:
{'cellBlock': {'a': {1101: ['#6444', '#6523'], 1102: ['#6723', '#6734']},
  'b': {2103: ['#6984', '#8523'], 2104: ['#5723', '#7734']}}}
```
```
6 Library= {'fiction':{'Stephen King': ["Tommyknockers", "IT", "Carrie", "The Gunslinger"],'Ray Bradbury':["Farenheit 141","Cellar of Death"]},'nonfiction':{"Stephen Hawking":["A Brief Histroy of Time", "On the Event Horizons of Black Holes"],"Richard Dawkins":["The God Delusion", "This is a book"]}
}

In [49]: Library['fiction']['Stephen King'][0]
Out[49]: 'Tommyknockers'
```
```
7. In [62]: coords
Out[62]: [[2, 4], [3, 4], [5, 6], [3, 5]]

In [63]: if [2,4] in coords: print('hello')
hello
```
```
8. I would need to wrap the entire dictinary in another dictionary that gives each person a unique ID to support multiple people.
Profile = {"id-01":{'info':{"Name": 'Scott Mccann',"b-day":'08031993'},"friends":{'bffs': ['joe','zack','james'],'new':['liza','jane','rose']}}, "id-02"{'info':{"Name": 'Ryan Mier',"b-day":'08031993'},"friends":{'bffs': ['joe','zack','james'],'new':['liza','jane','rose']}}}
```
```
9. nope :P (took the tedious route just to be safe)
```
```
10.In [79]: del prison['cellBlock']['a'][1101][0]

In [80]: prison
Out[80]:
{'cellBlock': {'a': {1101: ['#6523'], 1102: ['#6723', '#6734']},
  'b': {2103: ['#6984', '#8523'], 2104: ['#5723', '#7734']}}}
```
