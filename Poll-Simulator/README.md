# Poll Simulator

Exercise:

Suppose there is election for Present, SBG (Student Body Governance) at your institute. Let
following be in the scope of this work:
• There are number of student candidates nominates themselves for fighting election
for the position of Present, SBG.
• Students are voters; each student votes for the post.
• Let the system record IDs of all students who vote so that we can detect repeat voting
by same student; however we do not record who votes whom.
• We do not use any database for recording proceedings of polling; let us use some in
memory data objects for storing the same.
• Let web browser be only client for accessing the application.
• We would want to allow polling to be performed from multiple web clients (i.e.
browsers from different machines)

Objective : multi-tier application architecture.

Solution:

home page has all the options available for poll simulator 
1) Add Candidate:- inputs name of candidate and will display the names of eligible candidates for voting after submitting the name.
2) Vote:- inputs valid student id for once and ask to vote for a candidate by choosing one of the radio button and counts for the vote.
3) Poll result:- counts the winner votes and lost by votes.
4) Voting summary:- total votes of each candidate.




