#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
#include<process.h>
#include<string.h>

int password()
{
int k,pass;
char p1,p2,p3,p4,p5,p6,p7,p8,p9,p10,p11;
for(k=3;k>0;k--)
{

printf("\n\n\n  Enter your Password:-");
p1=getch();
printf("*");
p2=getch();
printf("*");
p3=getch();
printf("*");
p4=getch();
printf("*");
p5=getch();
printf("*");
p6=getch();
printf("*");
p7=getch();
printf("*");
p8=getch();
printf("*");
p9=getch();
printf("*");
p10=getch();
printf("*");
p11=getch();
printf("*");
if(((p1=='m')||(p1=='M'))&&((p2=='e')||(p2=='E'))&&((p3=='s')||(p3=='S'))&&((p4=='s')||(p4=='S'))&&(p5=='@')&&((p6=='j')||(p6=='J'))&&((p7=='a')||(p7=='A'))&&((p8=='y')||(p8=='Y'))&&((p9=='e')||(p9=='E'))&&((p10=='s')||(p10=='S'))&&((p11=='H')||(p11=='h')))
{
printf("\n\n\n\n  Correct Password......Press any key to continue");
getch();
pass=1;
break;
}
else
{
printf("\n\n\n\n  Incorrect Password......Press any key");
printf("\n\n  Trials Remaining:- %d",k-1);
getch();
pass=0;
}
}
return(pass);
}


void menu()
{
  int i,j,k,m;
  char l;

  printf(" welcome to hostel\n");
  printf(" menu:enter your choice\n");


  cal :
  printf(" enter\n 1)breakfast\n 2)Meal\n 3)snacks\n \n");
  scanf("%d",&i);

  switch(i)
 {
   case 1:
   printf("1.aloo paratha\n");
   printf("2.chai\n");
   printf("3.maggi\n");
   printf("4.bread jam\n");
   printf("\n");

   printf(" do you want anything else type y or n \n");
   scanf(" %c",&l);
   if(l=='y')
   goto cal;
   else
   exit(1);
  case 2:

     printf("enter 1)monday\n2)tuesday\n3)wednesday\n4)thursday\n5)friday\n6)saturday\n7)sunday\n");
     scanf("%d",&j);

     if((j==1)||(j==3)||(j==5))
     printf(" you will get:vegetable curry,roti,daal, rice and salad\n");

     if((j==2)||(j==6))
     printf(" you will get: paneer curry,daal tadka,tandoori roti,pulaav\n");

     if(j==7)
     printf(" you will get : daal bati,ladoo and salad\n");
     printf("\n do you want anything else type y or n \n");
   scanf(" %c",&l);
   if(l=='y')
   goto cal;
   else
   exit(1);
     break;
  case 3:

   printf(" snacks:1)pizza\n2)samosa\n3)chaat\n4)lassi\n5)panipuri\n6)maggi\n");
   printf(" do you want anything else type y or n \n");
   scanf(" %c",&l);
   if(l=='y')
   goto cal;
   else
   exit(1);
   break;


  default:
  printf("invalid choice\n");
}
}


void student()
{
char j[12],y[50];
int u=0,v,r,s,t,w;
char x[8][50]={
       "akanksha",
       "ashi",
       "jayesh",
       "arpit",
      };

printf("\n\n 1.Add New Student");
printf("\n\n 2.Search Student Information");
printf("\n\n 3.Display All Information");
printf("\n\n 4.Remove Data");
printf("\n\n 5.Exit from Student Database");
printf("\n\n\n Enter your choice :- ");
scanf("%d",&w);

switch(w)
 {
  case 1:
  printf("enter the number of names to be added\n");
  scanf(" %d",&u);
  printf(" enter the names\n");
  for(v=4;v<=4+u;v++)
  {
    gets(x[v]);
  }
  printf(" the final list is\n");
 for(v=0;v<=4+u;v++)
 {
   puts(x[v]);
 }
 break;

  case 2:

  printf("enter your name\n");
  gets(y);
  for(r=0;r<=3;r++)
  {
    s=strcmp(y,x[r]);


  if(s==0)
    {
     t=2;
     break;
    }
}
  if(t==2)
  printf("you are registered");
  else
    printf(" sorry you are not registered\n");
    break;

 case 3:
    printf("list of students: \n");
    printf("\n",x[10][50]);
    break;

  case 4:
   printf("enter a name");
   gets(j);
   printf("entry has been deleted");
   break;

  case 5:
   break;

  default:
   printf("\n\n You have entered a wrong choice");
 }
}

void rates()
{
int choice,num,ans;


     printf("choices available :\n");
     printf("1. 1 time meal\n");
     printf("2. 2 time meal\n");
     printf("3. include breakfast with 1 time meal packs\n");
     printf("4. include breakfast with 2 time meal packs\n");
     printf("5. thali \n");
     printf("6. special thali ");
     printf("\n");
     printf("choose your prefrence to know final prices\n");
     scanf("%d",&choice);


     switch(choice)
     {
      case 1:
      printf("thank you \n you have to pay 1200 Rs");
      break;

      case 2:
      printf("thank you \n you have to pay 2200 Rs");
	break;

	case 3:
	printf("thank you \n you have to pay 1500 Rs");
	break;

	case 4:
	printf("thank you \n you have to pay 2500 Rs");
	break;

	case 5:
	printf("enter number of thali ");
	scanf("%d",&num);
	ans=num*50;
	printf("thank you \n you have to pay %d",ans);
	break;

	case 6:
	printf("enter number of thali");
	scanf("%d",&num);
	ans=num*70;
	printf("thank you \n you have to pay %d",ans);
	break;


     }


}

void about()
{
  printf("Test the best,RB mess. we provide best quality food with affordable price.\n We take care of your hygiene and maintain proper cleanliness.\n our serving timings are as follows:\n" );
  printf("11:00Am to 3:00pm  -   morning.\n");
  printf("7:00 Pm to 10:00Pm -   evening. \n");
  printf("Note that we do not serve at sunday evenings and are closed on all national holidays\n");
}

void main()
{
  char a,pass;
  clrscr();
  printf("\n********************************************************************************");
  printf("********************************************************************************");
  printf("\n  W       W       W  EEEEEE L      CCCCCC OOOOOO  M               M  EEEEEE");
  printf("\n  W      W W      W  E      L      C      O    O  M M           M M  E");
  printf("\n  W     W   W     W  E      L      C      O    O  M  M         M  M  E");
  printf("\n  W    W     W    W  EEEEEE L      C      O    O  M   M       M   M  EEEEEE");
  printf("\n  W   W       W   W  E      L      C      O    O  M    M     M    M  E");
  printf("\n  W  W         W  W  E      L      C      O    O  M     M   M     M  E");
  printf("\n  W W           W W  E      L      C      O    O  M      M M      M  E");
  printf("\n  W               W  EEEEEE LLLLLL CCCCCC OOOOOO  M       M       M  EEEEEE");
  printf("\n\n********************************************************************************");
  printf("********************************************************************************");
  getch();
  password();
  if(pass==0)
  {
	  exit(0);
  }
  do
  {

  printf("\n\n\t\t\t RB MESS MANAGEMENT SYSTEM");
  printf("\n\t\t\t ^^^^^^ ^^^^ ^^^^^^^^^^ ^^^^^^");
  printf("\n\n Enter Your Choice -");
  printf("\n\n 1.Menu");
  printf("\n\n 2.Student Record");
  printf("\n\n 3.rates");
  printf("\n\n 4.About Our mess\n");
  printf("\n\n 5.Exit");
  printf("\n\n Enter Your Choice :- ");
  fflush(stdin);
  scanf("%c",&a);
  if(a=='1')
  {
	  menu();
  }
  else if(a=='2')
  {
	  student();
  }
  else if(a=='3')
  {
	 rates();
  }
  else if(a=='4')
  {
   about();
  }
  else if(a=='5')
  {
  exit(0);
  }
  else
  {
  printf("\n\n You have entered a wrong choice");
  }
  }while(1);
  getch();
}
