#include <bits/stdc++.h>

using namespace std;

int main()
{
    ios_base::sync_with_stdio(0); cin.tie(0); cout.tie(0);
    long long n;

      while(cin>>n,n)
      {
          vector<int>v;
          for(int i=0; i<n; i++)
          {
              int x;
              cin>>x;
              v.push_back(x);
          }
          sort(v.begin(),v.end());
          for(int j=0; j<n;j++)
          {
              if(i<n-1)
              cout<<v[j]<<" ";
              else
              cout<<v[j];
          }
      }

    return 0;
}
