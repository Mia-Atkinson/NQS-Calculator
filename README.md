Results:
https://docs.google.com/spreadsheets/d/1LbbfnVvjJ50y4yA-I0_dGwCCr2Bz0jIs_i_tt0RcO8Q/edit?usp=sharing

Setup:
  - Install Python 3
  - Run pip install pandas
  - Input file: prospect_rtn_data.csv stored at the root of the project

Notes:
  - Rank is not calculated, so if a team or athlete has the same NQS for any event, they will both be listed with that score, but the output may not order them the same way that RTN does.
  - Input data does not have a way to calculate neutral deductions.

  For example, LIU had an away meet on February 20th where the score should have been 194.1 based on the athlete scores (and also shown on the LIU Athletics website), however they received a 0.1 neutral deduction, so the correct score (shown on roadtonationals.com) is 194.0. Because this meet was used to calculate their NQS, the calculated NQS is slightly off from the RTN NQS.
