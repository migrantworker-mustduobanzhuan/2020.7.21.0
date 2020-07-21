# 2020.7.21.0
C++面向对象输入时间输出格式时间
#include<iostream>
using namespace std;
struct 
{
int year;
int month;
int day;
int hour;
int minute;
int second;
}s;
int main()
{cout<<"Input year:"<<endl;
cin>>s.year;
cout<<"Input month:"<<endl;
cin>>s.month;
cout<<"Input day:"<<endl;
cin>>s.day;
cout<<"Input hour:"<<endl;
cin>>s.hour;
cout<<"Input minute:"<<endl;
cin>>s.minute;
cout<<"Input second:"<<endl;
cin>>s.second;
cout<<s.year<<"."<<s.month<<"."<<s.day<<endl;
cout<<s.hour<<":"<<s.minute<<":"<<s.second<<endl;
return 0;
}
