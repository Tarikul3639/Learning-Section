#include<bits/stdc++.h>
using namespace std;
int main()
{
    int n;
    cin>>n;

    vector<int>v;
    for(int i=0; i<n; i++)
    {
        int x;
        cin>>x;
        v.push_back(x);
    }
     int x=0;
    cin>>x;
    sort(v.begin(), v.end());
    reverse(v.begin(),v.end());
    int ans=0;
    for(int i=0; i<n; i++)
    {
        ans+=x/v[i];

        x-=x/v[i] * v[i];

    }
  cout<<ans<< " ";
}
