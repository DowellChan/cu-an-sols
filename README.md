# Clemson Math Analysis Prelim Solutions
## Organization 
Each exam's solutions are stored in the `.tex` file with their date. The only file to compile is `analysis_prelim_sols.tex` which gathers together all these solutions into a giant pdf.

## Referencing
It may the case that an problem is repeated or a solution is super similar to another. If so, the completed solution should be labeled by
```\phantomsection\label{q:<problem>}```
and then referenced as
```See \hyperref[q:<problem>]{<Summer/Winter> <Year> \#<Number>}```
For example, if Summer 09 #4 has the solution which is written in Winter 14 #8, on Winter 14 #8, place the label
```\phantomsection\label{q:w14-8}```
and the entry in Summer 09 will be
```\item[4.] See \hyperref[q:w14-8]{Winter 14 \#8}```