# assignment2
#include <iostream>

using namespace std;

int main()
{
    int total_student;
    double marks;
    int age;
    double product=marks*age;
    cout<<"enter enter total number of students in the class: ";//this part is for the lecturer;
    cin>>total_student;
    int counter=1;
    while(counter<=total_student){
        cout<<"enter your current age: ";
            cin>>age;
        cout<<"enter your exams score: ";
            cin>>marks;
        cout<<age<<marks<<endl;
        cout<<product;
    }
    system("pause>0");
}
