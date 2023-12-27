case 2:
		cout<<"enter daily spending limit : ";
		cin>>dailySpendingLimit;
		cout<<"enter weekly spending limit : ";
		cin>>weeklySpendingLimit;
		break;

  oid deposit() 
{
	double amount;
	cout<<"enter amout to be deposited : ";
	cin>>amount;
    if (amount > 0) {
            initialBalance1 = initialBalance1 + amount;
        cout << "Deposit successful. Current balance: " << initialBalance1 << endl;
    } else {
        cout << "Invalid deposit amount. Please enter a positive value." << endl;
    }
}


void displayAccount(const string& accountHolder, int accountNumber, double balance)
{
    cout << " Account Holder: " << accountHolder << endl;
    cout << " Account Number: " << accountNumber << endl;
    cout << " Balance: Rs" << balance << endl;
    cout<<endl;
}
cout << "Enter account holder name: ";
    cin>>holdername1;

    cout << "Enter allotted account number: ";
    cin >> accountNumber1;

    cout << "Set a 4-digit pin for your account: ";
    for(int s=0;s<4;s++)
	{
		cin>>password[s];
	}

    cout << "Enter initial balance: ";
    cin >> initialBalance1;

    cout << "\nAccount created successfully. "<<endl<<"Details : "<<endl;
    displayAccount(holdername1, accountNumber1, initialBalance1);
	}
	
	{
	string holdername2;
    int accountNumber2;
	int password2[4];
	cout << "Enter account holder name: ";
    cin>>holdername2;
    
    cout << "Enter allotted account number: ";
    cin >> accountNumber2;
    
    cout << "Enter 4 digit account pin : ";
	for(int t=0;t<4;t++)
	{
		cin>>password2[t];
	}
	int u=0;
	bool f=true;
	for(u=0;u<4;u++)
	{
    if(password2[u] != password[u])
    {
		f=false;
	}
	}
	if (f==true)
	{
		cout<<"correct pin"<<endl<<endl;
	}
	else
	{
		cout<<"Incorrect pin"<<endl<<endl;
	}
	

	}
	else if(opt1 == 3)
	{
		break;
	}
