^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package interactive_behavior_201409
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.1 (2015-06-11)
------------------
* [interactive_behavior_201409] add /people to look-at source
* [interactive_behavior_201409] utilize look-at related funcs to pr2-behavior-utils.l
* [jsk_demos] remove rosmake files
* Add small launch file to run interactive_behavior on pr2
* Fix typo :heck -> :neck and add sound-localize.l to launch file
* Better sound source localization and visualization:
  1) detect sound source by area of power circle and elipse ratio
  2) visualize using marker and pictogram
  3) separate sound localization and behavior controller
* Better sound source localization
* Fix minor stuff for hydro
* changed open-fridge-door function in pr2-action.l
* Run behavior server and use it from detect_cans demo
* Add interactive behavior server
* Contributors: Kamada Hitoshi, Kei Okada, Ryohei Ueda, Yuki Furuta
