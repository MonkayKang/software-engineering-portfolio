## Defects and Decision Points
### Task 1 Manual Code Walkthrough
- The total number of complexity points is 11. While there is no loop it does crosses McCabe's threshold of 10 cyclomatic complexity decision points
- For each destination of where the code is going, each has three duplication logic that the weights are repeated. For unclear naming, multiple variables are not named properly such as "c", "wt, "p", and "q". These could be very hard to understand what these variables could mean. Also, the values are hard coded meaning that they cant be changed very easily and are already defined.
- The cyclomatic complexity, duplication logic in the code, an number of conditions are all Internal Attributes. Readability, organization, naming quality, and design quailty are all Human Judgement.

### Task 2 Defect Density
- System A: 45/30 = 1.5 defect density
- System B: 15/6 = 2.5 defect density
- System A looks better because the overall defect density is smaller than System B and is under the 2 defects/KLOC threshold. 

- The comparison may be unfair as one could have a more thoroughly tests than the other and would therefore uncover more defects (More tests = more defects). They could also be a different type of software as one could have a more strict requirement which has different purpose and quality. Finally there could be differences on how the defects are counted. A company might only count serious defects while minor ones are ignored or count lines of code differently.
- While one system might look good compare the other, it could be unfair to compare the two because of a multitude of reasons. It all comes down to how many tests were done, how they were tested, and what method was used to count the defects.
