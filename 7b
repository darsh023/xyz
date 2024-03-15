#include <iostream>
#include<cmath>
using namespace std;
class dist
{
	int feet ;
	float inches;
 
 public:
 	void getdist()
 	{
 		cout<<"Enter distance(feet,inches):-";
 		cin>>feet>>inches;
 	}
 	void putdist()
 	{
 		cout<<"feet="<<feet<<"inches="<<inches<<endl;
 	}
 	dist adddata(const dist d1,const dist d2)
 	{
 		dist result;
 		result.feet = d1.feet + d2.feet;
 		result.inches = d1.inches + d2.inches;
 		if(result.inches>=12)
 		{
 			result.feet+=static_cast<int>(result.inches/12);
 			result.inches=fmod(result.inches,12);
 		}                    
 		return result;
 	} 	
};
int main()
{
	dist d1,d2;
	d1.getdist();
	d2.getdist();
	dist sum= d1.adddata(d1,d2);
	cout<<"sum of distans"<<endl;
	sum.putdist();
	return 0;
	}

