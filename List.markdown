#List Macros Documention 


### list
	give name and size of list 
	 
#### Example
	list    mylist , 100

### append 
	give name of list and value for append 
	and append value to end of list 
#### Example
	append 	mylist , 10 

	
### len 
	give name of list and move len of list to EAX register 
	
#### Example 
	len 	mylist 
	
	after run this line: len --> EAX  
	
### find 
	give name and value of list and search value in list 
	move index of value to EBX register 
	if value not exists in list move -1 to EBX register 
### Example 
	find  mylist, 11 
	after run this line:   index of value in list --> EBX 
### get 
	
	give name of list and index and move value of this index to EBX register
	if index > len output this error : "index > len "
#### Example 
	get  mylist , 5 
	
	after run this line:   value of this index --> EBX 

### show 
	show all of list's item s 


####