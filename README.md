# zones-cstrike
work-in-progress standardized zones for bhoptimer (for Counter-Strike: Source)

Pull-requests are welcome.

[home page](https://github.com/srcwr/zones-cstrike)

[github pages page](https://srcwr.github.io/zones-cstrike/)

## To use
in `cfg/plugin.shavit-zones.cfg`
```
shavit_zones_usesql "0"
```
in `cfg/plugin.shavit-zones-http.cfg`
```
shavit_zones_http_url "http://zones-{engine}.srcwr.com/x/{map}.json"
// Or you could use the github pages direct url 
shavit_zones_http_url "https://srcwr.github.io/zones-{engine}/x/{map}.json"
```

## other stuff
the initial zone dump originates from the btimes zones table from Solitude, courtesy of Eric ([Github]( https://github.com/ecsr) / [Steam](https://steamcommunity.com/id/-eric))

the cutehops zone dump originates from cutehops (obviously), courtesy of may/lilac ([Github](https://github.com/lilac1337) / [Steam](https://steamcommunity.com/profiles/76561198955846348))
