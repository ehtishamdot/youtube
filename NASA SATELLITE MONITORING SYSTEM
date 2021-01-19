#include <iostream>
#include <windows.h>
#include <iomanip>
using namespace std;
struct Sattellite
{
 string orbit;
 string type;
 int range;
 int timings;
 double frequency;
 int distanceorbit;
}p1[3], p2[3], p3[3];
int *d1, *d2, *d3;
int* september[3] = {d1,d2,d3}; 
Page 5 of 9
int l1[3],l2[3],l3[3];
string l4[3], l5[3], l6[3]; // FOR FAR DISTANCE SETTLITES
string p4[3],p5[3],p6[3]; // FOR SHORT DISTANCE SETTLITES
void mercury()
{
 int temp;
 for (int i = 0; i < 3; i++)
 {
 cout << "Enter The Type(NAME) Of Satellite: " << endl;
 cin >> p1[i].type;
 cout << "Enter The Name of Planet satellite is orbiting: " << endl;
 cin >> p1[i].orbit;
 cout << "Enter The Range Of Satellite: " << endl;
 cin >> p1[i].range;
 cout << "Enter The Frequency Of Satellite: " << endl;
 cin >> p1[i].frequency;
 cout << "Enter The Distance Of Satellite From Planet: " << endl;
 cin >> p1[i].distanceorbit;
 }
 d1 = &p1[0].distanceorbit;
 for (int j = 0; j < 3; j++)
 {
 temp = p1[j].distanceorbit;
 if (temp < *d1)
 {
 d1 = &temp;
 }
 else
 {
 l1[j] += temp;

 }
 }
 for (int k = 0; k < 3; k++)
 {
 if (p1[k].distanceorbit == *d1)
 {
 p4[1] += p1[k].type;
 cout << "NEAREST PLANET IS " << p1[k].type << endl;
 }
 else
 {
 l4[3] += p1[k].type;
 }
 }
}
void venus()
{
 int temp;
 for (int i = 0; i < 3; i++)
 {
 cout << "Enter The Type(NAME) Of Satellite: " << endl;
 cin >> p2[i].type;
 cout << "Enter The Name of Planet satellite is orbiting: " << endl;
 cin >> p2[i].orbit;
 cout << "Enter The Range Of Satellite: " << endl;
 cin >> p2[i].range;
 cout << "Enter The Frequency Of Satellite: " << endl;
 cin >> p2[i].frequency;
 cout << "Enter The Distance Of Satellite From Planet: " << endl;
 cin >> p2[i].distanceorbit;
 }
 d2 = &p2[0].distanceorbit;
 for (int j = 0; j < 3; j++)
 {
 temp = p2[j].distanceorbit;
 if (temp < *d2)
 {
 d2 = &temp;
 }
 else
 {
 l2[j] += temp;
 }
 }
 for (int k = 0; k < 3; k++)
 {
 if (p2[k].distanceorbit == *d2)
 {
 p5[1] += p2[k].type;
 cout << "NEAREST PLANET IS " << p2[k].type << endl;
 }
 else
 {
 l5[3] += p2[k].type;
 }
 }
}
void earth()
{
 int temp;
 for (int i = 0; i < 3; i++)
 {
 cout << "Enter The Type(NAME) Of Satellite: " << endl;
 cin >> p3[i].type;
 cout << "Enter The Name of Planet satellite is orbiting: " << endl;
 cin >> p3[i].orbit;
 cout << "Enter The Range Of Satellite: " << endl;
 cin >> p3[i].range;
 cout << "Enter The Frequency Of Satellite: " << endl;
 cin >> p3[i].frequency;
 cout << "Enter The Distance Of Satellite From Planet: " << endl;
 cin >> p3[i].distanceorbit;
 }
 d3 = &p3[0].distanceorbit;
 for (int j = 0; j < 3; j++)
 {
 temp = p3[j].distanceorbit;
 if (temp < *d3)
 {
 d3 = &temp;
 }
 else
 {
 l3[j] += temp;
 }
 }
 for (int k = 0; k < 3; k++)
 {
 if (p3[k].distanceorbit == *d3)
 {
 p6[1] += p3[k].type;
 cout << "NEAREST PLANET IS " << p3[k].type << endl;
 }
 else
 {
 l6[3] += p3[k].type;
 }
 }
}
int main()
{
 mercury();
 venus();
 earth();
 system("PAUSE");
 system("CLS");
 cout << ":::: NASA SATELLITE MONITORING SYSTEM ::::" << endl;
 cout << ":::: MERCURY ::::" << endl;
 cout << "NAME" << setw(20) << "RANGE" << setw(15) << "FREQUENCY" << setw(15) <<"ORBIT" << setw(15) << ":::: NEAREST SATTELITE ::::" << setw(15) << ":::: FARSATTELITES ::::" << endl;
 for (int i = 0; i < 3; i++)
 {
 cout << p1[i].type << setw(15) << p1[i].range << setw(15) << p1[i].frequency<< setw(15) << p1[i].orbit << setw(15) << p4[1]<< setw(15) << l4[i] << endl;
 }

 cout << ":::: NASA SATELLITE MONITORING SYSTEM ::::" << endl;
 cout << ":::: VENUS ::::" << endl;
 cout << "NAME" << setw(20) << "RANGE" << setw(15) << "FREQUENCY" << setw(15) <<"ORBIT" << setw(15) << ":::: NEAREST SATTELITE ::::" << setw(15) << ":::: FAR SATTELITES ::::" << endl;
 for (int i = 0; i < 3; i++)
 {
 cout << p2[i].type << setw(20) << p2[i].range << setw(15) << p2[i].frequency<< setw(15) << p2[i].orbit << setw(15) << p5[1] << setw(15) << l5[i] << endl;
 }

 cout << ":::: NASA SATELLITE MONITORING SYSTEM ::::" << endl;
 cout << ":::: EARTH ::::" << endl;
 cout << "NAME" << setw(20) << "RANGE" << setw(15) << "FREQUENCY" << setw(15) <<"ORBIT" <<setw(15) << ":::: NEAREST SATTELITE ::::" << setw(15) << ":::: FARSATTELITES ::::" << endl;
 for (int i = 0; i < 3; i++)
 {
 cout << p3[i].type << setw(20) << p3[i].range << setw(15) << p3[i].frequency<< setw(15) << p3[i].orbit << setw(15) << p6[1] << setw(15) << l6[i] << endl;
 }

 for (int i = 0; i < 3; i++)
 {

 cout << endl;
 }


}
