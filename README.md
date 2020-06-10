# Runoff
Complete the vote function.  The function takes arguments voter, rank, and name. If name is a match for the name of a valid candidate, then you should update the global preferences array to indicate that the voter voter has that candidate as their rank preference (where 0 is the first preference, 1 is the second preference, etc.). If the preference is successfully recorded, the function should return true; the function should return false otherwise (if, for instance, name is not the name of one of the candidates). You may assume that no two candidates will have the same name.

Recall that candidate_count stores the number of candidates in the election.
Recall that you can use strcmp to compare two strings.
Recall that preferences[i][j] stores the index of the candidate who is the jth ranked preference for the ith voter.

# Testing

An election with any number of candidate (up to the MAX of 9)

Voting for a candidate by name

Invalid votes for candidates who are not on the ballot

Printing the winner of the election if there is only one

Not eliminating anyone in the case of a tie between all remaining candidates
