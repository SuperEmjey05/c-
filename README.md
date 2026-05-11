#include <iostream>
using namespace std;
int main() {
    string name;
    int APgrade;
    int Mathgrade;
    int FilipinoGrade;
    int EnglishGrade;
    int MAPEHgrade;
    int ScienceGrade;
    int TLEgrade;

    cout << "Enter student name: ";
    cin >> name;
    cout << "Enter A.P. grade: ";
    cin >> APgrade;
    cout << "Enter Math grade: ";
    cin >> Mathgrade;
    cout << "Enter Filipino grade: ";
    cin >> FilipinoGrade;
    cout << "Enter English grade: ";
    cin >> EnglishGrade;
    cout << "Enter MAPEH grade: ";
    cin >> MAPEHgrade;
    cout << "Enter Science grade: ";
    cin >> ScienceGrade;
    cout << "Enter TLE grade: ";
    cin >> TLEgrade;

    double average = (APgrade + Mathgrade + FilipinoGrade + EnglishGrade + MAPEHgrade + ScienceGrade + TLEgrade) / 7.0;
    cout << "Average grade: " << average << endl;

    cout << "Hello, " << name << "! Your average grade is " << average << ".";
    return 0;
};
