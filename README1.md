# circle
如何用1角、2角和5角的硬币凑出10元以下的金额？
/* Note:Your choice is C IDE */
#include "stdio.h"
int main()
{
	//如何用1角、2角和5角的硬币凑出10元以下的金额？
 int x;
 int one,two,five;
 
 	//printf("你想要加总得几元：");
  	//scanf("%d",&x);
  	
	x=2;//用2元做下示范
   for(one=1;one<x*10;one++){
   	 for(two=1;two<x*10/2;two++){
   		for(five=1;five<x*10/5;five++){
   			if(one+two*2+five*5==x*10){
   	printf("可以用%d个1角加%d个2角加%d个5角得到%d元\n",one,two,five,x);
    
   			 }
   			}
   		}
   	 }
    return 0;
}
