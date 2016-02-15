#include <stdio.h>
#include <stdlib.h>

//print all permutations: ex. Peter had a good day at the bar

char *names[3] = {"Peter", "Jen", "Jake"};
char *moods[2] = {"good", "bad"};
char *places[3] = {"bar", "beach", "game"};

void printStrPerm();    //prototype

void printStrPerm()
{
    int i;
    int j;
    int k;

    for (i = 0; i < 3; i++)
    {
        for (j = 0; j < 2; j++)
        {
            for (k = 0; k < 3; k++)
            {
                printf("%s had a %s day at the %s.\n", names[i], moods[j], places[k]);
            }
        }
    }
}

int main()
{
    printStrPerm();

    return 0;
}
