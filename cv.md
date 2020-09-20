1. Darya Tereschenko
2. Call +37529 8761354 or use vk https://vk.com/darytereshchenko
3. I want to work as a full stack developer and be able to travel anywhere
4. a little c++ and java, git, math, html&css
5. 
```#include <iostream>
#include <cmath>
using namespace std;
void Polinom(double* x, double* L, int i) {
	double K[10];
	int I = 0;
	for(int j = 0; j < 11; ++j)
		if(i != j) {
			K[I] = (-1) * x[j];
			I++;
		}
	L[0] = 1;
	for(int j = 1; j < 10; ++j)
		L[j] = 0;
	L[1] = K[0] + K[1] + K[2] + K[3] + K[4] + K[5] + K[6] + K[7] + K[8] + K[9];
	L[10] += K[0] * K[1] * K[2] * K[3] * K[4] * K[5] * K[6] * K[7] * K[8] * K[9];
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k) 
			L[2] += K[j] * K[k];
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				L[3] += (K[j] * K[k] * K[u]);
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				for(int y = u + 1; y < 10; ++y)
					L[4] += (K[k] * K[j] * K[u] * K[y]);
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				for(int y = u + 1; y < 10; ++y)
					for(int q = y + 1; q < 10; ++q)
						L[5] += (K[k] * K[j] * K[u] * K[y] * K[q]);
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				for(int y = u + 1; y < 10; ++y)
					for(int q = y + 1; q < 10; ++q)
						for(int r = q + 1; r < 10; ++r)
							L[6] += (K[k] * K[j] * K[u] * K[y] * K[q] * K[r]);
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				for(int y = u + 1; y < 10; ++y)
					for(int q = y + 1; q < 10; ++q)
						for(int r = q + 1; r < 10; ++r)
							for(int w = r + 1; w < 10; ++w)
								L[7] += (K[k] * K[j] * K[u] * K[y] * K[q] * K[r] * K[w]);
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				for(int y = u + 1; y < 10; ++y)
					for(int q = y + 1; q < 10; ++q)
						for(int r = q + 1; r < 10; ++r)
							for(int w = r + 1; w < 10; ++w)
								for(int z = w + 1; z < 10; ++z)
									L[8] += (K[k] * K[j] * K[u] * K[y] * K[q] * K[r] * K[w] * K[z]);
	for(int j = 0; j < 10; ++j)
		for(int k = j + 1; k < 10; ++k)
			for(int u = k + 1; u < 10; ++u)
				for(int y = u + 1; y < 10; ++y)
					for(int q = y + 1; q < 10; ++q)
						for(int r = q + 1; r < 10; ++r)
							for(int w = r + 1; w < 10; ++w)
								for(int z = w + 1; z < 10; ++z)
									for(int p = z + 1; p < 10; ++p)
										L[9] += (K[k] * K[j] * K[u] * K[y] * K[q] * K[r] * K[w] * K[z] * K[p]);
}
double Value(double x) {
	double p = pow(x, sqrt(11.0)) + 1;
	return (cos(acos(-1.0) * x) / p);
}
double Value1(double x) {
	double p = pow(x, sqrt(11.0)) + 1;
	double q = (-acos(-1.0) * sin(acos(-1.0) * x)) * p - sqrt(11.0) * pow(x, sqrt(11.0) - 1) * cos(acos(-1.0) * x);
	return q / (p * p);
}
double Value2(double x) {
	double p = pow(x, sqrt(11.0)) + 1;
	double t = (-acos(-1.0) * acos(-1.0) * p * cos(acos(-1.0) * x) - sqrt(11.0) * (sqrt(11.0) - 1) * cos(acos(-1.0) * x) * pow(x, sqrt(11.0) - 2)) / (p * p);
	double y = 2 * sqrt(11.0) * pow(x, sqrt(11.0) - 1) * (-acos(-1.0) * p * sin(x * acos(-1.0)) - sqrt(11.0) * pow(x, sqrt(11.0) - 1) * cos(acos(-1.0) * x) ) / (p * p * p);
	return t - y;
}
```
6. university practice, many online html,css and js courses, platforms like cosewars and so on
7. university practice, many online html,css and js courses, platforms like cosewars and so on
8. communication with native speakers, school & university lessons
