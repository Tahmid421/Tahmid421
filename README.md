- #include<iostream>
using namespace std ;


#define size 10
int arr[size], top = -1;



bool isempty()
{
 if(top==-1)
 return true ;
 else
 return false ;

}

  void push(int value)
  {
      if(top==SIZE-1)
      {
       cout<<"Stack is full"<<endl ;
      }
     else
     {
      top++ ;
      arr[top]=value ;
     }

  }
 void pop ()
 {
  if(isempty())
    cout<<"Stack is empty !"<<endl:
   else
   top-- ;
 }

void show_top()
{
 if(isempty())
   cout<<"Stack is empty"<<endl;

 else
 cout <<"Element at top is : "<<arr[top]<<endl;

}
void displayStack()
{
  if(isempty())
  {
   cout<<"Stack is empty !"<<endl;
  }
   else
   {
     for(int i = 0 ; i<=top ;i++)
   cout<<arr[i]<<" ";

   }
}
int main()
{

 push(6);
 pop(8);
 show_top(4);
 displayStack(3);
 return 0 ;
}
👋 Hi, I’m @Tahmid421
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Tahmid421/Tahmid421 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
