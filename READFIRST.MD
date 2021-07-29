As discussed in the notebook and the PDF report I struggled with some data loading/parsing problems. I discussed this with Marcos and he said to use the largest data that would work.

The file <code>ST446-201301.ipynb</code> is what the paper was based upon but the function <code>bucket_black_gr</code> and <code>bucket_white_gr</code> use the collect function 4 times and so as
data size increase these get very slow. I created a similar function in <code>ST446-Project.ipynb</code> but it does not use the min and max of the ratings as the boundaries, but 
arbitrary values. This leads to the graphs being slightly different than in the final report, but the code is considerably quicker than the <code>collect()</code> method.
Moving these boundaries though changes the numerical results so would have required a late stage rewrite of a lot of the paper. The conclusions would have been the same though. The cheaters
we found are considerable outliers compared to their peers so would have been caught either way, only the magnitude of their cheatiing changes, not the order of who was cheating.
