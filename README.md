#include <iostream>
#include <cstdlib>
using namespace std;

int main()
{

    int n = 10;
    int nx = 100;
    int z = 30;
    int gab;

do
{

   system("cls");

    gab = (nx / n) + n * nx;

    std::cout << "Write yor result here: \n" ;
    std::cin >> gab;
    std::cout << gab <<"\n";

    if (gab> z)
    {
        std::cout << "Run away\n";
    }
    else if (gab==z)
    {
        std::cout<< "Are you alredy ? \n" ;
    }
    
    else
    {
        std::cout << "Return to base\n";
    }
    std::cout << gab << " Result " << "\n";

    std::cout <<"Try again ? (0 to try or 1 to end quest )\n";

    int again;
    cin>> again;

    if (again !=1){
        
    }else if (again ==1){
std::cout<< "Okay!! my lil homie, thanks to meet you, see you again\n ";
break;
    }

} while(true);
    return 0;
}

