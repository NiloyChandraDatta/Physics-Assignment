#include<bits/stdc++.h>
using namespace std;
int main() {
    double lamda_green = 530e-9;
    double lamda_red = 700e-9;
    int m_green = 3;
    int m_red = 2;
    double theta_green_deg = 65.0;

    double theta_green_rad = theta_green_deg* 3.1416 / 180.0;
    double d = (m_green * lamda_green) / sin(theta_green_rad);
    double sin_theta_red = (m_red * lamda_red)/ d;
    if(sin_theta_red > 1.0) {
        cout<<" Error : No solution exists as sin(theta) exceeds 1." << endl;
    } else {
        double theta_red_rad = asin(sin_theta_red);
        double theta_red_deg = theta_red_rad* 180.0 / 3.1416;
        cout << " The angle for the the second-order bright spot for red light is : "<< theta_red_deg << " degrees." << endl;
    }
    return 0;
}
