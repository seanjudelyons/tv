# tv

- `tv.m3u` (and identical `tv.m3u8`) — the household channel list, served at https://seanjudelyons.github.io/tv/tv.m3u.
  Used by TiviMate on the Android box and by the Samsung TV app. Guide: see the `url-tvg` header.
- `app/index.html` + `package.json` — "My TV", a TiviMate-style live TV app for Samsung (Tizen) TVs, loaded by
  [TizenBrew](https://github.com/reisxd/TizenBrew) as module `gh/seanjudelyons/tv`. After changing it, purge jsDelivr:
  `curl https://purge.jsdelivr.net/gh/seanjudelyons/tv/app/index.html`.

Guide data and Pluto links come from [seanjudelyons/tv-guide](https://github.com/seanjudelyons/tv-guide).
