链表问题算法难度不高，主要是考察代码实现能力。	
指针设计很多操作，需要仔细考虑，容易考虑不周。	

链表和数组		
 
	都是一种线性空间		
    数组是一段连续的存储空间	
    链表空间不保证连续，临时分配空间	

代码实现关键点		

    链表调整函数的返回值类型，根据要求往往是节点类型	
    处理链表过程中，先采用画图的方式理清逻辑。	
    链表问题对于边界条件讨论要求严格。头结点，尾节点，空节点等问题	


链表插入和删除的注意事项

    特殊处理链表为空，或者链表长度为1的情况
    注意插入操作的调整过程
    注意删除操作的调整过程
    注意头尾节点和空节点需要特殊处理
    双链表插入和删除类似，需要额外考虑previous指针的指向


单链表的翻转操作	

大量链表问题可以使用额外数据结构来简化调整过程		
链表问题的最优解往往是不适用额外数据结构的方法