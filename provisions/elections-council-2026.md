# Provisions for GC.OS steering council elections 2026

## Seats and voting algorithm

### Roles

The elections are for seats on the steering council.

### Seats and tenure

* the 2026 GC.OS board elections are for all seven board seats
* three seats are elected by the current board
* four seats are elected by the general electorate (contributors)

There are three shifted cohorts, cohort A, B, C.
Ultimately these cohorts are planned for 3 years tenure.

As these are the first sktime elections, some cohorts have shorted tenure to enable future shifting.

Seats are filled in this order:

1. cohort C, 3 years tenure, by current board
2. cohort C, 3 years tenure, by general electorate
3. cohort B, 2 years tenure, by current board
4. cohort B, 2 years tenure, by general electorate
5. cohort B, 2 years tenure, by general electorate
6. cohort A, 1 year tenure, by current board
7. cohort A, 1 year tenure, by general electorate

### Vote tallying algorithm

Each voter from the general electorate fills in four polls:

* selecting top preference from all candidates
* selecting top 2 preferences from all candidates
* selecting top 3 preferences from all candidates
* selecting top 4 preferences from all candidates

Each voter from the current board fills in three polls:

* selecting top preference from all candidates
* selecting top 2 preferences from all candidates
* selecting top 3 preferences from all candidates

Votes are tallied as follows:

Proceed with the seats ordered as above, 1-7.

1. consider the the open seat with lowest number.
  Let n be its order rank to be filled,
  by the group determining the seat (board or general electorate),
  this will be an integer, between 1 and 4.
  Find the candidate with most mentions in the "top n preferences" vote of that group.
2. check exclusion criteria for the candidate. If not met, seat the candidate.
  Eliminate the candidate from further seatings, in any case.
3. Goto 1 until no more seats or candidates remain.

Proceed with the four general electorate seats, using the same algorithm.

### Exclusion rules

* a candidate of a primary affiliation that is already present on the board or has filled a seat cannot be elected. The same holds for a primary affiliation that is the same up to significant individual or institutional dependency relation such as >50% owned subsidiaries, or a substantial conflict of interest relationship.

* at least 1/3 of the seats must be filled by candidates eligible through code contributions; at least 1/3 of the seats must be filled by candidates eligible through community contributions. If a seat assignment would make this impossible, the candidate cannot take the seat. If there is no possible seat assignment satisfying the above to start with, the 1/3 should be replaced by the largest possible fraction smaller than 1/3.

## Eligibility

### Eligibility to vote

1. voter registration completed in time - [voter registration form](https://forms.office.com/e/sDSDtnewga)
2. contributor with any contribution registered in `allcontributor-src` (only projects with such a mechanism)
3. not subject to an active full ban or relevant code of conduct sanction at the voter registration cutoff


### Eligibility to be elected

1. candidates must be eligible to vote
2. contributor with at least a "substantial" code or community contribution as defined
  in the [contribution requirements document](https://github.com/gc-os-ai/elections/blob/main/provisions/contributions.md),
  within the 18 calendar months prior to the election date
3. candidates must have registered in time
4. candidates must have submitted a candidate statement with their registration, intended for publication
5. candidates must have truthfully declared their full name, primary affiliations, and any conflicts of interest in their candidate statement

## Arbitration and administration of the election process

The 2026 voting process is implemented and overseen by the current code of conduct committee
(chair: Dr Franz Kiraly), carrying out functions of an elections committee and arbitration committee.

The current GC.OS board recognizes: the experimental nature of the widened governance model;
the transitionality of the current setup; and the potentially
adverserial nature of an open source ecosystem under increasing competitive pressure.

The board is committed to ensure a peaceful and efficient transition to the
more professional governance model, and to protect the guiding vision
behind the elections, that of openly goverend open source AI software that benefits all.

For this reason, the elections committee and the current board reserve
their rights to make amendments to the provisions
in the present transitional situation, when (and, strictly, only when) necessary
in order to ensure the vision is protected and realized, e.g.,
for the purposes of security, minimizing interference, or ensuring process robustness.
