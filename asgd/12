#include <iostream>
#include <cstring>
using namespace std;
struct node
{	char a;
	node *next;
};
int main()
{	char a[50];
	cin>>a;
	int len = strlen(a);
	node *p,*head=NULL,*tail=NULL; 
	for (int i = 0 ; i<len ;i++)
	{	node *q = new node;
		q->a = a[i];
		if (head==NULL)
			head = p = q;
		else
		{	p->next = q;
			p = q;	
		}	 
	}
	p->next=NULL;
	while (head)
	{	cout<<head->a<<" ";
		head = head->next;
	}
 } 
