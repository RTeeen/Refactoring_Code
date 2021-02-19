# Refactoring_Code

(1). I used Megan's starter pack so there are some initial commits from her.
(2). Me, Ryan and Steve did the majority of the lab together. (except the readings :)
(3). Biggest issue we faced: 
Initially we were passing our original data (as string, number array, LinkedListGroup) to sortUtil function while we were supposed to pass it the 
handler class so we can use the unique compare and swap function for each datatype. In effect of that, we couldn't get rid of the excessive use of Type Guards (the if statements)
so our logic in sortUtil was 3x longer. with solving that issue we refactored our code so it can automaticlly call the swap and compare function of it's own datatype.
