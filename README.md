```
#include<stdio.h>
#include<stdlib.h>
#include<math.h>
int main()
{ int A1,A11,A12,last;
	
	float P,V,N,T;
	float R1,R2,M1,M2,s,q;
	float a;
	a = 0.5;
	
	
while(A1!=3)
{	
A1:
	{
	
	printf("\n\n\n\t\t WELCOME TO 2 CHE FORMULA PROGRAM");
	printf("\n\n\n\t 1. Ideal Gas Law Formula");
	printf("\n\t 2. Graham's Law of Diffusivity");
	printf("\n\t 3. Exit");
	printf("\n\n\n Enter the number of your choice: ");
	scanf("%d",&A1);
	{
	if(A1==1)
	{system("cls");
	while (A11!=5)
			{printf("\n\n\t\t Ideal Gas Law Formula");
			printf("\n\n 1. Solve for Pressure (atm)");
			printf("\n 2. Solve for Volume (L)");
			printf("\n 3. Solve for The Number of Moles (mol)");
			printf("\n 4. Solve for Temperature (K)");
			printf("\n 5. Go to Main Menu");
			printf("\n\n\n Enter the number of your choice: ");
			scanf("%d",&A11);
			{
			if(A11==1)
			{system ("cls");
			
				{printf("\n\n\t\t SOLVING FOR PRESSURE");
				 printf("\n Enter the value of the following");
				 printf("\n\t Volume:");
				 scanf("%f",&V);
				 printf("\n\t Number of Moles: ");
				 scanf("%f",&N);
				 printf("\n\t Temperature: ");
				 scanf("%f",&T);
				 
				 P = ((N*0.08206*T)/V);
				 
				 printf("\n\n Pressure = %2f",P);
				 getch();
				 system("cls");

				}
			}
			else if(A11==2)
			{system ("cls");
			A112:
				{printf("\n\n\t\t SOLVING FOR VOLUME");
				 printf("\n Enter the value of the following");
				 printf("\n\t Pressure:");
				 scanf("%f",&P);
				 printf("\n\t Number of Moles: ");
				 scanf("%f",&N);
				 printf("\n\t Temperature: ");
				 scanf("%f",&T);
				 
				 V = ((N*0.08206*T)/P);
				 
				 printf("\n\n Volume = %2f",V);
				 getch();
				 system("cls");

				}
			}
			else if(A11==3)
			{system ("cls");
			A113:
				{printf("\n\n\t\t SOLVING FOR THE NUMBER OF MOLES");
				 printf("\n Enter the value of the following");
				 printf("\n\t Volume:");
				 scanf("%f",&V);
				 printf("\n\t Pressure: ");
				 scanf("%f",&P);
				 printf("\n\t Temperature: ");
				 scanf("%f",&T);
				 
				 N = ((P*V)/(0.08206*T));
				 
				 printf("\n\n Number of Moles = %0f",N);
				 getch();
				 system("cls");

				}
			}
			else if(A11==4)
			{system ("cls");
			A114:
				{printf("\n\n\t\t SOLVING FOR TEMPERATURE");
				 printf("\n Enter the value of the following");
				 printf("\n\t Volume:");
				 scanf("%f",&V);
				 printf("\n\t Pressure: ");
				 scanf("%f",&P);
				 printf("\n\t Number of Moles: ");
				 scanf("%f",&N);
				 
				 T = ((P*V)/(0.08206*N));
				 
				 printf("\n\n Temperature = %2f",T);
				 getch();
				 system("cls");


				}
			}
			else if (A11==5)
			{system("cls");
			}
			else 
			{printf("\n\n\t OOPS! INVALID NUMBER!");
			system("cls");
			}			
			}
		}

	}
	else if(A1==2)
	{system("cls");
	while (A12 != 5)

	A12:
		{printf("\n\n\t\t GRAHAM'S LAW OF DIFFUSIVITY");
		    printf("\n\nwhere:\n\t R1 = Rate of Molecule 1 (mol/s)\n\t R2 = Rate of Molecule 2 (mol/s)\n\t M1 = Molar Mass of Molecule 1\n\t M2 = Molar Mass of Molecule 2\n");
		    getch();
			printf("\n\n 1. Solve for R1");
			printf("\n 2. Solve for R2");
			printf("\n 3. Solve for M1");
			printf("\n 4. Solve for M2");
			printf("\n 5. Go to Main Menu");
			printf("\n\n\n Enter the number of your choice: ");
			scanf("%d",&A12);
			{if(A12==1)
			{system ("cls");
			A121:
				{printf("\n\n\t\t\t SOLVING FOR R1");
				 printf("\n Enter the value of the following");
				 printf("\n\t R2:");
				 scanf("%f",&R2);
				 printf("\n\t M1: ");
				 scanf("%f",&M1);
				 printf("\n\t M2: ");
				 scanf("%f",&M2);
				 
				q = M2/M1;
				s = sqrt(q);
				R1 = R2*s;
				 
				 printf("\n\n The Rate of The First Molecule = %2f",R1);
				 getch();
				 system("cls");

				}
			}
			else if(A12==2)
			{system ("cls");
			A122:
				{printf("\n\n\t\t\t SOLVING FOR R2");
				 printf("\n Enter the value of the following");
				 printf("\n\t R1:");
				 scanf("%f",&R1);
				 printf("\n\t M1: ");
				 scanf("%f",&M1);
				 printf("\n\t M2: ");
				 scanf("%f",&M2);
				 
				q = M1/M2;
				s = sqrt(q);
				R2 = R1*s;
				 
				 printf("\n\n The Rate of The Second Molecule = %2f",R2);
				 getch();
				 system("cls");

				}
			}
			else if(A12==3)
			{system ("cls");
			A123:
				{printf("\n\n\t\t\t SOLVING FOR M1");
				 printf("\n Enter the value of the following");
				 printf("\n\t R1:");
				 scanf("%f",&R1);
				 printf("\n\t R2: ");
				 scanf("%f",&R2);
				 printf("\n\t M2: ");
				 scanf("%f",&M2);
				 
				q = (R2/R1)*(R2/R1);
				M1 = q*M2;
				 
				 printf("\n\n The Molar Mass of the First Molecule = %2f",M1);
				 getch();
				 system("cls");

				}
			}
			else if(A12==4)
			{system ("cls");
			A124:
				{printf("\n\n\t\t\t SOLVING FOR M2");
				 printf("\n Enter the value of the following");
				 printf("\n\t R1:");
				 scanf("%f",&R1);
				 printf("\n\t R2: ");
				 scanf("%f",&R2);
				 printf("\n\t M1: ");
				 scanf("%f",&M1);
				 
				q = (R1/R2)*(R1/R2);
				M2 = q*M1;
				 
				 printf("\n\n The Molar Mass of the Second Molecule = %2f",M2);
				 getch();
				 system("cls");

				}
			}
			else if(A12==5)
			{system("cls");
			}
			else 
			{printf("\n\n\t OOPS! INVALID NUMBER!");
			system("cls");
			}
			}
		}
	}
	else if(A1>3)
	{printf("\n\t\t OOPS! INVALID NUMBER!");
	getch();
	system("cls");
	}
	}
	}
}
system("cls");
printf("\n\n\n\n\t\t\t\t GOODBYE!!!!\n\n\n\n");	
	
system ("PAUSE");
return 0;
}
```
