# Breaking-nested-loops

outerloop:
for (var i = 0;i<3;i++){
 innerloop:
 for (var j = 0;j <3; j++){
 console.log(i);
 console.log(j);
 if (j == 1){
 break outerloop; 
 }
 }
}  
/* 
Output:
0
0
0
1 */
