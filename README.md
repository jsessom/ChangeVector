# ChangeVector
Use function to change a vector 
#include "stdafx.h"
#include <iostream>
#include <string>
#include <fstream>

using namespace std;

class Point
{ 
	public:

		double x, y;



};

class Vector
{

public:
	Point start, end;
};


void changexy(double changex, double changey)
{

	changex = +3.0;
	changey = +4.0;



}


int main()
{

	Vector vec1, vec2;
	Point x, y;
	vec1.start.x = 0.0;
	vec2.start.y = 2.0;

	vec1.end.x = 3.0;
	vec2.end.y = 5.0;
	changexy(vec1.start.x, vec2.start.y);
    return 0;
}
