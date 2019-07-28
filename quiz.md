# Quiz: Command Line for Data Science

Follow the code in **Practice 1** to create a file named `temporary.csv`.

1. Use `head -1 temporary.csv`, what is the returned result?
    - [ ] The `columns` in a comma-separated format
    - [ ] One row of observation with the receipt id `9622257`
    - [ ] One row of observation with the receipt id `9643416`
    
Extending on what you learn from the **`grep` for regex matching** section, supposed we want to find all transactions where the value for `yearmonth` is anything but `2018-07`. Refer to the code in **Practice 2** and print the lines (observations) that do not end with the string `2018-07` using inverse matching, the `-v` flag. 

2. How many lines in `rice.csv` do not end with the string `2018-07` not including the header line (column)?
    - [ ] None
    - [ ] More than 4 
    - [ ] 1
    - [ ] 2
    + 2 points
   
Refer to the code in **Practice 3**. As a quick refresher:
    - `grep -v "^#"` matches and returns all lines that do not start with a `#` character through inverse matching  
    - `sed 1d` or `sed '1d'` removes the first line through **s**tream **ed**iting 
    - `wc -l` uses the wordcount utility to count the number of lines

3. Count the number of lines in `rice.csv` **excluding** the header line (first line) and comments (any line that starts with a `#` symbol). How many lines are there?
    - [ ] 36
    - [ ] 46
    - [ ] 35
    - [ ] 45
    + 2 points
