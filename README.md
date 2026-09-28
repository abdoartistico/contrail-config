# contrail-config

Remote config for the Contrail Android app, read once at launch.

```json
{
  "adsb_lol_base": "",
  "adsb_fi_base": ""
}
```

Empty values mean "use the public ADS-B endpoints". Set a base URL here (for example your own caching server) and every installed app picks it up on its next launch — no app update needed.
