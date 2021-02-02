# ACM Research Coding Challenge (Spring 2021)

There are two circular genome maps in the repository. 

The first genome map was built using the CGView library, which is implemented in the CGView Server hosted by the Standford Research Group. 
Link to CGView server: http://cgview.ca/
Further information can be found about CGView here: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2447734/

The second genome map was built using the GView library. 
Further information about the same can be found here: https://github.com/phac-nml/gview-wiki/wiki

However, both of these libraries were already implemented (CGView through a web server, GView through a simple GUI). 
I looked for ways to implement these libraries myself but could not find sufficient documentation about it's implementation. 

Then, I did some more research and looked into the resources mentioned in these forums: 
http://seqanswers.com/forums/showthread.php?t=16807
https://www.biostars.org/p/67015/

My research showed me that Circos is the industry-standard for this use-case. So, I tried implementing that. 
Information about Circos can be found here: http://circos.ca/
However, you need PERL to run Circos. My experience with PERL is at the beginner's level. But, I tried implementing Circos for our use-case by following their official tutorial (http://circos.ca/documentation/tutorials/)
But, I was facing many errors due to gaps in knowledge and lack of time. 
Thus, my approach to solve this problem will be to learn PERL first and implement Circos to create a circular genome map. 


