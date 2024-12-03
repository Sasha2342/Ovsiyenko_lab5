# Ovsiyenko_lab5

#include <iostream>
using namespace std;

int main(){
    
    int matrix[4][4];

    cout<<"Введіть елементи матриці 4x4:"<<endl;
    for (int i = 0; i < 4; ++i) {
        for (int j = 0; j < 4; ++j) {
            cin>>matrix[i][j];
        }
    }

    cout<<"Транспонована матриця:"<<endl;
    for (int i = 0; i < 4; ++i) {
        for (int j = 0; j < 4; ++j) {
            cout<<matrix[j][i]<<" ";
        }
        cout<<endl;
    }

    return 0;
}
