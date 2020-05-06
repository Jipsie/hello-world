#include<iostream>
#include<cstdlib>

using namespace std;

int main()
{
    int choose_r,U_ans,ans,rand_no1=rand()%100,rand_no2=rand()%100,rand_no3=rand()%1000,rand_no4=rand()%1000,rand_no5=rand()%10000,rand_no6=rand()%10000;
    
    cout<<"\n1. Below 100";
    cout<<"\n2. Below 1000";
    cout<<"\n3. Below 10000";
    cout<<"\nChoose a range = ";
    cin>>choose_r;
    
    cout<<"\n---------------------------";
    
    if(choose_r==1)
    {   cout<<"\n\n\nThe first number is = "<<rand_no1;
        cout<<"\nThe second number is = "<<rand_no2;
        cout<<"\nThe answer is = ";
        cin>>U_ans;
        ans=rand_no1+rand_no2;
        
        cout<<"\n---------------------------";
        
        if(ans==U_ans)
        {   cout<<"\n\nYou are right, Welldone"; }
        
        else
        {   cout<<"\n\nNo, The answer is "<<ans;
            cout<<"\nBetter luck next time";  }
    }
    
    else if(choose_r==2)
    {   cout<<"\n\nThe first number is = "<<rand_no3;
        cout<<"\nThe second number is = "<<rand_no4;
        cout<<"\nThe answer is = ";
        cin>>U_ans;
        ans=rand_no3+rand_no4;
        
        cout<<"\n---------------------------";
        
        if(ans==U_ans)
        {   cout<<"\n\nYou are right, Welldone"; }
        
        else
        {   cout<<"\n\nNo, The answer is "<<ans;
            cout<<"\nBetter luck next time";  }
    }
    
    else
    {   cout<<"\n\nThe first number is = "<<rand_no5;
        cout<<"\nThe second number is = "<<rand_no6;
        cout<<"\nThe answer is = ";
        cin>>U_ans;
        ans=rand_no5+rand_no6;
        
        cout<<"\n----------------------------";
        
        if(ans==U_ans)
        {   cout<<"\n\nYou are right, Welldone"; }
        
        else
        {   cout<<"\n\nNo, The answer is "<<ans;
            cout<<"\nBetter luck next time";  }
    }
    
    return 0;
}
