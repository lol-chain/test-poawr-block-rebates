[ Photo ]
Created tests/br_conditional.go

In order to test block_rebates triggered by conditionals

To execute the program in go
i.e 
go run br_conditional.go
or build the program 
go build br_conditional.go
then run the executable
./br_conditional.exe

https://github.com/lol-chain/go-kekchain-testnet/blob/main/tests/br_conditional.go

In example above, first 2 blocks are logging 
"disabled rebates: blockNumber

This is further proof the expected outcome is produced down the call line. Although in main net BR is activated on genesis, and disabled post final subsidy trigger. 

Take notice post final subsidy activation there is no 
"REBATE AMOUNT: xY

  This indicates the function won't reach the line where it would add rebate to oracle contract balance in main source.
 
Tests resulted in optimized final code applied and merged to main branch.
 Marvelous. Thanks, M
