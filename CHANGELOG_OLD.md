# Older changes
## 4.0.1 (2022-10-14)

Tested with OctoPrint 1.8.4

* (klein0r) Just download every thumbnail once (requires plugin Slicer Thumbnails)

## 4.0.0 (2022-05-19)

NodeJS 14.x is required (NodeJS 12.x is EOL)

Tested with OctoPrint 1.8.0

* (klein0r) Added last and average layer duration (requires plugin Display Layer Progress)
* (klein0r) Moved thumbnail information of files to new structure **(BREAKING CHANGE - CHECK YOUR SCRIPTS AND VIS)**
* (klein0r) Improved handling of thumbnails and states for plugins

## 3.2.2 (2022-04-29)

* (klein0r) Updated depedency for js-controller to 4.0.15

## 3.2.1 (2022-04-28)

* (klein0r) Get thumbnail url of current file and copy value to printjob (requires plugin Slicer Thumbnails)
* (klein0r) Updated log messages

## 3.2.0 (2022-03-07)

Tested with OctoPrint 1.7.3

* (klein0r) Added print times as readable states (seconds to string)
* (klein0r) Added formatted date when print job will finish
* (klein0r) Added fan speed and feedrate from plugin Display Layer Progress

## 3.1.0 (2022-02-24)

* (klein0r) Calculate date/time when print will be finished
* (klein0r) Renamed ``printjob.progress.printtime_left`` to ``printjob.progress.printtimeLeft`` **(BREAKING CHANGE - CHECK YOUR SCRIPTS AND VIS)**

## 3.0.1 (2022-02-12)

* (klein0r) Updated state roles
* (klein0r) Added hint for Admin 4 configuration

## 3.0.0 (2022-01-19)

* (klein0r) Added printing and operational state

## 2.2.0 (2022-01-15)

* (klein0r) Added plugin support: Slicer Thumbnails

## 2.1.1 (2022-01-14)

* (klein0r) Added: Request timeout in seconds
* (klein0r) Logging improvements

## 2.1.0 (2021-12-28)

* (klein0r) Added HTTPS option
* (klein0r) Fixed Display Layer Progress integration

## 2.0.7 (2021-12-23)

* (klein0r) Added plugin support: Display Layer Progress

## 2.0.6 (2021-12-01)

* (klein0r) Allow to pause/resume printjob

## 2.0.5 (2021-11-18)

* (klein0r) Require new version for translated instance objects
* (klein0r) Fixed timeout issues

## 2.0.4 (2021-11-16)

* (klein0r) Improved API request handling

## 2.0.3 (2021-11-15)

* (klein0r) Translated all objects

## 2.0.2 (2021-11-08)

* (klein0r) Extrude commands

## 2.0.1 (2021-11-06)

* (klein0r) Fixed missing translations

## 2.0.0 (2021-11-04)

* (klein0r) Admin 5 Support **(BREAKING CHANGE - RENAMED TEMPERATURE NAMESPACE)**

## 1.1.2 (2021-09-17)

* (klein0r) Updated file refresh handling

## 1.1.1 (2021-05-27)

* (klein0r) Minor fixes

## 1.1.0 (2021-05-03)

* (klein0r) Encrypt sensitive information **(BREAKING CHANGE - RE-ENTER YOUR API KEY)**

## 1.0.10 (2021-05-01)

* (klein0r) Fixed printjob state format issues

## 1.0.9 (2021-03-22)

* (klein0r) nodejs 12 required

## 1.0.8 (2021-02-06)

* (klein0r) Avoid constant refresh of file list

## 1.0.7 (2021-01-24)

* (klein0r) Fixed async object creation

## 1.0.6 (2021-01-09)

* (foxriver76) Avoid spamming the same error again and again

## 1.0.5 (2020-12-10)

* (klein0r) Allow to select and print files using objects
* (klein0r) Fixed .toFixed exception when no job is running

## 1.0.4 (2020-12-08)

* (klein0r) Fixed .toFixed exception when no job is running

## 1.0.3 (2020-12-05)

* (klein0r) Fixed filament information (volume and length)

## 1.0.2 (2020-11-27)

* (klein0r) Added name for OctoPrint Instance
* (klein0r) Fixed admin translation issue (syntax error)

## 1.0.1 (2020-11-10)

* (klein0r) Added iobroker sentry

## 1.0.0 (2020-10-29)

* (klein0r) First stable release

## 0.0.6 (2020-08-25)

* (klein0r) Improved error handling

## 0.0.5 (2020-08-21)

* (klein0r) Switched to axios lib (replaced request - deprecated)

## 0.0.4 (2020-05-14)

* (klein0r) Added missing translations
* (klein0r) Changed default port to 80

## 0.0.3 (2020-05-13)

* (klein0r) Updated depencencies

## 0.0.2 (2020-02-26)

* (klein0r) fixed several issues, new class based structure

## 0.0.1 (2018-05-15)

* (klein0r) initial release
