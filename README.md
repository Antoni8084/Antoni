#include <iostream>
using namespace std;

int main() {
    int score = 0, answer;

    cout << "Welcome to the Quiz!\n";

    cout << "Q1: What is 2 + 2?\n1. 3\n2. 4\n3. 5\nYour answer: ";
    cin >> answer;
    if (answer == 2) score++;

    cout << "Q2: What is the capital of France?\n1. Berlin\n2. Madrid\n3. Paris\nYour answer: ";
    cin >> answer;
    if (answer == 3) score++;

    cout << "You scored: " << score << "/2\n";
    return 0;
}
