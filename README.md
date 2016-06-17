//save this file as hello.c in a folder called "ccode"
//compile with $gcc hello.c -o hello
//run with the command: $./hello
#include<stdio.h>
main()
{
	int i;
	printf("Hello world");
	for (i = 0 ; i < 10; i++){
		printf("%d Hello World \n",i);
	}
}

