Programming Assignment 2- Information Retrieval (CS F469)
2019H1030026G


Important Note:
--------------------
1)Simply open the IRa2.ipynp file using jupyter notebook(Anaconda Navigator) and start executing sequentially, all the necessary instructions are given  in the IRa2.ipynb file.
2)Remainder : Create two folders named (corpnew and corporiginal) , initially (corpnew is empty , corporiginal has 6377 documents(whole corpora))
3)Remainder : a1results.txt file holds the results of assignment 1
4)Remainder : Kindly provide the path to the variables, it is necessary for proper execution of the code
	*corpus_root   //path of corporiginal folder with 6377 documents //before task1
	*source           //path of corporiginal folder with 6377 documents //before task1
	*dest	      //path of corpnew folder which is initiall empty //before task1
	*a1path	     //path of a1results.txt file //in task1
	cd "path to corpnew folder"  //change 

Other Information:
-----------------------
1)In the execution of task 4, each clustering algorithm takes approximately '50min' for testing k value from
   (k=1 to 50) over a corpora of size 1000+ documents.//k=number of clusters
2)Six algorithms combinely take around 5 hours of execution time
3)K- means algorithm , would give different outputs for same k value on different executions, to eliminate this randomness
random_state varaible was fixed to a constant
4)K- means cosine similarity was implemented completely, instead of sending normalized vectors to kmeans euclidean of sklearn
 
