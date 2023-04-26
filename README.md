<h1 align="center">NawaabFetch</h1>

#
NawaabFetch is a modification of the IPCP Prefetcher[[1]](#references) specialized for graph applications, built on top of the ChampSim simulator[[2]](#references), for the CS230 course project at IIT Bombay. <br>
Refer to this presentation[] and the video[] for a detailed understanding of our project.

### Code Files
Changes have been made to the following code files:
- `ipcp.l1d_pref` : This file has all the changes that have been made to original implementation of the data prefetcher at L1 level.   
- `ipcp.l2c_pref` : Has the implementation of CPLX class added on to the original imlementation at the L2 level.   

### Traces used
The following traces have been used for the project after evaluating the performance of IPCP over all the traces[[3]](#references):
- `pr-10.trace.gz`
- `pr-14.trace.gz`
- `pr-3.trace.gz`
- `pr-5.trace.gz`

### Final Results
- We got an overall 25.1% increase in speedup on average as compared to IPCP, for the traces used.
- Also, we get an overall prefetch accuracy of 28.3% vs the 1.80% accuracy as shown by the initial implementation, which is a significant improvement! 

### Team Members
Akshat Singh (210020013) <br>
Yash Ruhatiya (210050169) <br>
Yashwanth Reddy Challa (210050171) <br>

### References
1.  S. Pakalapati and B. Panda, "Bouquet of Instruction Pointers: Instruction Pointer Classifier-based Spatial Hardware Prefetching", https://www.cse.iitk.ac.in/users/biswap/IPCP_ISCA20.pdf 
2. "ChampSim", https://github.com/ChampSim/ChampSim
3. Traces, https://utexas.app.box.com/s/2k54kp8zvrqdfaa8cdhfquvcxwh7yn85/folder/132804598561 