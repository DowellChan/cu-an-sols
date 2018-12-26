# Clemson Math Analysis Prelim Solutions

Email me awgreen@clemson.edu if you want to contribute, so I can add you on GitHub.

## Goals
The first goal is to gather together all the solutions. So, if you have some, go ahead and edit the already existing `analysis_sol_mmyy.tex` files to add them. It is totally fine to have multiple answers to a problem (especially if they are different). If you want to put your name with your solutions, go for it.

If you are not comfortable editing and doing the github stuff, just upload some of your own (labeled) `.tex` files to the `solution-dump` folder and others can clean them up and put things together.

The second goal is to make the solutions nice and correct. Many of my solutions were written a long time ago and they may be wrong. They could almost certainly be cleaned up and made more concise.

The final goal is NOT to complete all the problems. That will be no fun. But I will try to make some realistic goals and identify the worthwhile problems for which to write up solutions.

## Organization 
Each exam's solutions are stored in the `.tex` file with their date. The only file to compile is `analysis_prelim_sols.tex` which gathers together all these solutions into a giant pdf.

## Referencing
It may be the case that a problem is repeated or a solution is super similar to another. If so, the completed solution should be labeled by
```
\phantomsection\label{q:<problem>}
```
and then referenced as
```
See \hyperref[q:<problem>]{<Summer/Winter> <Year> \#<Number>}
```
For example, if Summer 09 #4 has the solution which is written in Winter 14 #8, on Winter 14 #8, place the label
```
\phantomsection\label{q:w14-8}
```
and the entry in Summer 09 will be
```
\item[4.] See \hyperref[q:w14-8]{Winter 14 \#8}
```