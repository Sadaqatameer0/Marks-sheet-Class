#include <iostream>
using namespace std;

class Student {
private:
    int marks;  

public:
    void setMarks(int m) {
        marks = m;
    }

    void showMarks() {
        cout << "Marks = " << marks;
    }
};

int main() {
    Student s1;

    s1.setMarks(85);
    s1.showMarks();

    return 0;
}
