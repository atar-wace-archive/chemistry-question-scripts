# atar chemistry old question scripts

pdftk scripts that I made a year ago to pick out good/relevant ATAR chemistry questions from the old wace system past exams (pre-2015). This is because these older exams have some stuff that is no longer in the new syllabus as of 2020 (when I made these scripts/did the exam), so I just got rid of them with these scripts. This was part of my plan to trihard chemistry and get a good mark over 90% (which did happen surprisingly).

Answers are at the back of the generated PDFs.\
Note that some of these questions don't have answers (as it seems they didn't publicly release marking keys to students, only through the teacher portal). So answers may be missing depending on whether I could find a marking key pdf.

## Guide

You need pdftk installed/on the `$PATH` for these to work.\
copy the scripts to the `ROOT/chemistry` directory, assuming you bulk-downloaded the old files using the script generated by my site. For reference, your directory structure should look like this with these scripts.

Run each script to generate a PDF containing relevant questions. Some may have irrelevant questions at the start/end because I can only copy whole pages and not subpages, so use your judgement to ignore them.
```
This is from the ROOT/chemistry directory:
.
|-- 2007-2008_wace_draft
|-- 2010
|-- 2011
|-- 2012
|-- 2013
|-- 2014
|-- 2015
|-- 2015-2016_wace1516_samples
|-- 2016
|-- 2017
|-- 2018
|-- 2019
|-- acid&equilibrium.sh
|-- empirical.pdf
|-- empirical.sh
|-- mcq.sh
|-- org.sh
|-- redox.sh
|-- relevant_questions.sh
|-- stoichiometry.sh
`-- titration.sh

12 directories, 9 files
```