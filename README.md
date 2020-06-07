# HLTVApi
Unofficial HLTV API
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
	GetStats(int id);
	GetRanking(int id);

# Note: You can be banned due to many requests to HLTV.
