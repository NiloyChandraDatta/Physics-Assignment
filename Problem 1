//the Wavelength Calculator 

#include<bits/stdc++.h>

using namespace std;

string getColor(double wavelength_nm) {

    if(wavelength_nm >= 380 && wavelength_nm < 450)
    return  " Voilet ";
    if(wavelength_nm>= 450 && wavelength_nm < 485)
    return " Blue ";
    if(wavelength_nm>= 485 && wavelength_nm < 500)
    return " Cyan ";
    if(wavelength_nm >= 500 && wavelength_nm < 565)
    return  " Green ";
    if(wavelength_nm>= 565 && wavelength_nm < 590)
    return " Yellow";
    if(wavelength_nm>= 590 && wavelength_nm < 625)
    return " Orange ";
    if(wavelength_nm>= 625 && wavelength_nm < 750)
    return " Red ";

    return " Out of visible spectrum ";
}

void calculateWavelength() {
    double m , theta_deg, d;
    cout<< " Enter order(m): ";
    cin>>m;
    cout<<" Enter angle  θ (degrees): ";
    cin >>theta_deg;
    cout<< "Enter slit separation (d) in  micrometre : ";
    cin >>d;
    double theta_rad = theta_deg* M_PI / 180.0 ;
    double wavelength_nm = (d*1e3*sin(theta_rad)) / m ;

    cout<< " Wavelength : " << wavelength_nm << " nm\n";
    cout <<" Color :" << getColor(wavelength_nm) << endl;

}

int main(){
    calculateWavelength();
    return 0;
}
