# Square-in-C

#include<stdio.h>
#include<string.h>
int main(){
  int a, b, input;
  char cha;
  printf("Enter the character:  ");
  scanf("%c", &cha);
  printf("Enter the stars:  ");
  scanf("%d", &input);
  for(a=1; a<=input; a++)
  {
    for(b=1;b<=input;b++)
    {
      printf(" %c",cha);
    }
    printf("\n");
  }
}
