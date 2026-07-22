#include<iostream>
using namespace std;

bool searchPlayer(char playerInitials[], int teamSize, char targetInitial)
{
    for (int index = 0; index < teamSize; index++)
    {
        if (playerInitials[index] == targetInitial)
        {
            return true;
        }
    }
    return false;
}

int main()
{
    int teamSize = 11;
    char playerInitials[11];
    for (int index = 0; index < teamSize; index++)
    {
        cin >> playerInitials[index];
    }
    char targetInitial;
    cin >> targetInitial;
    bool isFound = searchPlayer(playerInitials, teamSize, targetInitial);
    if (isFound)
    {
        cout << "Player is in the team";
    }
    else
    {
        cout << "Player not found";
    }
    return 0;
}
