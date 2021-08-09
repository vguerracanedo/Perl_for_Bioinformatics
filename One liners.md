# One liners

Add a sample ID to fastq header that looks like @1/1 followed by @2/1 and @3/1    
`perl -p -e 's/^(@\d+)\/1$/$1-SRR573675\/1/g'`    
the \d+ will select the columns that start with @ and are followed by numbers only (so this should ignore the other three lines that can start with @ but would have a letter at one point)  



