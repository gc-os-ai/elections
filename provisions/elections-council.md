### DRAFT provisions for GC.OS board elections

NOTE: the below are draft provisions for continuous board elections.

The 2024 elections are subject to special provisions, and the elected board
will finalize the election provisions.


1. Timelines 

    i. Elections to the board occur annually, in December.

    ii. The voting period spans two weeks.

    iii. Prospective candidates are required to complete their registration within a window of at least two weeks and no more than four weeks prior to the commencement of the voting period. Additionally, they must submit a comprehensive candidate statement along with their registration.

    iv. Individuals intending to vote must register within a timeframe of at least two weeks and no more than eight weeks before the voting period starts.

    v. The announcement of voting results should take place no later than two weeks after the conclusion of the voting period. In cases of unexpected delays or procedural discrepancies, timely communication regarding such matters must be conveyed to both the voters and candidates.


2. Term Structure and Re-election

    i. The board operates with three shifted cohorts of seats, cohort A, B, and C

    ii. To maintain this structure, seats in each of the cohorts open for re-election every three years, cohort B in the year after cohort A, and cohort C in the year after cohort B, and so on.

3.  Votes and Determination of End 

    i. A vote constitutes an ordered preference list of all eligible candidates who have registered for the election. Votes of the boardors (at vote opening) and the general electorate, excluding the boardors, are counted separately. 

    ii. half of the seats of a year's cohort (rounded up/down alternatingly) is determined based on votes of the general electorate excluding board; the other half is determined based on votes of the board (at vote opening). First the board preference seats are filled; then the general electorate preference seats.

    iii. The determination of the end result involves a multi-step process. For each step: first, all candates filtered out by the exclusion rules (see there) are eliminated. Then, all first-choice votes are tallied for the candidates competing for a given seat. If a candidate receives an absolute majority at this stage, that candidate claims a seat. If not, the candidate with the fewest first-choice votes is eliminated, and their votes are redistributed to the remaining candidates based on the next preference marked on each ballot. This iterative process continues until candidates secure an absolute majority for the available seats.

    iv. Once a candidate claims a seat, they are removed from all further counts for the end result. The procedure in iii is carried out first for the boardor votes, then the general electorate votes.

    v. a well-annotated piece of python code determining the end result, given digitized votes, should be publicly available at all times. This code should be used to tally the votes and determine the end result.


4. voting

    i. Each eligible voter is entitled to cast one vote by indicating their ordered preference of candidates on the ballot.

    ii. The voting process should be designed to ensure anonymity, and mechanisms must be in place to safeguard the confidentiality of each voter's choices.

    iii. the precise voting procedures must be communicated to all voters no later than two weeks before the vote, and deposited in a publicly visible location.

5. Audit

    i. In the interest of transparency and fairness, observers are to be appointed to audit the voting process.

    ii. The observers should include at least two representatives chosen by the arbitration committee.

    iii. together with voter registration, voters from the general electorate may volunteer as observers. If there is at least one such volunteer, then at least one or two observers should be selected by a fair lot from among the volunteers.


#### eligibility to vote

Formal requirements

    i. voter registration in time

    ii. members of the GC.OS organisation

    iii. individual 

    iv. not subject to an active full ban or relevant code of conduct sanction at the voter registration cutoff

There is no contribution requirement for eligibility, as members are already assumed to contribute (at least registration details or membership fees)

#### eligibility to be elected

1. Formal requirements

    i. candidates must be eligible to vote

    ii. candidates must have registered in time

    iii. candidates must have submitted a candidate statement with their registration

    iv. candidates must have truthfully declared their primary affiliations and conflicts of interest in their candidate statement

2. Exclusion rules

    i. these exclusion rules are used in the iterative procedure for determining the end result of the vote, and count at the point a candidate could fill a seat.

    ii. a candidate of a primary affiliation that is already present on the board or has filled a seat cannot be elected. The same holds for a primary affiliation that is the same up to significant individual or institutional dependency relation such as >50% owned subsidiaries, or a substantial conflict of interest relationship.

    iii. after 6 years of continuous tenure, a candidate can claim a seat only with 2/3 or more of cast votes, at any point of the iterative procedure

    iv. at least 1/3 of the seats must be filled by candidates eligible through code contributions; at least 1/3 of the seats must be filled by candidates eligible through community contributions. If a seat assignment would make this impossible, the candidate cannot take the seat. If there is no possible seat assignment satisfying the above to start with, the 1/3 should be replaced by the largest possible fraction smaller than 1/3.

    v. upon any formal complaint by candidates, the arbitration committee determines interpretation of the exclusion rules. Such interpretations must be consistent with precedent.


3. Contribution requirement:

candidates must have made substantial code or community contributions in the 18 months leading up to the election period, as defined in the [contribution requirements document](https://github.com/GC.OS/elections/blob/main/contributions.md).
