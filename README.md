# tbjss
第一个
#include<iostream>
#include<cstdio>
using namespace std;
int main()
{ 
	int m,n,sum;
	cin>>m>>n;
	if(m%2==0) m++;
	while(m<=n){
		sum+=m;
		m=m+2;
	}
	cout<<sum;
	return 0;
}
