#include <stdio.h>
#include <cs50.h>

int main(void)
{
    string name = get_string("What is your name?\n");  //write a name
    printf("Hi,%s \n", name);  // A name appears with greeting
}