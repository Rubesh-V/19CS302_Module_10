# EX 46 C function to traverse the linked list and display it in the following format.
## DATE:26/03/2026
## AIM:
To write a C function to traverse the linked list and display it in the following format.

## Algorithm
1. Start.
2. Define a variables.
3. Write a functions to traverse the linked list and display it in the following format.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
struct Node{ 
char data;
struct Node *next;
}*head;
void display()
{
struct Node *temp; 
temp=head; 
while(temp!=NULL)
{
printf("%c\n",temp->data); 
temp=temp->next;
}
}
```

## Output:
![image](https://github.com/user-attachments/assets/213ad4a7-297a-4c05-be71-32fe526376be)


## Result:
Thus the program was executed and the output was verified successfully.
