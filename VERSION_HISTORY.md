VERSION HISTORY
===============

History was not kept before version 2.1.

#### 2.1
 * Fixed time issues

#### 2.2
 * Added PERFORMANCE, STATUS and HINTS logging levels

#### 2.3
 * Added host and username to be included in logs
 * Added `release.sh` for easy releaases

#### 2.5
 * Added _WIN64 macro checks for 64-bit windows machines
 * Issue#3 Force log file creation
 * Memory efficient approaches for writing logs

#### 2.6
 * Added helper function `string readLog(void)`
 * Changed `WARN` to `WARNING` for warning logs

#### 2.7
 * Fixed up log path creation issue to create whole path

#### 2.8
 * Added `update.sh` to update your old easylogging++.h without losing configuration
 * A lot of date improvements in terms of memory and performance efficiency
 * 2.843: Fixes milliseconds issue for linux only.
 * 2.844: Do not calculate milliseconds when SHOW_TIME is set to false
 * 2.845: Strict support for any other OS than linux or windows

#### 3.0
 * Major improvements
 * Added format specifiers for each logging level
 * Issue#7 formatting logs
 * 3.01: Fix up path creation on mac
 * 3.02: Added slash as escape character in format
 * 3.03: Fixed bug for other OS than mac, linux or windows
 * 3.04: Got rid of new line character `%n` instead `\n` can be used
 * 3.05 and 3.06: Fixes for \n from 3.04
 * 3.07: Adds _DISABLE_EASYLOGGINGPP, macro to disable EasyLogging++ while compiling
 * 3.08: Fix for update.sh includes
 * 3.09 improvements around log file performance

#### 3.1
 * 3.10: Removed comments around configuration to point to README
 * 3.11: Type / level constructor called within WRITE_LOG macro only 
 * 3.12: minor fixes around comments
 * 3.13: fixes for update.sh
 * 3.14: fix for windows compile failure, thanks to `codyzu`
 * 3.15: Added more control over disabling logs
         Changed from `_DISABLE_EASYLOGGINGPP` to `_DISABLE_LOGS`