##include<stdio.h>
int main()
{
  int input = 0;
  printf("上大学\n");
  printf("你有认真学习了吗？(1/0):");
  scanf("%d",&input);
  if(input == 1)
    printf("有个好成绩\n");
  else 
    printf("浑浑噩噩\n");
   return 0;
}
