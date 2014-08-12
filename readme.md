Identifiers
========
>regular expression  
>'[%@][a-zA-Z$._][a-zA-Z$._0-9]*'.  

- @全域變數  
- %區域變數  
- @1 $2這些應該是暫存變數不確定)
- 可用跳脫字元\
- 雙引號夾著有作用  

範例
-----
    %result = mul i32 %X, 8  
-
    %result = shl i32 %X, 3  
-
    %0 = add i32 %X, %X           ; yields i32:%0  
    %1 = add i32 %0, %0           ; yields i32:%1  
    %result = add i32 %1, %1  
    
