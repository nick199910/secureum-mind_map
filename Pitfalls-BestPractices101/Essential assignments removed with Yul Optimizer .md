# 87 - [Essential assignments removed with Yul Optimizer ](Essential%20assignments%20removed%20with%20Yul%20Optimizer%20.md)
The Yul optimizer can remove essential assignments to variables declared inside `for` loops when Yul's `continue` or `break` statement is used mostly while using inline assembly with `for` loops and `continue` and `break` statements. This is due to a compiler bug introduced in `v0.5.8`/`v0.6.0` and fixed in `v0.5.16`/`v0.6.1`. (see [here](https://docs.soliditylang.org/en/v0.8.9/bugs.html))
___
## Slide Screenshot
![087.png](../images/pitfalls_and_best_practices101/087.png)
___
## Slide Text
- 
___
## References
- Youtube Reference
___
## Tags