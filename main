#include<iostream>
#include<iomanip>
#include<conio.h>
#include<cstdlib>
#include<fstream>
#include<string.h>
#include<stdio.h>
#include<process.h>
using namespace std;

int a[1], b[1], c[1];
char* logname[] ={"UNKOWN","BlueDart","FedEx","Delhivery","DTDC/FirstFlight","Ecom Express","India Post","ATS","Ekart","Aramex"} ;
      char* wbname[] = {"UNKNOWN","Flipkart","Amazon","SnapDeal","PayTM","eBay","ShopClues"};


/*Made By SAMEER KUMAR
Class XII-C
www.sameerkumar.website
All Rights Reserved!
*/

class Expenditures
{
public:
	string categname="";
	int cod, city, log, category, websiteNum, sp, choice1, choice2, f, codfee=0,id;
	float trfee=0.0, mkpfee=0.0, logfee=0.0, l, pkfee=0.0, w, h, tax=0.0, texp, total, exp, x, a, b, fvfee=0.0, t, dedc, inhand;
	

	void finalvfee()
	{

			switch(websiteNum)
		{case 1: switch(category)//Flipkart
			{
							case 1: fvfee=(10*sp)/100; break; 
							case 2: fvfee=(10*sp)/100; break;
							case 3: fvfee=(4*sp)/100; break;
							case 4: fvfee=(8*sp)/100; break;
							case 5: cout<<"This Category Cannot be sold on this Website"; exit(1);
							case 6: fvfee=(10*sp)/100; break;
							case 7: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 8: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 9: fvfee=(10*sp)/100; break;
							case 10: fvfee=(10*sp)/100; break;
							case 11: fvfee=(10*sp)/100; break;
							case 12: fvfee=(10*sp)/100; break;
							case 13: fvfee=(10*sp)/100; break;
							case 14: fvfee=(10*sp)/100; break;
							case 15: fvfee=(10*sp)/100; break;
							case 16: fvfee=(10*sp)/100; break;
							case 17: fvfee=(4*sp)/100; break;
							case 18: fvfee=(5*sp)/100; break;
							case 19: fvfee=(4*sp)/100; break;
							case 20: fvfee=(4*sp)/100; break;
							case 21: fvfee=(4*sp)/100; break;
							case 22: fvfee=(4*sp)/100; break;
							case 23: fvfee=(10*sp)/100; break;
							case 24: fvfee=(8*sp)/100; break;
							case 25: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 26: fvfee=(10*sp)/100; break;
							case 27: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 28: fvfee=(10*sp)/100; break;
							case 29: fvfee=(4*sp)/100; break;
							case 30: fvfee=(10*sp)/100; break;
							case 31: fvfee=(12*sp)/100; break;
							case 32: fvfee=(10*sp)/100; break;
							case 33: fvfee=(10*sp)/100; break;
							case 34: fvfee=(4*sp)/100; break;
							case 35: fvfee=(4*sp)/100; break;
							case 36: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 37: fvfee=(10*sp)/100; break;
							default: cerr<<"Wrong Choice!!"; exit(0);
							} break;

				case 2: switch(category)//SnapDeal
							{case 1: fvfee=(9*sp)/100; break; 
							case 2: fvfee=(9*sp)/100; break;
							case 3: fvfee=(5*sp)/100; break;
							case 4: fvfee=(7*sp)/100; break;
							case 5: cout<<"This Category Cannot be sold on this Website"; exit(1);
							case 6: fvfee=(7*sp)/100; break;
							case 7: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 8: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 9: fvfee=(8*sp)/100; break;
							case 10: fvfee=(10*sp)/100; break;
							case 11: fvfee=(10*sp)/100; break;
							case 12: fvfee=(10*sp)/100; break;
							case 13: fvfee=(10*sp)/100; break;
							case 14: fvfee=(10*sp)/100; break;
							case 15: fvfee=(10*sp)/100; break;
							case 16: fvfee=(10*sp)/100; break;
							case 17: fvfee=(3*sp)/100; break;
							case 18: fvfee=(4*sp)/100; break;
							case 19: fvfee=(5*sp)/100; break;
							case 20: fvfee=(4*sp)/100; break;
							case 21: fvfee=(4*sp)/100; break;
							case 22: fvfee=(4*sp)/100; break;
							case 23: fvfee=(10*sp)/100; break;
							case 24: fvfee=(7*sp)/100; break;
							case 25: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 26: fvfee=(10*sp)/100; break;
							case 27: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 28: fvfee=(10*sp)/100; break;
							case 29: fvfee=(4*sp)/100; break;
							case 30: fvfee=(10*sp)/100; break;
							case 31: fvfee=(12*sp)/100; break;
							case 32: fvfee=(10*sp)/100; break;
							case 33: fvfee=(10*sp)/100; break;
							case 34: fvfee=(4*sp)/100; break;
							case 35: fvfee=(4*sp)/100; break;
							case 36: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 37: fvfee=(9.5*sp)/100; break;
							default: cerr<<"Wrong Choice!!"; exit(0); break;
							} break;



				case 3://Amazon
									if(sp<250)
									{fvfee=0;}

									else if(sp>250&&sp<500)
									{fvfee=5;}
									else if(sp>500)
									{fvfee=10;}
									break;


				case 4:		switch(category)//PayTM
							{
							case 1: fvfee=(7*sp)/100; break;
							case 2: fvfee=(7*sp)/100; break;
							case 3: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 4: fvfee=(7*sp)/100; break;
							case 5: fvfee=(2.5*sp)/100; break;
							case 6: fvfee=(14*sp)/100; break;
							case 7: fvfee=(2*sp)/100; break;
							case 8: fvfee=(5*sp)/100; break;
							case 9: fvfee=(8*sp)/100; break;
							case 10: fvfee=(7*sp)/100; break;
							case 11: fvfee=(7*sp)/100; break;
							case 12: fvfee=(9*sp)/100; break;
							case 13: fvfee=(15.2*sp)/100; break;
							case 14: fvfee=(4*sp)/100; break;
							case 15: fvfee=(2*sp)/100; break;
							case 16: fvfee=(15*sp)/100; break;
							case 17: fvfee=(2*sp)/100; break;
							case 18: fvfee=(6*sp)/100; break;
							case 19: fvfee=(5*sp)/100; break;
							case 20: fvfee=(2*sp)/100; break;
							case 21: fvfee=(10*sp)/100; break;
							case 22: fvfee=(2.5*sp)/100; break;
							case 23: fvfee=(9*sp)/100; break;
							case 24: fvfee=(5*sp)/100; break;
							case 25: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 26: fvfee=(12*sp)/100; break;
							case 27: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 28: fvfee=(8*sp)/100; break;
							case 29: fvfee=(2*sp)/100; break;
							case 30: fvfee=(15*sp)/100; break;
							case 31: fvfee=(15*sp)/100; break;
							case 32: fvfee=(12*sp)/100; break;
							case 33: fvfee=(7*sp)/100; break;
							case 34: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 35: fvfee=(14*sp)/100; break;
							case 36: fvfee=(9*sp)/100; break;
							case 37: fvfee=(8*sp)/100; break;
							default: cerr<<"Wrong Choice!!"; exit(0);}
									break;


			case 5:     switch(category)//eBay
							{
							case 1: fvfee=(5*sp)/100; break;
							case 2: fvfee=(6*sp)/100; break;
							case 3: fvfee=(4*sp)/100; break;
							case 4: fvfee=(7*sp)/100; break;
							case 5: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 6: fvfee=(7*sp)/100; break;
							case 7: fvfee=(7*sp)/100; break;
							case 8: fvfee=(7*sp)/100; break;
							case 9: fvfee=(7*sp)/100; break;
							case 10: fvfee=(5*sp)/100; break;
							case 11: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 12: fvfee=(5*sp)/100; break;
							case 13: fvfee=(7*sp)/100; break;
							case 14: fvfee=(5*sp)/100; break;
							case 15: fvfee=(7*sp)/100; break;
							case 16: fvfee=(5*sp)/100; break;
							case 17: fvfee=(2*sp)/100; break;
							case 18: fvfee=(1*sp)/100; break;
							case 19: fvfee=(1*sp)/100; break;
							case 20: fvfee=(5*sp)/100; break;
							case 21: fvfee=(1*sp)/100; break;
							case 22: fvfee=(1*sp)/100; break;
							case 23: fvfee=(6*sp)/100; break;
							case 24: fvfee=(7*sp)/100; break;
							case 25: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 26: fvfee=(7*sp)/100; break;
							case 27: fvfee=(5*sp)/100; break;
							case 28: fvfee=(6*sp)/100; break;
							case 29: fvfee=(1*sp)/100; break;
							case 30: fvfee=(6*sp)/100; break;
							case 31: fvfee=(7*sp)/100; break;
							case 32: fvfee=(6*sp)/100; break;
							case 33: fvfee=(7*sp)/100; break;
							case 34: fvfee=(5*sp)/100; break;
							case 35: fvfee=(2*sp)/100; break;
							case 36: fvfee=(2.5*sp)/100; break;
							case 37: fvfee=(7*sp)/100; break;
							default : cerr<<"Wrong Choice!!"; exit(0);
							}
							break;

			case 6:     switch(category)//ShopClues
							{
							case 1: fvfee=(12*sp)/100; break;
							case 2: fvfee=(15*sp)/100; break;
							case 3: fvfee=(7*sp)/100; break;
							case 4: fvfee=(12*sp)/100; break;
							case 5: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 6: fvfee=(15*sp)/100; break;
							case 7: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 8: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 9: fvfee=(12*sp)/100; break;
							case 10: fvfee=(17*sp)/100; break;
							case 11: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 12: fvfee=(12*sp)/100; break;
							case 13: fvfee=(14*sp)/100; break;
							case 14: fvfee=(6*sp)/100; break;
							case 15: fvfee=(17*sp)/100; break;
							case 16: fvfee=(15*sp)/100; break;
							case 17: fvfee=(4*sp)/100; break;
							case 18: fvfee=(6*sp)/100; break;
							case 19: fvfee=(4*sp)/100; break;
							case 20: fvfee=(12*sp)/100; break;
							case 21: fvfee=(6*sp)/100; break;
							case 22: fvfee=(6*sp)/100; break;
							case 23: fvfee=(15*sp)/100; break;
							case 24: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 25: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 26: fvfee=(15*sp)/100; break;
							case 27: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 28: fvfee=(15*sp)/100; break;
							case 29: fvfee=(6*sp)/100; break;
							case 30: cout<<"This Category Cannot be sold on this Website"; exit(0);
							case 31: fvfee=(12*sp)/100; break;
							case 32: fvfee=(8*sp)/100; break;
							case 33: fvfee=(15*sp)/100; break;
							case 34: fvfee=(20*sp)/100; break;
							case 35: fvfee=(8*sp)/100; break;
							case 36: fvfee=(10*sp)/100; break;
							case 37: fvfee=(10*sp)/100; break;
							default : cerr<<"Wrong Choice!!"; exit(0);}
							 break;

		    default : cerr<<"Wrong Choice!!"; exit(0); }
	}

	float logistics(int city, float w, int cod, int log)
	{
		switch (log)
		{
			case 1:
				if (city == 1)
				{
					if (w <= 500){ logfee = 30; }
					else if (w >= 501 && w <= 1000){ logfee = 30 + (1 * (35)); }
					else if (w >= 1001 && w <= 1500){ logfee = 30 + (2 * (35)); }
					else if (w >= 1501 && w <= 2000){ logfee = 30 + (3 * (35)); }
					else if (w >= 2001 && w <= 2500){ logfee = 30 + (4 * (35)); }
					else if (w >= 2501 && w <= 3000){ logfee = 30 + (5 * (35)); }
					else if (w >= 3001 && w <= 3500){ logfee = 30 + (6 * (35)); }
					else if (w >= 3501 && w <= 4000){ logfee = 30 + (7 * (35)); }
					else if (w >= 4001 && w <= 4500){ logfee = 30 + (8 * (35)); }
					else if (w >= 4501 && w <= 5000){ logfee = 30 + (9 * (35)); }
					else{
						cout << "Contact Customer Care!!";
						cout << "Press 1 to Continue or Press 2 to Exit";
						cin >> choice1;
						if (choice1 == 1){ logfee = 0; break; }
						else{ exit(0); }
					}
				}
				else if (city == 2)
				{
					if (w <= 500){ logfee = 50; }
					else if (w >= 501 && w <= 1000){ logfee = 50 + (1 * (55)); }
					else if (w >= 1001 && w <= 1500){ logfee = 50 + (2 * (55)); }
					else if (w >= 1501 && w <= 2000){ logfee = 50 + (3 * (55)); }
					else if (w >= 2001 && w <= 2500){ logfee = 50 + (4 * (55)); }
					else if (w >= 2501 && w <= 3000){ logfee = 50 + (5 * (55)); }
					else if (w >= 3001 && w <= 3500){ logfee = 50 + (6 * (55)); }
					else if (w >= 3501 && w <= 4000){ logfee = 50 + (7 * (55)); }
					else if (w >= 4001 && w <= 4500){ logfee = 50 + (8 * (55)); }
					else if (w >= 4501 && w <= 5000){ logfee = 50 + (9 * (55)); }
					else{
						cout << "Contact Customer Care!!";
						cout << "Press 1 to Continue or Press 2 to Exit";
						cin >> choice1;
						if (choice1 == 1){ logfee = 0; }
						else{exit(0); }
					}
				}
				else { cerr << "Wrong City placement Choice!!"; exit(0); }
				codfee = 0;
			break;
			case 2:
				if (city == 1)
				{
					if (w <= 500){ logfee = 36; }
					else if (w >= 501 && w <= 1000){ logfee = 36 + (1 * (40)); }
					else if (w >= 1001 && w <= 1500){ logfee = 36 + (2 * (40)); }
					else if (w >= 1501 && w <= 2000){ logfee = 36 + (3 * (40)); }
					else if (w >= 2001 && w <= 2500){ logfee = 36 + (4 * (40)); }
					else if (w >= 2501 && w <= 3000){ logfee = 36 + (5 * (40)); }
					else if (w >= 3001 && w <= 3500){ logfee = 36 + (6 * (40)); }
					else if (w >= 3501 && w <= 4000){ logfee = 36 + (7 * (40)); }
					else if (w >= 4001 && w <= 4500){ logfee = 36 + (8 * (40)); }
					else if (w >= 4501 && w <= 5000){ logfee = 36 + (9 * (40)); }
					else{
						cout << "Contact Customer Care!!";
						cout << "Press 1 to Continue or Press 2 to Exit";
						cin >> choice1;
						if (choice1 == 1){ logfee = 0; }
						else{exit(0); }
					}
				}
				else if (city == 2)
				{
					if (w <= 500){ logfee = 56; }
					else if (w >= 501 && w <= 1000){ logfee = 56 + (1 * (40)); }
					else if (w >= 1001 && w <= 1500){ logfee = 56 + (2 * (40)); }
					else if (w >= 1501 && w <= 2000){ logfee = 56 + (3 * (40)); }
					else if (w >= 2001 && w <= 2500){ logfee = 56 + (4 * (40)); }
					else if (w >= 2501 && w <= 3000){ logfee = 56 + (5 * (40)); }
					else if (w >= 3001 && w <= 3500){ logfee = 56 + (6 * (40)); }
					else if (w >= 3501 && w <= 4000){ logfee = 56 + (7 * (40)); }
					else if (w >= 4001 && w <= 4500){ logfee = 56 + (8 * (40)); }
					else if (w >= 4501 && w <= 5000){ logfee = 56 + (9 * (40)); }
					else{
						cout << "Contact Customer Care!!";
						cout << "Press 1 to Continue or Press 2 to Exit";
						cin >> choice1;
						if (choice1 == 1){ logfee = 0; }
						else{exit(0); }
					}
				}
				else { cerr << "Wrong City placement Choice!!"; exit(0); }
				switch (cod){
					case 1: cout << "COD Not Available!!";
						cout << "Press 1 to Continue as NON COD or Press 2 to Exit";
						cin >> choice2;
						if (choice2 == 1){ break; }
						else { exit(0); } break;
					case 2: codfee = 0; break;
					default: cerr << "Wrong COD Choice!!"; exit(0); break;
				}
			break;
			case 3:
				if (city == 1)
				{
					if (w <= 500){ logfee = 45; }
					else if (w >= 501 && w <= 1000){ logfee = 45 + (1 * (47)); }
					else if (w >= 1001 && w <= 1500){ logfee = 45 + (2 * (47)); }
					else if (w >= 1501 && w <= 2000){ logfee = 45 + (3 * (47)); }
					else if (w >= 2001 && w <= 2500){ logfee = 45 + (4 * (47)); }
					else if (w >= 2501 && w <= 3000){ logfee = 45 + (5 * (47)); }
					else if (w >= 3001 && w <= 3500){ logfee = 45 + (6 * (47)); }
					else if (w >= 3501 && w <= 4000){ logfee = 45 + (7 * (47)); }
					else if (w >= 4001 && w <= 4500){ logfee = 45 + (8 * (47)); }
					else if (w >= 4501 && w <= 5000){ logfee = 45 + (9 * (47)); }
					else{
						cout << "Contact Customer Care!!";
						cout << "Press 1 to Continue or Press 2 to Exit";
						cin >> choice1;
						if (choice1 == 1){ logfee = 0; }
						else{ exit(0); }
					}
				}
				else if (city == 2)
				{
					if (w <= 500){ logfee = 65; }
					else if (w >= 501 && w <= 1000){ logfee = 65 + (1 * (56)); }
					else if (w >= 1001 && w <= 1500){ logfee = 65 + (2 * (56)); }
					else if (w >= 1501 && w <= 2000){ logfee = 65 + (3 * (56)); }
					else if (w >= 2001 && w <= 2500){ logfee = 65 + (4 * (56)); }
					else if (w >= 2501 && w <= 3000){ logfee = 65 + (5 * (56)); }
					else if (w >= 3001 && w <= 3500){ logfee = 65 + (6 * (56)); }
					else if (w >= 3501 && w <= 4000){ logfee = 65 + (7 * (56)); }
					else if (w >= 4001 && w <= 4500){ logfee = 65 + (8 * (56)); }
					else if (w >= 4501 && w <= 5000){ logfee = 65 + (9 * (56)); }
					else{
						cout << "Contact Customer Care!!";
						cout << "Press 1 to Continue or Press 2 to Exit";
						cin >> choice1;
						if (choice1 == 1){ logfee = 0; }
						else{exit(0); }
					}
				}
				else{ cerr << "Wrong City Choice!!"; exit(0); }
				if (cod == 1){ codfee = 30; }
				else { codfee = 0; }
			break;
			case 4: cout<<"adele";
			if(city==1)
				{
				    if (w<=500){logfee=25;}
					else if(w>=501 && w<=1000){logfee=25+(1*(28));}
					else if(w>=1001 && w<=1500){logfee=25+(2*(28));}
					else if(w>=1501 && w<=2000){logfee=25+(3*(28));}
					else if(w>=2001 && w<=2500){logfee=25+(4*(28));}
					else if(w>=2501 && w<=3000){logfee=25+(5*(28));}
					else if(w>=3001 && w<=3500){logfee=25+(6*(28));}
					else if(w>=3501 && w<=4000){logfee=25+(7*(28));}
					else if(w>=4001 && w<=4500){logfee=25+(8*(28));}
					else if(w>=4501 && w<=5000){logfee=25+(9*(28));}
					else cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}

					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else if(city==2)
						{
                        if (w<=500){logfee=45;}
					else if(w>=501 && w<=1000){logfee=45+(1*(48));}
					else if(w>=1001 && w<=1500){logfee=45+(2*(48));}
					else if(w>=1501 && w<=2000){logfee=45+(3*(48));}
					else if(w>=2001 && w<=2500){logfee=45+(4*(48));}
					else if(w>=2501 && w<=3000){logfee=45+(5*(48));}
					else if(w>=3001 && w<=3500){logfee=45+(6*(48));}
					else if(w>=3501 && w<=4000){logfee=45+(7*(48));}
					else if(w>=4001 && w<=4500){logfee=45+(8*(48));}
					else if(w>=4501 && w<=5000){logfee=45+(9*(48));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
						            cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cout<<"Wrong Choice"; exit(0);}else {cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
									else cerr<<"Wrong Choice!!"; exit(0);
									if(cod==1){codfee=30;} else {codfee=0;}
					break;

		case 5: if(city==1)
				{if (w<=500){logfee=55;}
					else if(w>=501 && w<=1000){logfee=55+(1*(40));}
					else if(w>=1001 && w<=1500){logfee=55+(2*(40));}
					else if(w>=1501 && w<=2000){logfee=55+(3*(40));}
					else if(w>=2001 && w<=2500){logfee=55+(4*(40));}
					else if(w>=2501 && w<=3000){logfee=55+(5*(40));}
					else if(w>=3001 && w<=3500){logfee=55+(6*(40));}
					else if(w>=3501 && w<=4000){logfee=55+(7*(40));}
					else if(w>=4001 && w<=4500){logfee=55+(8*(40));}
					else if(w>=4501 && w<=5000){logfee=55+(9*(40));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else if(city==2)
						{if (w<=500){logfee=75;}
					else if(w>=501 && w<=1000){logfee=75+(1*(60));}
					else if(w>=1001 && w<=1500){logfee=75+(2*(60));}
					else if(w>=1501 && w<=2000){logfee=75+(3*(60));}
					else if(w>=2001 && w<=2500){logfee=75+(4*(60));}
					else if(w>=2501 && w<=3000){logfee=75+(5*(60));}
					else if(w>=3001 && w<=3500){logfee=75+(6*(60));}
					else if(w>=3501 && w<=4000){logfee=75+(7*(60));}
					else if(w>=4001 && w<=4500){logfee=75+(8*(60));}
					else if(w>=4501 && w<=5000){logfee=75+(9*(60));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
								else {cerr<<"Wrong Choice!!"; exit(0);}
					switch(cod){
					case 1: cout<<"Not Available!!";
									cout<<"Press 1 to Continue as NON COD or Press 2 to Try Again Later";
							    cin>>choice2;
									if(choice2==1){codfee=0;}
									else if(!choice2==1){cerr<<"Wrong Choice!!"; exit(0);} break;
					case 2: codfee=0; break;
					default: cerr<<"Wrong Choice!!"; exit(0);}
					break;

		case 6: if(city==1)
				{if (w<=500){logfee=30;}
					else if(w>=501 && w<=1000){logfee=30+(1*(35));}
					else if(w>=1001 && w<=1500){logfee=30+(2*(35));}
					else if(w>=1501 && w<=2000){logfee=30+(3*(35));}
					else if(w>=2001 && w<=2500){logfee=30+(4*(35));}
					else if(w>=2501 && w<=3000){logfee=30+(5*(35));}
					else if(w>=3001 && w<=3500){logfee=30+(6*(35));}
					else if(w>=3501 && w<=4000){logfee=30+(7*(35));}
					else if(w>=4001 && w<=4500){logfee=30+(8*(35));}
					else if(w>=4501 && w<=5000){logfee=30+(9*(35));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else if(city==2)
						{if (w<=500){logfee=50;}
					else if(w>=501 && w<=1000){logfee=50+(1*(55));}
					else if(w>=1001 && w<=1500){logfee=50+(2*(55));}
					else if(w>=1501 && w<=2000){logfee=50+(3*(55));}
					else if(w>=2001 && w<=2500){logfee=50+(4*(55));}
					else if(w>=2501 && w<=3000){logfee=50+(5*(55));}
					else if(w>=3001 && w<=3500){logfee=50+(6*(55));}
					else if(w>=3501 && w<=4000){logfee=50+(7*(55));}
					else if(w>=4001 && w<=4500){logfee=50+(8*(55));}
					else if(w>=4501 && w<=5000){logfee=50+(9*(55));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
								else {cerr<<"Wrong Choice!!"; exit(0);}
									if(cod==1){codfee=0;} else {codfee=0;}
					break;

		case 7: if(city==1)
				{if (w<=500){logfee=40;}
					else if(w>=501 && w<=1000){logfee=40+(1*(30));}
					else if(w>=1001 && w<=1500){logfee=40+(2*(30));}
					else if(w>=1501 && w<=2000){logfee=40+(3*(30));}
					else if(w>=2001 && w<=2500){logfee=40+(4*(30));}
					else if(w>=2501 && w<=3000){logfee=40+(5*(30));}
					else if(w>=3001 && w<=3500){logfee=40+(6*(30));}
					else if(w>=3501 && w<=4000){logfee=40+(7*(30));}
					else if(w>=4001 && w<=4500){logfee=40+(8*(30));}
					else if(w>=4501 && w<=5000){logfee=40+(9*(30));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
						            cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else if(city==2)
						{if (w<=500){logfee=60;}
					else if(w>=501 && w<=1000){logfee=60+(1*(50));}
					else if(w>=1001 && w<=1500){logfee=60+(2*(50));}
					else if(w>=1501 && w<=2000){logfee=60+(3*(50));}
					else if(w>=2001 && w<=2500){logfee=60+(4*(50));}
					else if(w>=2501 && w<=3000){logfee=60+(5*(50));}
					else if(w>=3001 && w<=3500){logfee=60+(6*(50));}
					else if(w>=3501 && w<=4000){logfee=60+(7*(50));}
					else if(w>=4001 && w<=4500){logfee=60+(8*(50));}
					else if(w>=4501 && w<=5000){logfee=60+(9*(50));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
								else cerr<<"Wrong Choice!!"; exit(0);
									if(cod==1){codfee=0;} else {codfee=0;}
					break;

		case 8: if(city==1)
				{if (w<=500){logfee=45;}
					else if(w>=501 && w<=1000){logfee=45+(9*(40));}
					else if(w>=1001 && w<=1500){logfee=45+(2*(40));}
					else if(w>=1501 && w<=2000){logfee=45+(3*(40));}
					else if(w>=2001 && w<=2500){logfee=45+(4*(40));}
					else if(w>=2501 && w<=3000){logfee=45+(5*(40));}
					else if(w>=3001 && w<=3500){logfee=45+(6*(40));}
					else if(w>=3501 && w<=4000){logfee=45+(7*(40));}
					else if(w>=4001 && w<=4500){logfee=45+(8*(40));}
					else if(w>=4501 && w<=5000){logfee=45+(9*(40));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0; break;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else if(city==2)
						{if (w<=500){logfee=65;}
					else if(w>=501 && w<=1000){logfee=65+(1*(60));}
					else if(w>=1001 && w<=1500){logfee=65+(2*(60));}
					else if(w>=1501 && w<=2000){logfee=65+(3*(60));}
					else if(w>=2001 && w<=2500){logfee=65+(4*(60));}
					else if(w>=2501 && w<=3000){logfee=65+(5*(60));}
					else if(w>=3001 && w<=3500){logfee=65+(6*(60));}
					else if(w>=3501 && w<=4000){logfee=65+(7*(60));}
					else if(w>=4001 && w<=4500){logfee=65+(8*(60));}
					else if(w>=4501 && w<=5000){logfee=65+(9*(60));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else cerr<<"Wrong Choice!!"; exit(0);
								if(cod==1){codfee=20;} else {codfee=0;}
					break;

		case 9: if(city==1)
				{if (w<=500){logfee=47;}
					else if(w>=501 && w<=1000){logfee=47+(1*(50));}
					else if(w>=1001 && w<=1500){logfee=47+(2*(50));}
					else if(w>=1501 && w<=2000){logfee=47+(3*(50));}
					else if(w>=2001 && w<=2500){logfee=47+(4*(50));}
					else if(w>=2501 && w<=3000){logfee=47+(5*(50));}
					else if(w>=3001 && w<=3500){logfee=47+(6*(50));}
					else if(w>=3501 && w<=4000){logfee=47+(7*(50));}
					else if(w>=4001 && w<=4500){logfee=47+(8*(50));}
					else if(w>=4501 && w<=5000){logfee=47+(9*(50));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}
					else {cerr<<"Wrong Choice!!"; exit(0);}
					}
				else if(city==2)
						{if (w<=500){logfee=65; break;}
					else if(w>=501 && w<=1000){logfee=65+(1*(70));}
					else if(w>=1001 && w<=1500){logfee=65+(2*(70));}
					else if(w>=1501 && w<=2000){logfee=65+(3*(70));}
					else if(w>=2001 && w<=2500){logfee=65+(4*(70));}
					else if(w>=2501 && w<=3000){logfee=65+(5*(70));}
					else if(w>=3001 && w<=3500){logfee=65+(6*(70));}
					else if(w>=3501 && w<=4000){logfee=65+(7*(70));}
					else if(w>=4001 && w<=4500){logfee=65+(8*(70));}
					else if(w>=4501 && w<=5000){logfee=65+(9*(70));}
					else if(w<=5001){cout<<"Contact Customer Care!!";
									cout<<"Press 1 to Continue or Press 2 to Try Again Later";
							    cin>>choice1;
									if(choice1==1){logfee=0;}
									else if(!choice1==1){cerr<<"Wrong Choice!!"; exit(0);}
									}

							else {cerr<<"Wrong Choice!!"; exit(0);}
						}
						else {cerr<<"Wrong Choice!!"; exit(0);}
									if(cod==1){codfee=30;} else {codfee=0;}
									break;
			default:cerr << "Wrong Log Choice!!"; exit(0); break;
		}
		return logfee;
	}

	float restfee(int wb, int sp)
	{

		switch (websiteNum)
		{
		case 1: trfee = (1 * sp) / 100;
			mkpfee = (1.5*sp) / 100;
			break;

		case 2: trfee = (3.2*sp) / 100;
			mkpfee = (1.5*sp) / 100;
			break;

		case 3: trfee = (1 * sp) / 100;
			mkpfee = (0.8*sp) / 100;
			break;

	    case 4: trfee=(3*sp)/100;
		mkpfee=(1.4*sp)/100;
			break;

	    case 5: trfee=(4.5*sp)/100;
			  mkpfee=5;
			break;
	    case 6: trfee=0;
			  mkpfee=(1.5*sp)/100;
			break;
		default: cerr << "Wrong Website Choice!!";
			exit(0);
		}
		a = trfee;
		b = mkpfee;
		return a, b;
	}

	float pkf(int w)
	{

		if (w <= 1000){ pkfee = 20; }
		else if (w>1000){ pkfee = 40; }
		else { exit(0); }
		x = pkfee;
		return x;
	}

	void calculator(float sp)
	{

		exp = x + b + fvfee + a + logfee + codfee;
		tax = (14.5*sp) / 100;
		cout << "Tax - " << tax;
		texp = exp + tax;
		total = sp - texp;
		t = total;
		inhand = (t / sp) * 100;
		dedc = 100 - inhand;
	}

	void categdisplay(int category)
	{

		switch (category)
		{
		case 1: categname= "Baby & Mom";
			break;
		case 2: categname = "Books & Magazines";
			break;
		case 3: categname= "Cameras & Optics";
			break;
		case 4: categname="Automotive";
			break;
		case 5:categname= "Charity";
			break;
        case 6:categname="Clothing & Accessories";
			break;
        case 7:categname="Coins & Notes";
                break;
        case 8:categname="Collectibles";
                break;
        case 9:categname="Fitness & Sports";
                break;
        case 10:categname="Fragrances, Beauty & Health";
                break;
        case 11:categname="Fun Stuff";
                break;
        case 12:categname="Games & Accessories";
                break;
        case 13:categname="Home and Living";
                break;
        case 14:categname="Home & Kitchen Appliances";
                break;
        case 15:categname="Jewellery & Precious Coins";
                break;
        case 16:categname="Kitchen & Dining";
                break;
        case 17:categname="Laptops & Computer Peripherals";
                break;
        case 18:categname="LCD, LED & Televisions";
                break;
        case 19:categname="Memory Cards, Pen Drives & HDD";
                break;
        case 20:categname="Mobile Accessories";
                break;
        case 21:categname="Mobile Phones";
                break;
        case 22:categname="Gaming Consoles";
                break;
        case 23:categname="Movies & Music";
                break;
        case 24:categname="Musical Instruments";
                break;
        case 25:categname="Services & Real Estate";
                break;
        case 26:categname="Shoes";
                break;
        case 27:categname="Stamps";
                break;
        case 28:categname="Stationery & Office Supplies";
                break;
        case 29:categname="Tablets & Accessories";
                break;
        case 30:categname="Hardware & Electricals";
                break;
        case 31:categname="Toys, Games & School Supplies";
                break;
        case 32:categname="Travel";
                break;
        case 33:categname="Watches";
                break;
        case 34:categname="Warranty Services";
                break;
        case 35:categname="Wearable Devices";
                break;
        case 36:categname="Audio & Home Entertainment";
                break;
        case 37:categname="Everything Else";
                break;
		default:cerr << "Wrong Category Choice!!"; exit(0);
		}
}
}ex;

class Datafile{

public:
	int x, y, z, i=0;
	void input(){
		int id,chz;
		cout << "Enter a Unique ID of Your Choice: ";
		cin >> id;
		if (c[i] == id){ cout << "Duplicate Input"; exit(0); }
		else {
			cout << "Categories \n 1. Baby & Mom \n 2. Books & Magazines \n 3. Cameras & Optics \n 4. Automotive \n 5. charity \n";
                cout<<"Do you want to see all the categories ? Yes=>1  ||  No=> 2 - "; cin>>chz;
                if(chz==1)
                {
                    cout<<endl<<"6. Clothing & Accessories"<<endl<<"7. Coins & Notes"<<endl<<"8. Collectibles"<<endl<<"9. Fitness & Sports"<<endl<<"10. Fragrances, Beauty & Health"<<endl;
                        cout<<"11. Fun Stuff"<<endl<<"12. Games & Accessories"<<endl<<"13. Home and Living"<<endl<<"14. Home & Kitchen Appliances"<<endl<<"15. Jewellery & Precious Coins"<<endl<<"16. Kitchen & Dining"<<endl<<"17. Laptops & Computer Peripherals"<<endl<<"18. LCD, LED & Televisions"<<endl<<"19. Memory Cards, Pen Drives & HDD"<<endl;
                        cout<<"20. Mobile Accessories"<<endl<<"21. Mobile Phones"<<endl<<"22. Gaming Consoles"<<endl<<"23. Movies & Music"<<endl<<"24. Musical Instruments"<<endl<<"25. Services & Real Estate"<<endl<<"26. Shoes"<<endl<<"27. Stamps"<<endl<<"28. Stationery & Office Supplies"<<endl<<"29. Tablets & Accessories"<<endl;
                        cout<<"30. Hardware & Electricals"<<endl<<"31. Toys, Games & School Supplies"<<endl<<"32. Travel"<<endl<<"33. Watches"<<endl<<"34. Warranty Services"<<endl<<"35. Wearable Devices"<<endl<<"36. Audio & Home Entertainment"<<endl<<"37. Everything Else"<<endl;

                }
            cout << "Enter the category number corresponding to its serial number: ";

			cin >> ex.category;

			cout << "Enter the Number corresponding to the Name of the Website the product is sold on -\n1. Flipkart\n2. SnapDeal\n3. Amazon"<<endl<<"4. PayTM"<<endl<<"5. eBay"<<endl<<"6. ShopClues"<<endl;;
			cin >> ex.websiteNum;



			cout << "What is the Selling Price Inclusive of all discounts and shipping charges : ";
			cin >> ex.sp;

			cout << "What is the Length, Breadth & Height of the Package (in Cms) : ";
			cin >> ex.l;
			cout << "X";
			cin >> ex.b;
			cout << "X";
			cin >> ex.h;
			ex.w = (ex.l*ex.b*ex.h) / 5;

			cout << endl << "Press 1 for COD orders or Press 2 for Non COD orders :";
			cin >> ex.cod;
			cout << endl << "Press 1 for Shipments within the City or Press 2 for Shipments Outside the City : ";
			cin >> ex.city;
			cout << "Which Logistics is Used for the Shipment - \n1. BlueDart\n2. FedEx\n3. Delhivery\n"<<endl<<"4. DTDC/FirstFlight"<<endl<< "5. Ecom Express";
            cout<<endl<<"6. India Post"<<endl<< "7. ATS"<<endl<< "8. Ekart"<<endl<<"9. Aramex"<<endl;
			cin >> ex.log;

			int t;
			ex.categdisplay(ex.category);
			ex.logistics(ex.city, ex.w, ex.cod, ex.log);
			ex.finalvfee();
			ex.restfee(ex.websiteNum, ex.sp);
			ex.pkf(ex.w);
			ex.calculator(ex.sp);

			ofstream fin,idin;
			fin.open("Seller.txt",ios::app);
			idin.open("UniqueId.txt", ios::app);
			if (fin.is_open()){
				fin.seekp(0,fin.end);
				fin << endl<< "\t\teCommerce Seller Fees Calculator" << endl << endl;
				fin << "Unique Custom ID= " << id << endl;
				fin << "Category= "; fin << ex.categname;
				fin << endl << "Website= " << wbname[ex.websiteNum];
				fin << endl << "Courier Company(Logistics)= " << logname[ex.log];
				fin << endl << "Weight= " << ex.w;
				fin << endl << "MarketPlace Fee= " << ex.a;
				fin << endl << "Transaction Fee= " << ex.b;
				fin << endl << "Final value Fee(Based on Category) Fee= " << ex.fvfee;
				fin << endl << "Logistics Fee= " << ex.logfee;
				fin << endl << " Packaging Fee= " << ex.x << endl;
				fin << endl << "The Total In Hand Amount after 14.5 % Tax is= " << ex.t << endl;
				fin << endl << " Total Deduction Percentage is= " << setprecision(4) << ex.dedc << " %" << endl;
				fin << endl << " Total In-Hand Percentage is= " << setprecision(4) << ex.inhand << " %" << endl;
				fin.close();
				idin << id<<"\n";
			}
			else cout << "Unable to open File in input function\n";
		}
		getch();
		cout << "\n\n"; mainmenu();
	}

	void output(){
		cout << endl << endl;
		int found = 0;
		string displaystring="",iddel="";
		cout << "Enter the Id whose data you want to show : "; cin >> iddel;
		ifstream fin("Seller.txt");
		if (fin.is_open()){
			cout << "\n----Search Result----\n\n";
			while (getline(fin, displaystring)){
				if (displaystring == ("Unique Custom ID= " + iddel)){
					for (int a = 0; a < 16; a++){
						cout << displaystring<<"\n";
						getline(fin, displaystring);
					}
					found = 1;
				}
			}
			if (found == 0) cout << "Id not found!\n";
			}
		else cout << "Unable To open the file\n";
		fin.close();
		getch();
		mainmenu();
	}

	void del(){
		ifstream rsrc("Seller.txt");
		ofstream tsrc("TempForDeletion.txt");
		string del = "";
		int start, end;
		string idc;
		cout << "Enter the Id you want to delete : "; cin >> idc;
		while (getline(rsrc,del)){
			if (del == ("Unique Custom ID= " + idc)){
				for (int a = 0; a < 17; a++){
					getline(rsrc, del);
				}
			}
			else{
				tsrc << del<<"\n";
			}
		}
		rsrc.close();
		tsrc.close();
		remove("Seller.txt");
		rename("TempForDeletion.txt", "Seller.txt");
		ifstream idsrc("UniqueId.txt");
		ofstream tempid("TempForId.txt");
		while (getline(idsrc, del)){
			if (del != idc) tempid << del<<"\n";
		}
		idsrc.close(); tempid.close();
		remove("UniqueId.txt");
		rename("TempForId.txt","UniqueId.txt");
		cout << "Data deleted ! \n";
		getch();
		mainmenu();
	}

	int mainmenu()
	{
		int g;
		string ids;
		string forId = "";
		cout << endl << "\t\t eCommerce Seller Fees Calculator" << endl<< endl;
		cout << "1=> Input\n2=>Show\n3=>Delete\n4=>Show all Unique Custom IDs\n5=>Exit\nEnter your choice: ";
		cin >> g;
		if (g == 1){ input(); }
		else if (g == 2){ output(); }
		else if (g == 3){ del(); }
		else if (g == 4){
			ifstream allId;
			allId.open("UniqueId.txt");
			cout << "\nThese are all of the Id's: \n";
			while (getline(allId,ids))
			{
				cout <<ids<<"\n";
			}
			allId.close();
			mainmenu();
		}
		else exit(0);
		return 0;
	}
 } eg;

int main()
{
	eg.mainmenu();
	return 0;
}
