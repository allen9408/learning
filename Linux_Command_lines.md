#Linux Shell Commands

**Count command lines in a folder:**  
    find ./ -name "*.c" |xargs cat|wc -l  

**Output file size and sort:**  
    ls -s | sort -n(r: reverse)  

**find string in files**  
    grep -R(include sub directory) -i "make" ./*  
    

