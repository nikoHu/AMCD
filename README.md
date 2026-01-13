# Source code is available:
https://github.com/nikoHu/AMCloneDetector

# AMCD
AMCD is a code clone detection tool used for recognizing code clones in software repositories.

# application.properties
compare-type=1  #Based on different types of comparisons  1=string 2-simhash 3-token  
similarity=0.7  #Similarity threshold  
min-line=5      #The minimum number of lines of the method  
language=java  
extensions=java  
mlc=50  
thread-num=1    #Number of threads  
buffer=100000  

# How to use
java -jar AMCloneDetector.jar your-file
