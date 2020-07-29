# HLTVApi
Unofficial HLTV API on C#

# Install

Download bin folder and add reference on dll file in your project

# Description

You can get information about events, matches, players and teams. One request may take some time, it's caused by delay to prevent ban.

# Event:

Get();
Get(int id);
GetStats(int id);

# Match:

Get();
Get(int id);
GetStats(int id);

# Player:

Get();
Get(int id);
GetByName(string name);
GetStats(int id, string startDate, string endDate, string matchFilter, string rankingFiler, string mapFilter);
GetStats(int id);
GetPlayerRanking(int id, string startDate, string endDate, string matchFilter, string rankingFiler, string mapFilter);
GetPlayerRanking(int id);
# Team:

Get(int id);
Get(int id, string teamLink);
GetStats(int id);
GetRanking(int id);

# Note: You can be banned due to many requests to HLTV.
