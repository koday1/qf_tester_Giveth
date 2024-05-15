Forked for Giveth on May 14 2024. This repo will be used to adjust, implement, and experiment with COCM and other QF-related mechanisms for QF rounds at Giveth.

COCM announcement post: https://forum.giveth.io/t/cluster-match-qf-announcement/1419

Questions? Comments? Engage with us on the forum!

-------------------------------------------------------
## QF TESTER
This codebase is designed to implement various Quadratic Funding (QF) algorithms. It includes functions for data preparation, calculation of matching funds, and testing of different QF strategies.

## Key Files
- fundingutils.py: Contains utility functions for data preparation and QF calculations.
- qf_tester.py: Contains functions to run QF calculations on a given dataset and save the results.

## Usage
- If you run 'python qf_tester.py' in the terminal, the code will run a QF calculation on the sample dataset provided. The results will be saved in a new file. 
- You can also import the functions from qf_tester.py and use them in your own code.
- You can use any votes file as long as it has the following columns: 
  - voter
  - amountUSD
  - payoutAddress
  - project_name
  - score
