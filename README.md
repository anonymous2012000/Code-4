# Pseudorandom Function 
Dependencies:

* GMP: https://gmplib.org/

* Cryptopp: https://www.cryptopp.com

Running a test: 
* Clone the repository (i.e., Code-4-main).
* Install the libraries and unzip the downloaded file, Code-4-main.zip. 
* Run the following command lines in order:

        g++  -c Rand.cpp  -lgmpxx -lgmp -std=c++11 -lcryptopp

        g++  Rand.o  main.cpp  -o main -lgmpxx -lgmp -std=c++11 -lcryptopp
        
        ./test


