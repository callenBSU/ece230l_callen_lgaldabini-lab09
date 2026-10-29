# Sequential Circuits: Latches

In this lab, you learned about the basic building block of sequential circuits: the latch.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Names
Connor Allen, Logan Galdabini

## Summary
For this lab, we both implemented sequential logic circuits. Sequential logic circuits are
circuits that factor in before and after signals, aka memory. We learned, implemented, and
tested d-latch circuits to hold and use memory.

## Lab Questions

###  Why can we not just use structural Verilog to implement latches?
We can't do that because of sensitivity blocks. We also can't do it because of the reg keyword.

### What is the meaning of always @(*) in a sensitivity block?
@(*) means that it holds continuous assignment and no memory is needed.

### What importance is memory to digital circuits?
Memory is important because it lets us store, use, and remove binary data.