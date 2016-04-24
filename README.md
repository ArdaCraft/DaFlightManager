DaFlightManager [![Build Status](https://travis-ci.org/DaFlight/DaFlightManager.svg?branch=master)](https://travis-ci.org/DaFlight/DaFlightManager) [![latest](https://img.shields.io/badge/releases-latest-blue.svg)](https://github.com/DaFlight/DaFlightManager/releases/latest "Grab the Latest Build") 
===============
Server-side management of DaFlight users for SpongeAPI and Bukkit

### Default Config
```yml
flySpeeds:
  moderator: 15.0
  member: 5.0
  guest: 1.0
  operator: 100.0
sprintSpeeds:
  member: 5.0
  guest: 1.0
  operator: 100.0
  moderator: 15.0
```
Speed names can be added/removed/renamed (but don't rename or delete 'flySpeeds or 'sprintSpeeds')

### Permissions
- `daflight.fly.<speed_name>` - set the user's maximum fly speed  
- `daflight.sprint.<speed_name>` -  set the user's maximum sprint speed  

Where '`<speed_name>`' is replaced by the config name of the desired speed.  
For example `daflight.fly.member` would set a maximum fly speed of `5.0` for a user (using the above config).
