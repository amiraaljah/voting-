# voting-

#include <iostream>
#include<string>
using namespace std;

struct Candidate{
 int age;
 string name;

    void readCandidate(){
     cout <<"Enter the name of the candidate : " << endl;
     cin >> name;
     cout << "Enter the age of the candidate: " << endl;
     cin >> age ;
  }

     void writeCandidate(){
     cout << "\n name:" << name <<"\n age:"<< age << endl;
  }
};

int main()
{
   Candidate candidate;
   candidate.readCandidate();
   candidate.writeCandidate();
   return 0;
}
