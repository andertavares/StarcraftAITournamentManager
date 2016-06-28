# StarcraftAITournamentManager
Tournament Manager Software for StarCraft AI Competitions

Instructions: http://webdocs.cs.ualberta.ca/~cdavid/starcraftaicomp/tm.shtml

Tutorial video: https://www.youtube.com/watch?v=tl-nansNbsA

## Persistent knowledge disabled

This fork of the Tournament Manager has the option to disable persistent knowledge from a round to the next. With persistent knowledge disabled, files in bwapi-data/write are not moved to bwapi-data/read.

To disable persistent knowledge, set `AllowRead` option to `no` in `server_settings.ini`.
