Magic square :

Magic square means sum of elements in any column or any row or diagonal are equal.

Steps:

1.In any magic square,1 is located at(n/2,n-1)

2.Let's say the position of 1 i.e.(n/2,n-1) is (p,q),then next number which is 2 is located at (p-1,q+1)position.
   Anytime if the calculated row position becomes -1 then make it n-1 and if column position becomes n then make it 0.
   
3.If the calculated position already contains a number then decrement the column by 2 and increment the row by 1.

4.If anytime position becomes -1 and column becomes n,switch it to(0,n-2).
