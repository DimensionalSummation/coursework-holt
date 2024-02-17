#Shell Assignment
author: Lucas Holt
date created: 2024-01-29

#Task 1
cd work/classes/GPGN268/coursework-holt/
mkdir short-assignments
cd short-assignments/

#Task 2
ls -F north-pacific-gyre/

#Task 3
mkdir NENE-A NENE-B
mv *A.txt NENE-A
mv *B.txt NENE-B

#Task 4
cd NENE-A
wc -l *|sort -r
cd ./NENE-B
wc -l *|sort -r

#Task 5
cd ..
rm *Z.txt

#Task 6
mv shell-assignment.md short-assignments/
