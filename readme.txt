----------------------------------------------------------------------------------
ddHUP+ 
----------------------------------------------------------------------------------
	Mining High Utility Itemsets in One Phase without Generating Candidates 

	Junqiang Liu ( jjliu @ alumni.sfu.ca )
	Ke Wang ( wangk @ sfu.ca )
	Benjamin C.M. Fung ( ben.fung @ mcgill.ca )	

----------------------------------------------------------------------------------
Citation Policy:
----------------------------------------------------------------------------------
If you publish material based on our algorithm, then, in your references, please cite one of the following:

[1] Junqiang Liu, Ke Wang, Benjamin Fung. Mining high utility patterns in one phase without generating candidates. IEEE Transactions on Knowledge and Data Engineering(TKDE), vol. 28, no. 5, pp. 1245-1257, May 2016. 

[2] Junqiang Liu, Ke Wang, Benjamin Fung. Direct discovery of high utility itemsets without candidate generation. Proceedings of the 12th IEEE International Conference on Data Mining (ICDM), Brussels, Belgium, December 10 - 13, 2012. 

----------------------------------------------------------------------------------
Help 
----------------------------------------------------------------------------------

1. Three executables were compiled for Windows, Linux (Ubuntu), and Cygwin (2.738), respectively. 

2. To run the example or the experiments, simply get to the respective directory and run "demo.bat" with the Windows executable.

3. The six datasets used in the experiments, the running example, and the executable are archived by 6 files. 
	Chainstore.zip
	Chess.zip
	Foodmart.zip
	T10.zip
	T20.zip
	WV1.zip
   Moreover, a toy dataset used in the published paper together with the demo.bat is also attached to this distribution. 

Note:
The files Chainstore.zip and T10.zip and T20.zip may only contain the executable and batch files. 
If this is the case, please visit "http://cucis.ece.northwestern.edu/projects/DMS/MineBench.html" 
and download "NU-MineBench-2.0.data3.tar.gz" to extract the files, 
namely "data.ntrans_1000.tlen_10.nitems_1.patlen_6", "logn1000_binary", "product_price_binary", and "real_data_aa_binary".


4. The format of each dataset is in accordance with that in the experiments in the following paper. 
Y. Liu, W. Liao, and A. Choudhary. A fast high utility itemsets mining algorithm. 
In Proc. of the Utility-Based Data Mining Workshop in conjunction with the 11th ACM SIGKDD, 2005.

In other words, each dataset consists of two binary files, the transaction file and the price file.
1) The transaction (binary) file is of the following format where every entry is a long integer: 
the number of transactions
the number of distinct items
an additional number
Tranaction-id length-of-transaction item-1 quantity-1 item-2 quantity-2  ...  
...
Tranaction-id length-of-transaction item-1 quantity-1 item-2 quantity-2  ... 

2) The price binary file is of the following format where every entry is a float number:
price-of-item-1 
price-of-item-2
...
price-of-item-n

Note: 
Items are represented by an integer starting from 0, that is, 0 is item-1.

--------------------------------------------------------------------
Thank you very much for using our algorithm. 

Junqiang Jimmy Liu





