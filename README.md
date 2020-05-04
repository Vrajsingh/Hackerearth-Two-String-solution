# Hackerearth-Two-String-solution
My cpp code for hackerearth Two String solution

#include<bits/stdc++.h>
using namespace std;
int main()
{
    string s1[100]={},s2[100]={},s[2]={"YES","NO"};
    int n;
    cin>>n;
    for(int i=0;i<n;i++)
    {
       cin>>s1[i]>>s2[i];
       sort(s1[i].begin(),s1[i].end());
       sort(s2[i].begin(),s2[i].end());
    }
    for(int i=0;i<n;i++)
    {
        if(s1[i] == s2[i])
            cout<<s[0]<<endl;
        else
            cout<<s[1]<<endl;
    }

    return 0;
}

-by VISHAL RAJ
CONTRIBUTER
