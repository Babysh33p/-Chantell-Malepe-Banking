@ -0,0 +1,366 @@
#include <iostream>

using namespace std;

int main()
{
    int choice;
    int deposit;
    int withdrawal;
    int accountbalance;
    int accountnumber;
    int startingamount;
    int login;
    int phonenumber;
    int password;
    int sum=deposit-withdrawal;
    int cardreplacement;
    string streetname;
    double identityNumber;
    string userpin;
    string username;
    string surname;

    cout<<"WELCOME TO OKLAM BREW BANK... "<<endl;
    cout<<"PLEASE ENSURE THAT YOU LOGIN FIRST TO INSERT YOUR ACOUNT BALANCE..."<<endl;
    cout<<"PLEASE PICK A CHOICE FORM BELLOW "<<endl;
    cout<<"WHILE ANSWARING TRY TO AVOID SPACING ATMOST "<<endl;

    cout<<"Enter 1 to deposit "<<endl;
    cout<<"Enter 2 to withdraw "<<endl;
    cout<<"Enter 3 to account balance"<<endl;
    cout<<"Enter 4 for card replacement "<<endl;
    cout<<"Enter 5 to login "<<endl;
    cin>>choice;

     switch(choice)
    {

    case 1:
        cout<<"How much would you like to deposit "<<endl;
        cin>>deposit;
        cout<<"you have deposited "<<deposit<<" right into your account"<<endl;
        break;

    case 2:
        cout<<"How much would you like to withdraw "<<endl;
        cin>>withdrawal;
        cout<<"You have withdrawn "<<withdrawal<<" Out of your account "<<endl;
        break;

    case 3:
        cout<<"Your account balance is "<<sum<<endl;
        if (sum <0)
        {
            cout<<"Insufficient amount "<<endl;
        }
        else if( sum >0)
        {
            cout<<"sufficient amount "<<endl;
        }
        cout<<"This is your account balance "<<sum<<" from your account "<<endl;
        break;

    case 4:
        cout<<"THE FINE TO REPLACE YOUR CARD WILL BE R250.00 ,IT CAN EITHER BE CASH OR CREDIT "<<endl;
        cout<<"Please do follow the few simple steps as instructed "<<endl;
        cout<<"One must leave no question/case unanswared "<<endl;
        cout<<"Enter previous nine digit acconunt number "<<endl;
        cin>>accountnumber;
        cout<<"Enter your address/street name "<<endl;
        cin>>streetname;
        cout<<"Enter your ten digit phone number "<<endl;
        cin>>phonenumber;
        cout<<"Enter you thirteen digit Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Your account number is "<<accountnumber<<" your street address/street name is "<<streetname<<" and your phone number is "<<phonenumber<<" your identity number is "<<identityNumber<<endl;
        break;

    case 5:
         cout<<"TO LOGIN FOLLOW THE FEW STEPS "<<endl;
        cout<<"Enter your name "<<endl;
        cin>>username;
        cout<<"Enter your surname "<<endl;
        cin>>surname;
        cout<<"Enter your Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Enter your starting amount "<<endl;
        cin>>startingamount;
        cout<<"Your name is is "<<username<<" your surname is "<<surname<<" your identity number is "<<identityNumber<<" your account number is "<<accountnumber<<" your strating amount is "<<endl;

    }
     string useraccountnumber = "1234";
        switch (choice)
       while (true)
       {
           cout<<"Enter your user account number: ";
           cin>>accountnumber;

           if (useraccountnumber == "1234")
            {
                cout<<"Correct ACCNUMBER. Access granted Buddy!"<<endl;
            }
            else
            {
                cout<<"INCORRECT ACCNUMBER. Access denied Buddy try again later!"<<endl;
            }
       }


    cout<<"Enter 1 to deposit "<<endl;
    cout<<"Enter 2 to withdraw "<<endl;
    cout<<"Enter 3 to account balance"<<endl;
    cout<<"Enter 4 for card replacement "<<endl;
    cout<<"Enter 5 to login "<<endl;
    cin>>choice;

     switch(choice)
    {

    case 1:
        cout<<"How much would you like to deposit "<<endl;
        cin>>deposit;
        cout<<"you have deposited "<<deposit<<" right into your account"<<endl;
        break;

    case 2:
        cout<<"How much would you like to withdraw "<<endl;
        cin>>withdrawal;
        cout<<"You have withdrawn "<<withdrawal<<" Out of your account "<<endl;
        break;

    case 3:
        cout<<"Your account balance is "<<sum<<endl;
        if (sum <0)
        {
            cout<<"Insufficient amount "<<endl;
        }
        else if( sum >0)
        {
            cout<<"sufficient amount "<<endl;
        }
        cout<<"This is your account balance "<<sum<<" from your account "<<endl;
        break;

    case 4:
        cout<<"THE FINE TO REPLACE YOUR CARD WILL BE R250.00 ,IT CAN EITHER BE CASH OR CREDIT "<<endl;
        cout<<"Please do follow the few simple steps as instructed "<<endl;
        cout<<"One must leave no question/case unanswared "<<endl;
        cout<<"Enter previous nine digit acconunt number "<<endl;
        cin>>accountnumber;
        cout<<"Enter your address/street name "<<endl;
        cin>>streetname;
        cout<<"Enter your 10 digit phone number "<<endl;
        cin>>phonenumber;
        cout<<"Enter you 13 digit Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Your account number is "<<accountnumber<<" your street address/street name is "<<streetname<<" and your phone number is "<<phonenumber<<" your identity number is "<<identityNumber<<endl;
        break;

    case 5:
         cout<<"TO LOGIN FOLLOW THE FEW STEPS "<<endl;
        cout<<"Enter your name "<<endl;
        cin>>username;
        cout<<"Enter your surname "<<endl;
        cin>>surname;
        cout<<"Enter your Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Enter your account balance "<<endl;
        cout<<accountbalance;
        cout<<"Your name is is "<<username<<" your surname is "<<surname<<" your identity number is "<<identityNumber<<" your account number is "<<accountnumber<<endl;

    }


    cout<<"Enter 1 to deposit "<<endl;
    cout<<"Enter 2 to withdraw "<<endl;
    cout<<"Enter 3 to account balance"<<endl;
    cout<<"Enter 4 for card replacement "<<endl;
    cout<<"Enter 5 to login "<<endl;
    cin>>choice;

     switch(choice)
    {

    case 1:
        cout<<"How much would you like to deposit "<<endl;
        cin>>deposit;
        cout<<"you have deposited "<<deposit<<" right into your account"<<endl;
        break;

    case 2:
        cout<<"How much would you like to withdraw "<<endl;
        cin>>withdrawal;
        cout<<"You have withdrawn "<<withdrawal<<" Out of your account "<<endl;
        break;

    case 3:
        cout<<"Your account balance is "<<sum<<endl;
        if (sum <0)
        {
            cout<<"Insufficient amount "<<endl;
        }
        else if(sum >0)
        {
            cout<<"sufficient amount "<<endl;
        }
        cout<<"This is your account balance "<<sum<<" from your account "<<endl;
        break;

    case 4:
        cout<<"THE FINE TO REPLACE YOUR CARD WILL BE R250.00 ,IT CAN EITHER BE CASH OR CREDIT "<<endl;
        cout<<"Please do follow the few simple steps as instructed "<<endl;
        cout<<"One must leave no question/case unanswared "<<endl;
        cout<<"Enter previous nine digit acconunt number "<<endl;
        cin>>accountnumber;
        cout<<"Enter your address/street name "<<endl;
        cin>>streetname;
        cout<<"Enter your ten digit phone number "<<endl;
        cin>>phonenumber;
        cout<<"Enter you thirteen digit Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Your account number is "<<accountnumber<<" your street address/street name is "<<streetname<<" and your phone number is "<<phonenumber<<" your identity number is "<<identityNumber<<endl;

        break;

    case 5:
        cout<<"TO LOGIN FOLLOW THE FEW STEPS "<<endl;
        cout<<"Enter your name "<<endl;
        cin>>username;
        cout<<"Enter your surname "<<endl;
        cin>>surname;
        cout<<"Enter your Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Enter your account balance "<<endl;
        cout<<accountbalance;
        cout<<"Your name is is "<<username<<" your surname is "<<surname<<" your identity number is "<<identityNumber<<" your account number is "<<accountnumber<<endl;
    }

     cout<<"Enter 1 to deposit "<<endl;
    cout<<"Enter 2 to withdraw "<<endl;
    cout<<"Enter 3 to account balance"<<endl;
    cout<<"Enter 4 for card replacement "<<endl;
    cout<<"Enter 5 to login "<<endl;
    cin>>choice;

     switch(choice)
    {

    case 1:
        cout<<"How much would you like to deposit "<<endl;
        cin>>deposit;
        cout<<"you have deposited "<<deposit<<" right into your account"<<endl;
        break;

    case 2:
        cout<<"How much would you like to withdraw "<<endl;
        cin>>withdrawal;
        cout<<"You have withdrawn "<<withdrawal<<" Out of your account "<<endl;
        break;

    case 3:
        cout<<"Your account balance is "<<sum<<endl;
        if (sum <0)
        {
            cout<<"Insufficient amount "<<endl;
        }
        else if( sum >0)
        {
            cout<<"sufficient amount "<<endl;
        }
        cout<<"This is your account balance "<<sum<<" from your account "<<endl;
        break;

    case 4:
        cout<<"THE FINE TO REPLACE YOUR CARD WILL BE R250.00 ,IT CAN EITHER BE CASH OR CREDIT "<<endl;
        cout<<"Please do follow the few simple steps as instructed "<<endl;
        cout<<"One must leave no question/case unanswared "<<endl;
        cout<<"Enter previous nine digit acconunt number "<<endl;
        cin>>accountnumber;
        cout<<"Enter your address/street name "<<endl;
        cin>>streetname;
        cout<<"Enter your 10 digit phone number "<<endl;
        cin>>phonenumber;
        cout<<"Enter you 13 digit Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Your account number is "<<accountnumber<<" your street address/street name is "<<streetname<<" and your phone number is "<<phonenumber<<" your identity number is "<<identityNumber<<endl;
        break;

    case 5:
         cout<<"TO LOGIN FOLLOW THE FEW STEPS "<<endl;
        cout<<"Enter your name "<<endl;
        cin>>username;
        cout<<"Enter your surname "<<endl;
        cin>>surname;
        cout<<"Enter your Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Enter your account balance "<<endl;
        cout<<accountbalance;
        cout<<"Your name is is "<<username<<" your surname is "<<surname<<" your identity number is "<<identityNumber<<" your account number is "<<accountnumber<<endl;

    }
     cout<<"Enter 1 to deposit "<<endl;
    cout<<"Enter 2 to withdraw "<<endl;
    cout<<"Enter 3 to account balance"<<endl;
    cout<<"Enter 4 for card replacement "<<endl;
    cout<<"Enter 5 to login "<<endl;
    cin>>choice;

     switch(choice)
    {

    case 1:
        cout<<"How much would you like to deposit "<<endl;
        cin>>deposit;
        cout<<"you have deposited "<<deposit<<" right into your account"<<endl;
        break;

    case 2:
        cout<<"How much would you like to withdraw "<<endl;
        cin>>withdrawal;
        cout<<"You have withdrawn "<<withdrawal<<" Out of your account "<<endl;
        break;

    case 3:
        cout<<"Your account balance is "<<sum<<endl;
        if (sum <0)
        {
            cout<<"Insufficient amount "<<endl;
        }
        else if( sum >0)
        {
            cout<<"sufficient amount "<<endl;
        }
        cout<<"This is your account balance "<<sum<<" from your account "<<endl;
        break;

    case 4:
        cout<<"THE FINE TO REPLACE YOUR CARD WILL BE R250.00 ,IT CAN EITHER BE CASH OR CREDIT "<<endl;
        cout<<"Please do follow the few simple steps as instructed "<<endl;
        cout<<"One must leave no question/case unanswared "<<endl;
        cout<<"Enter previous nine digit acconunt number "<<endl;
        cin>>accountnumber;
        cout<<"Enter your address/street name "<<endl;
        cin>>streetname;
        cout<<"Enter your 10 digit phone number "<<endl;
        cin>>phonenumber;
        cout<<"Enter you 13 digit Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Your account number is "<<accountnumber<<" your street address/street name is "<<streetname<<" and your phone number is "<<phonenumber<<" your identity number is "<<identityNumber<<endl;
        break;

    case 5:
         cout<<"TO LOGIN FOLLOW THE FEW STEPS "<<endl;
        cout<<"Enter your name "<<endl;
        cin>>username;
        cout<<"Enter your surname "<<endl;
        cin>>surname;
        cout<<"Enter your Identity Number "<<endl;
        cin>>identityNumber;
        cout<<"Enter your account balance "<<endl;
        cout<<accountbalance;
        cout<<"Your name is is "<<username<<" your surname is "<<surname<<" your identity number is "<<identityNumber<<" your account number is "<<accountnumber<<endl;

    }
    return 0;
}
