#include<stdio.h>
int main()
{
	 char iAddition1;
	 char iAddition2;
	 int iAddition3=0;
	 char iMeiosis;
	 char iMinuend;
	 int iDifference=0;
	 char iFactor1;
	 char iFactor2;
	 int iProduct=0;
	 char iDividend;
	 char iDivisor;
	 int iMerchant=0;
	 int iSelect=99;
	 while(iSelect!=0)
	 {
		  printf("----操作选项----\n");
		  printf("----加法运算---1\n");
		  printf("----减法运算---2\n");
		  printf("----乘法运算---3\n");
		  printf("----除法运算---4\n");
		  printf("------退出-----0\n");
		  printf("按数字键选择要执行的操作: ");
		  scanf("%d",&iSelect);
		  switch(iSelect)
			{
				case 1:
					printf("请输入第一个加数："); 
					scanf("%d",&iAddition1);
					printf("请输入第二个加数："); 
					scanf("%d",&iAddition2);
					iAddition3 = iAddition1 + iAddition2;
					printf("和为%d\n",iAddition3);
					break;
				case 2:
					printf("请输入被减数：");
					scanf("%d",&iMeiosis);
					printf("请输入减数：");
					scanf("%d",&iMinuend);
					iDifference = iMeiosis - iMinuend;
					printf("差为%d\n",iDifference); 
					break;
				case 3:
					printf("请输入第一个乘数：");
					scanf("%d",&iFactor1);
					printf("请输入第二个乘数：");
					scanf("%d",&iFactor2);
					iProduct = iFactor1 * iFactor2;
					printf("积为%d\n",iProduct);
					break;
				case 4:
					printf("请输入除数；");
					scanf("%d",&iDividend);
					printf("请输入被除数；");
					scanf("%d",&iDivisor);
					iSelect = iDividend / iDivisor;
					printf("商为%d\n",iSelect); 			
					break;
				case 0:
					printf("正在退出...\n");
					printf("退出成功！\n");
					break;
				default:
			 		printf("没有此选项！\n");
					break;
			}
	 }
 return 0;
}
