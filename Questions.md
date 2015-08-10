1.	画出下面结构体在内存中所占空间的示意图
struct st{
    char a;
    char *c;
    short b;
    short *c;
    int d;
    int *e;    
};

2.	写出下面语句的执行结果

    char *s = "hello";
	char a[] = "hello";
	printf("%d, %d\n", sizeof(s), sizeof(a));

3.	写出下面语句执行结果

    int a[2][3] = { { 1, 2, 3 }, { 4, 5, 6 } };
    int *b = a;
    int *c = &b;
printf("%d, %d, %d, %d\n", *(b + 1), *(c + 1), *b + 1, *c + 1);

已知printf("%d\n", a); 结果为  100,



4.	写完成下面的函数，计算输入数组的和
unsigned short GetSum(unsigned short* arr, unsigned short len){



5.	完成一个链表，分别实现创建，插入和删除操作

