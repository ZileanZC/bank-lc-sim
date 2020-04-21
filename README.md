# An Optimal Investment Strategy of Lending Club
Sponsor:
* `Alan King`

Main Contributors:
* `Zihan Chen`
* `Chenyi Yang` 
* `Jie Qian` (https://github.com/jieqian2/bank-lc-sim)
* `Yulong Wang` (https://github.com/wyyyl/bank-lc-sim)

Cooperators:
* `Heze Liu`
* `Jiaqi Su`

Remarks: This is a new version of bank simulation regarding Lending Club dataset. The previous version is developed by our sponsor Alan King from IBM, refer to https://github.com/IBM/bank-lc-sim

## bank-lc-sim
A simulator for a simple bank using the LendingClub public loan data set

### data
Download the LendingClub data file `loan.csv` from the kaggle site https://www.kaggle.com/wendykan/lending-club-loan-data into the `./data/` directory (it is too large for git).

Download the processed dataset file `data_df_backup.csv` from Google Drive https://drive.google.com/file/d/1t6qkXfVN7j3cWmLMvlkJYTPtHAy0snQd/view?usp=sharing into the `./data/` directory (it is a encoded dataset for neural network).

### play
Use the notebooks in `./notebooks/` to prepare the data, build the classifier, and simulate the bank.
