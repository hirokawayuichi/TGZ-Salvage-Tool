Salvage tool for corrupted GZIP(.tgz/.tar.gz/.gz) file. 

This software is provided "AS IS". 
Please use at YOUR OWN RISK. 

Prerequisites: Python ver.3, Gunzip, GNU TAR

Usage: execute the following command in terminal

       python gzs.py -i filename [-s] [-k]

       -i filename: filename of corrupted tgz
       
       -s         : Only split corrupted tgz file to temporary salvaged files. 
       
       -k         : Keep temporary salvaged files
