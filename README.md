### Attempt the Following Exercise
#### *Write down commands and answers in `day_one_answers.txt` file*
While working from your `home` directory in the server; 

1. Create a directory named `Day_One` and inside `Day_One` create `Exercise` folder and `day_one_answers.txt` file.

2. From inside the `nCoV-2019/V2` folder, copy fasta file named `nCov-2019.reference.fasta` to the `Exercise` folder.

3. Count the number of lines, words and characters in `nCov-2019.reference.fasta`.

4. Also from `Training_set/fastq_pass/barcode87` copy file named `FAT23053_pass_barcode87_ab9ebb45_9.fastq.gz` to `Exercise` folder. Unzip the file using `zcat` command. What is the ID for the first 2 reads of the file.


[Link to Introduction_to_Linux_Slides_](https://kemriwellcometrust-my.sharepoint.com/:p:/g/personal/jmwanga_kemri-wellcome_org/EZTPY9xsGLhPqaU36QeV-swBuUo3onBPyT6BLbBDy3fqFg?e=4Eb7hH)



Code

`trimmomatic PE SS1577_R1.fastq.gz SS1577_R2.fastq.gz SS1577_forward_paired.fastq.gz SS1577_forward_unpaired.fastq.gz SS1577_reverse_paired.fastq.gz SS1577_reverse_upaired.fastq.gz ILLUMINACLIP:../reference/V4_primers.fasta:2:30:10 LEADING:3 TRAILING:3 SLIDINGWINDOW:4:15 MINLEN:36`
