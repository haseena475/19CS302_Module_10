# EX 47 C function to insert a node in a linked list.

## AIM:
To write a C function to insert a node in a linked list.

## Algorithm

Start. Define a variables. Write a function to insert a node in a linked list. Read the value using scanf. Ask the user to make an input. Print out the answer. End

## Program:
```
/*
C function to insert a node in a linked list.
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void insert(char data) 
{ 
struct Node *n=(struct Node*)malloc(sizeof(struct Node)); 
struct Node*temp; 
if(head==NULL) 
{ 
head=n; 
n->data=data; 
n->next=NULL; 
temp=head; 
return; 
} 
 
}  
else 
{ 
while(temp->next!=NULL) 
{ 
temp=temp->next; 
} 
n->next=NULL; 
n->data=data; 
temp->next=n; 
} 
}

Developed by: DUDEKULA HASEENA
RegisterNumber: 212222063004  
*/
```

## Output:

<img width="530" height="669" alt="image" src="https://github.com/user-attachments/assets/ebad27c8-aecb-432e-b1ab-0c741a44a482" />


## Result:
Thus the program was executed and the output was verified successfully.
