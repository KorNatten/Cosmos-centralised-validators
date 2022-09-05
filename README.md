# Cosmos-centralised-validators
A list of centralised validators and exchange accounts on the Cosmos Hub

**Problem**
- The [validators.json](https://github.com/gnolang/independence-day/blob/main/consolidate/validators.json) file is based on the snapshot height 10562840.
While prop69 was running on different dates/heights.
- There was no info on the validators, votes, (in)active, CEX or other remarks.
**First steps to possible solution**
- I put the [validators.json](https://github.com/gnolang/independence-day/blob/main/consolidate/validators.json) file into a spreadsheet.
- I checked manually on their votes on mintscan, which lead to some different obstacles
  * There were 387 validators in the file on height 10562840
  * Some monikers were not the same anymore
  * There were duplicates in monikers
  * Mintscan only shows the 175 active validators and their votes today.

I added a separate column (prop_69_vote) in the spreadsheet with their votes. I followed the same values as used in [Prop69 Snapshot](https://github.com/gnolang/independence-day/tree/main/prop69#readme)
```
  VOTE_OPTION_ABSTAIN
  VOTE_OPTION_YES
  VOTE_OPTION_NO_WITH_VETO
  VOTE_OPTION_NO
```
I added an option for validators that did not vote on prop69
````
nil
````
