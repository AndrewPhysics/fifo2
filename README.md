# fifo2
simple fifo data structure
class FIFO includes:

1. data pointer will be responsible for the elements which were placed into the data structure 
2. data pointer is private so this-> is used to access elements
3. put() function handles two situation:
3.1 count>size:
  means that we have to allocate bigger size of memory
3.2 count<size
  simle:
    data[count] = item;
	  count++; 
