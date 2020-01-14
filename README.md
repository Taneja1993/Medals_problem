# Medals_problem
#In this medals problem, basically we want to aggregate/manipulate the 'summer' dataframe to have 0 divergence and score with the official
#medal data tables of year 1976 and 1996, which are supposed to be correct(wik_1976 and wik_1996 data tables).

#Some of the assumtions which are available from the sports experts, to solve this problem are as follows:
#To identify all the unique events, Event Gender matters, there are men, women and mixed events. So, to identify the mixed events,
#Following conditions are to be considered:
#The Events marked with "mixed" or "pairs"
#The "Equestrian" sports
#The "sailing" sport before year "1988" were all mixed events.
#And index labels with the numbers : 21773, 21782, 21776, 21785, 21770, 21779, 23703, 23712, 23706, 23715, 23709, 23700,25720, 25729,
#25723, 25732, 25726, 25717, 27727, 27736, 27730, 27739, 27724, 27733,29784, 29785, 29786, 29787, 29788, 29789 are awarded to mixed
#Badmintopn Events.

#And it's also important to identify the team events and singular events, so in this problem, events with 5 or less medals are deemed to be
#SINGLE events and more than 5 are deemed to be TEAM events. For e.g. if a team has won 12 medals for basketball event, that must be counted
#as 1 only instead of 12, so in such kind of case 11 medals are redundant and needs to be dropped.
