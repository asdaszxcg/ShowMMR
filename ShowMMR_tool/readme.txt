
  ShowMMR tool by AveYo - adapted from SteamKit2 Samples at github.com/SteamRE/SteamKit
  -------------------------------------------------------------------------------------

  To compile:
  - install dotnet 7.0 or 6.0
  - use dotnet_build_net7.0.bat or dotnet_build_net6.0.bat

  To run:
  - use run.bat to launch ShowMMR from bin/release/netxxx
  outputs user_keys_[steamid]_slot3.vcfg with 200 recent matches by default
  can provide command line arguments for more matches: run.bat steamuser steampass 360
  can press enter after the tool runs to also install the vcfg, or do it manually:
  - open Steam > Library > Dota2 > right-click Properties > Installed files > Browse..
  - replace game/dota/cfg/user_keys_[steamid]_slot3.vcfg with the generated file

  ShowMMR DOTA dashboard mod keeps a local history of up to 640 matches, then overrides oldest entries
  So there is no need to run this optional tool frequently - likely once every couple months is enough
  Can even not run it at all if you are not interested in mmr numbers from before installing the mod

