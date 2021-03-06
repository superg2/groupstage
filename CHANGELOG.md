0.7.0 / 2013-12-23
==================
  * Updated `tournament` to 0.21.0 so that `GroupStage` is an `EventEmitter`

0.6.3 / 2013-12-11
==================
  * documentation mistakes fixed

0.6.2 / 2013-11-24
==================
  * allow 2 player groupstages (needed for grouped tiebreakers)

0.6.1 / 2013-11-13
==================
  * fix broken release (0.6.0 fails to install)

0.6.0 / 2013-11-13
==================
  * We no longer break up positions between groups - 1st placers are always tied 1st out of this module (only TieBreakers can break between groups)
  * Interface with tournament@0.20.2 for cleaner results implementation

0.5.1 / 2013-11-06
==================
  * Interface with tournament@0.20.0 for cleaner results implementation

0.5.0 / 2013-11-02
==================
  * tiebreaker factored into its own module and fundamentally changed therein
  * Interface with tournament@0.19.0 for multi stage support

0.4.0 / 2013-10-31
==================
  * Use tournament@0.18.0 interface
  * GroupStage sorting now takes into account score losses (`.against`)
  * TieBreaker positions are now demoted before it is done
  * Many other TieBreaker results improvements
  * Constructor changes, now groupSize is a key in options
  * Default `groupSize` now initialized to `numPlayers` so basic use is a league
  * NB: TieBreaker will still change massively - its tests still fail

0.3.0 / 2013-10-25
==================
  * Using tournament@0.17.0 for better stats interface
  * Replace `maps` with `for` and add `against` in results for cross tournament consistency
  * Huge code readability improvements

0.2.0 / 2013-10-22
==================
  * Use tournament@0.16.0 interface
  * Allow home and away matches (for double length) for `GroupStage` - for #1

0.1.1 / 2013-10-16
==================
  * refactor `score` to use Base implementation

0.1.0 / 2013-10-15
==================
  * first release - factored out of tournament 0.14.0
