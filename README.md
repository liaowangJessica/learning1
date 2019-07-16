＃include <stdio.h>
int main()
{
  int num,a,b,c;
  scanf("%d",&num);
  a=num%10;
  b=num/10%10;
  c=num/100;
  printf("%d",a*100+b*10+c);
  return 0;
  }
  
