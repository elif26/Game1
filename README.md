# Game1
#include <iostream>
using namespace std;
int main()
{
    char choice;
    cout << "------------------------------------" << endl;
    cout << "        Welcome to the game         " << endl;
    cout << "        -------------------         " << endl;
    cout << "       *** Start new game - A ***" << endl;
    cout << "     *** Enter a new question - B ***" << endl;
    cout << "   *** Edit an existing question - C ***" << endl;
    cout << "             *** Exit - D ***        " << endl;
    cout << "------------------------------------" << endl;
    cout << "Your choice:";
    cin >> choice;
    if (choice == 'A') {
        //new game
        char choice2;
        cout << " A) Geography " << endl;
        cout << " B) History " << endl;
        cout << " C) Literature " << endl;
        cout << " D) All categories" << endl;
        cout << "Your choice:";
        cin >> choice2;
        if (choice2 == 'A') {
            //cout << "kolko";
        }
        if (choice2 == 'B') {

        }
        if (choice2 == 'C') {

        }
        if (choice2 == 'D') {

        }

    }
    if (choice == 'B') {
        //enter new question
        cout << "b";
    }
    if (choice == 'C') {
        //edit
        cout << "c";
    }
    if (choice == 'D') {
        return 0;
        cout << "Press any key to quit";
        
        
    }
 
}
