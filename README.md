# Puerto Rico's Municipal Elections, 1976-2020

This respository includes several CSV files on with the results of Puerto Rico's municipal elections. 

Most of the data was collected from Puerto Rico's [Comisión Estatal de Elecciones](https://www.ceepur.org). I also used data from Manuel Alvarez Rivera's website - [Elecciones in Puerto Rico](https://electionspuertorico.org/home_es.html) to ascertain the gender of the winning mayors.

Here is a list of the CSV files with a short description found in this repository.

| File Name | Description |
| ----------- | ----------- |
| tidy_municipalities_elections_pr_data.csv | This CSV includes the results of Puerto Rico's municipal elections for mayors from 1976 to 2020. There are missing data from 1976 to 1988. From 1992 to 2020, the dataset includes the name of the winning candidate and the gender of the candidate. It includes vote tallies for major and fringe political parties as well as votes for independent and writing-in candidates.|
| municipal_elec_pr_mayors_party_year.csv| This CSV includes the winning party for municipal elections for Puerto Rico's 78 mayors from 1976-2020.|
|elec_mayors_pr_index_1976_2020.csv| This CSV is part of a project indexing the influence of Puerto Rico's main political parties at the municipal level. If the PNP candidate won the mayoral election, the win is represented as a 1. If the PPD candidate won the race, the victory is presented as -1. Thus, overtime we can calculate whether a municipality has been more closely aligned with the PNP or PPD. Thus, scores closer to 1 means that the municipality has aligned the PNP, while scores closer to -1 show that the municipality is aligned with the PPD.|


These CSV share the same variable. Here are a list and a short description of the variables used in the first file.

- year: This represents the year of the election.
- municipality: The name of Puerto Rico's 78 municipalities.
- party_win: The political party that won the mayorship. 
- name_winner: The name of the candidate that won the election.
- winner_gender: The gender of the winning candidate. Two possible answers: male or female.
- ppd_votes: Vote tally for the pro-Commonwealth, Partido Popular Democratico (PPD).
- ppd_per: Percent of the PPD's vote.
- pnp_votes: Vote tally for the pro-statehood, Partido Nuevo Progresista (PNP).
- pnp_per: Percent of the PNP's vote.
- pip_votes: Vote tally for the pro-independence, Partido Independentista Puertorriqueno (PIP).
- pip_per: Percent of the PIP's vote.
- mvc_votes: Vote tally for the Moviemiento de Victoria Cuidadana (MVC).
- mvc_per: Percent of the MVC's vote.
- pd_votes: Vote tally for the Partido Dignidad (PD).
- pd_per: Percent of the PD's vote.
- psp_votes: Vote tally for the Partido Socialista Puertorriqueno (PSP).
- psp_per: Percent of the PSP's vote.
- indies_vote: Tally of the vote for the independent candidate.
- indies_per: Percent of the vote for the independent candidate.
- ppt_votes: Tally of the vote for the Partido del Pueblo Trabajador (PPT).
- ppt_per: Percent of the PPT's vote.
- mus_votes: Tally of the vote for the Movimiento Union Soberanista (MUS).
- mus_per: Percent of the MUS's vote.
- local_votes: Vote tally for the local candidate (*This is a a designation that appears in the results tabulated by the Puerto Rico's Comision Estatal de Elecciones*).
- local_per: Percent of the vote for the local candidate.
- total: A tally of all casted votes (*Note that adding all the previous variable may no equal this total. This dataset does not include the number of spoiled or blank ballots*).



