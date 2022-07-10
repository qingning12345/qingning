#include<stdio.h>
int main()
{
	char arr[] = "hello world";
	memset(arr, 'a', 7);//memset修改内容
	printf("%s\n", arr);
	


	return 0;
}
