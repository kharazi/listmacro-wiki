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


### pop_back
	give name of list and delete last value of list

### top
	give name of list and return last value of list in EBX register


### delete
	give name of list and index to delete and delete that index 

### ave
  give name of list and return average of  values of list in EBX register
;
;			min:		give name of list and return minimum value of list in EBX register
;
;			max:		give name of list and return maximum value of list in EBX register
;
;			sum:		give name of list and return sum value of list in EBX register
;
;			QuickSort:	give name of list and sorts list with quick sort alghorithm
;
;			in_sort:	give name of list and sorts list with insertion sort alghorithm
;
;			BubbleSort:	give name of list and sorts list with bubble sort alghorithm
