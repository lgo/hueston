# hueston
Hueston to Ground Control - Philips Hue Control Center developed in Flask.

###


### Functionality

- Per user rooms and bulbs, with management via. a web dashboard.
- Scripting in order to control
  - querying current bulb status
  - device locations, last activity, etc. (hueston-mobile, hueston-native client repositories)
- Service jobs for all scripting and API calls and in addition to run timed operations
- Ability to deploy to Heroku, without the need for a second dyno for just jobs (instead run services synchronously).


### Scripting use cases
If the room bulbs are on, and the last used device among a phone and laptop was 30 minutes ago, turn off the lights. If instead you want to do an activity such as reading, there will be a "lock" mode for locking any script activities until the lock is released or expires.

