<!-- THIS FILE IS UPDATED AUTOMATICALLY, ANY CHANGES WILL BE OVERRIDDEN -->
# Changelog
All notable changes to Mainsail will be documented in this file.

## [0.1.12](https://github.com/lulzbot3d/mainsail_AMOS/releases/tag/v0.1.12) - 2026-02-25
### Features

- **AFC**: Add function to map Tools to Lanes in the start print dialog ([#2256](https://github.com/lulzbot3d/mainsail_AMOS/pull/2256))
- **AFC**: Show toolchanges instead of filament length in status panel ([#2295](https://github.com/lulzbot3d/mainsail_AMOS/pull/2295))
- **AFC**: Merged buttons into macros to display help text ([#2272](https://github.com/lulzbot3d/mainsail_AMOS/pull/2272))
- **AFC**: Add TD-1 data to AFC panel ([#2273](https://github.com/lulzbot3d/mainsail_AMOS/pull/2273))
- **Console**: Change from Helplist to Printer.Gcode ([#2033](https://github.com/lulzbot3d/mainsail_AMOS/pull/2033))
- **Console**: Improve key up/down in Console with multi-line input/history ([#2108](https://github.com/lulzbot3d/mainsail_AMOS/pull/2108))
- **Dashboard**: Add option to change length and filter files ([#2051](https://github.com/lulzbot3d/mainsail_AMOS/pull/2051))
- **Editor**: Store last state of file structure sidebar ([#2140](https://github.com/lulzbot3d/mainsail_AMOS/pull/2140))
- **Extruder**: Show PA settings for extruder_stepper ([#2283](https://github.com/lulzbot3d/mainsail_AMOS/pull/2283))
- **Gcodefiles**: Add support for multi color gcode files  ([#2216](https://github.com/lulzbot3d/mainsail_AMOS/pull/2216))
- **HappyHare**: Add Flowguard meter to monitor clog/tangle ([#2311](https://github.com/lulzbot3d/mainsail_AMOS/pull/2311))
- **HappyHare**: Added flowrate % to flowguard meter when using proportional sensor
- **HappyHare**: Adds tiny numeric indicator of sensor position for Proportional Feedback sync-feedback buffers ([#2343](https://github.com/lulzbot3d/mainsail_AMOS/pull/2343))
- **Heightmap**: Add option to set the default orientation ([#2006](https://github.com/lulzbot3d/mainsail_AMOS/pull/2006))
- **History**: Add option to show stats in different values ([#2007](https://github.com/lulzbot3d/mainsail_AMOS/pull/2007))
- **Preheat**: Add chamber temperature (M141) support to preheat gcode button ([#2382](https://github.com/lulzbot3d/mainsail_AMOS/pull/2382))
- **StatusPanel**: Change tab text to icons ([#2054](https://github.com/lulzbot3d/mainsail_AMOS/pull/2054))
- **StatusPanel**: Add option to show history in StatusPanel ([#2055](https://github.com/lulzbot3d/mainsail_AMOS/pull/2055))
- **TemperaturePanel**: Add SHT3X support ([#2025](https://github.com/lulzbot3d/mainsail_AMOS/pull/2025))
- **TemperaturePanel**: Add support for AHT1X, AHT2X, AHT3X sensors ([#2329](https://github.com/lulzbot3d/mainsail_AMOS/pull/2329))
- **TemperaturePanel**: Add support for 'temperature_combined' sensor ([#2366](https://github.com/lulzbot3d/mainsail_AMOS/pull/2366))
- **Temperatures**: Add menu to open Settings & turn off heaters ([#2103](https://github.com/lulzbot3d/mainsail_AMOS/pull/2103))
- **UpdateManager**: Implement python package entries ([#2092](https://github.com/lulzbot3d/mainsail_AMOS/pull/2092))
- **Webcam**: Add a optional overlay for IDEX calibration ([#2053](https://github.com/lulzbot3d/mainsail_AMOS/pull/2053))
- **Webcam**: Add rotation function to all webcam clients ([#2259](https://github.com/lulzbot3d/mainsail_AMOS/pull/2259))
- **Webcam**: Add iframe-based webcam service option ([#2384](https://github.com/lulzbot3d/mainsail_AMOS/pull/2384))
- **console**: Add debug prefix ([#1973](https://github.com/lulzbot3d/mainsail_AMOS/pull/1973))
- **console**: Add option for RAW-output (for debugging) ([#1975](https://github.com/lulzbot3d/mainsail_AMOS/pull/1975))
- **dashboard**: Add support for moonraker sensor ([#1888](https://github.com/lulzbot3d/mainsail_AMOS/pull/1888))
- **history**: Add support for Moonraker sensor history_fields ([#1884](https://github.com/lulzbot3d/mainsail_AMOS/pull/1884))
- **history**: Add moonraker sensors to total statistic ([#1886](https://github.com/lulzbot3d/mainsail_AMOS/pull/1886))
- **miscellaneous**: Add support for pwm_tool and pwm_cycle_time ([#1804](https://github.com/lulzbot3d/mainsail_AMOS/pull/1804))
- **notification**: Add TMC overheating warnings ([#1919](https://github.com/lulzbot3d/mainsail_AMOS/pull/1919))
- **spoolman**: Add multi tool support ([#1946](https://github.com/lulzbot3d/mainsail_AMOS/pull/1946))
- **statusPanel**: Add option to disable the thumbnail zoom ([#1905](https://github.com/lulzbot3d/mainsail_AMOS/pull/1905))
- **systemLoads**: Add function to output app name in system loads panel ([#1906](https://github.com/lulzbot3d/mainsail_AMOS/pull/1906))
- **systemLoads**: Add firmware name, when it is not Klipper ([#1911](https://github.com/lulzbot3d/mainsail_AMOS/pull/1911))
- **theme**: Add voron build-in theme ([#1930](https://github.com/lulzbot3d/mainsail_AMOS/pull/1930))
- **theme**: Add LDO Motion theme ([#1932](https://github.com/lulzbot3d/mainsail_AMOS/pull/1932))
- **theme**: Add YUMI theme ([#1936](https://github.com/lulzbot3d/mainsail_AMOS/pull/1936))
- **theme**: Add VzBot theme ([#1937](https://github.com/lulzbot3d/mainsail_AMOS/pull/1937))
- **theme**: Add Prusa Research theme ([#1935](https://github.com/lulzbot3d/mainsail_AMOS/pull/1935))
- **theme**: Add bigtreetech theme ([#1931](https://github.com/lulzbot3d/mainsail_AMOS/pull/1931))
- **theme**: Add Multec theme ([#1934](https://github.com/lulzbot3d/mainsail_AMOS/pull/1934))
- **theme**: Add option for dedicated CSS file per theme ([#1958](https://github.com/lulzbot3d/mainsail_AMOS/pull/1958))
- **updateManager**: Use info_tag desc for the name ([#1959](https://github.com/lulzbot3d/mainsail_AMOS/pull/1959))
- Add fullscreen size for gcodefiles, gcodeviewer and webcam ([#1803](https://github.com/lulzbot3d/mainsail_AMOS/pull/1803))
- Add qr search function in the spoolman change spool dialog ([#1802](https://github.com/lulzbot3d/mainsail_AMOS/pull/1802))
- Add confirmation dialog to cooldown button ([#1808](https://github.com/lulzbot3d/mainsail_AMOS/pull/1808))
- Add only save button to editor ([#1835](https://github.com/lulzbot3d/mainsail_AMOS/pull/1835))
- Add option to disable favicon progress circle ([#1825](https://github.com/lulzbot3d/mainsail_AMOS/pull/1825))
- Add support for klipper runtime warnings ([#1809](https://github.com/lulzbot3d/mainsail_AMOS/pull/1809))
- Show macro description as tooltip when hovering a macro ([#1849](https://github.com/lulzbot3d/mainsail_AMOS/pull/1849))
- Connect to Moonraker via subdirectory/path ([#1836](https://github.com/lulzbot3d/mainsail_AMOS/pull/1836))
- Direct link to specific printer via query parameter ([#1837](https://github.com/lulzbot3d/mainsail_AMOS/pull/1837))
- Expose css variable for changing theme logo color ([#1856](https://github.com/lulzbot3d/mainsail_AMOS/pull/1856))
- Reminders panel on the History page ([#1274](https://github.com/lulzbot3d/mainsail_AMOS/pull/1274))
- Add support for base url ([#1873](https://github.com/lulzbot3d/mainsail_AMOS/pull/1873))
- Add hotkeys tied to Save, Save + Restart ([#1902](https://github.com/lulzbot3d/mainsail_AMOS/pull/1902))
- Add support for build-in themes and add a Klipper theme ([#1859](https://github.com/lulzbot3d/mainsail_AMOS/pull/1859))
- Added second layer confirmation for Cancel Job ([#1978](https://github.com/lulzbot3d/mainsail_AMOS/pull/1978))
- Adds a file structure sidebar in the editor ([#1943](https://github.com/lulzbot3d/mainsail_AMOS/pull/1943))
- Add output on connection dialog for unauthorized ([#1996](https://github.com/lulzbot3d/mainsail_AMOS/pull/1996))
- Add heartbeat to the moonraker websocket ([#2003](https://github.com/lulzbot3d/mainsail_AMOS/pull/2003))
- Add link to the Docs for Unauthorized connections ([#2035](https://github.com/lulzbot3d/mainsail_AMOS/pull/2035))
- Multiple nevermore support ([#1939](https://github.com/lulzbot3d/mainsail_AMOS/pull/1939))
- Add button to open the device dialog in SystemPanel ([#2046](https://github.com/lulzbot3d/mainsail_AMOS/pull/2046))
- Add SGP40 support ([#2040](https://github.com/lulzbot3d/mainsail_AMOS/pull/2040))
- Add option to hide other Klipper & Moonraker instances ([#2029](https://github.com/lulzbot3d/mainsail_AMOS/pull/2029))
- Use _CLIENT_LINEAR_MOVE macros instead of multi-line gcodes ([#2043](https://github.com/lulzbot3d/mainsail_AMOS/pull/2043))
- Add load cell gram scales in misc panel ([#2173](https://github.com/lulzbot3d/mainsail_AMOS/pull/2173))
- Add support for hall filament width sensor ([#2193](https://github.com/lulzbot3d/mainsail_AMOS/pull/2193))
- Add search functionality to macro settings interface ([#2141](https://github.com/lulzbot3d/mainsail_AMOS/pull/2141))
- Added more date format options ([#2210](https://github.com/lulzbot3d/mainsail_AMOS/pull/2210))
- Add -unprivileged docker image to conform with restricted pod security standard ([#2213](https://github.com/lulzbot3d/mainsail_AMOS/pull/2213))
- Add AFC support (Armored Turtle) ([#2231](https://github.com/lulzbot3d/mainsail_AMOS/pull/2231))
- Add support for Happy Hare ([#2158](https://github.com/lulzbot3d/mainsail_AMOS/pull/2158))
- Add LED effects panel  ([#2275](https://github.com/lulzbot3d/mainsail_AMOS/pull/2275))

### Bug Fixes and Improvements

- **AFC**: This PR fix the AFC settings with many lanes ([#2260](https://github.com/lulzbot3d/mainsail_AMOS/pull/2260))
- **AFC**: Fixes issue where filament spool does not display correctly in safari browser ([#2270](https://github.com/lulzbot3d/mainsail_AMOS/pull/2270))
- **AFC**: Fix remap filament change dialog close with esc ([#2321](https://github.com/lulzbot3d/mainsail_AMOS/pull/2321))
- **AFC**: Use correct fallback for empty spool color in filament dialog ([#2381](https://github.com/lulzbot3d/mainsail_AMOS/pull/2381))
- **Configfiles**: Fix context menu handling ([#2339](https://github.com/lulzbot3d/mainsail_AMOS/pull/2339))
- **Dashboard**: Remove MMU-Panel, when no mmu module exists in Klipper ([#2313](https://github.com/lulzbot3d/mainsail_AMOS/pull/2313))
- **Dashboard**: Set ArmoredTurtle logo/icon for the AFC panel in settings ([#2314](https://github.com/lulzbot3d/mainsail_AMOS/pull/2314))
- **Docker**: Disable ipv6 when it is not available on the Host ([#2354](https://github.com/lulzbot3d/mainsail_AMOS/pull/2354))
- **Docker**: Add latest tag support for versioned releases ([#2374](https://github.com/lulzbot3d/mainsail_AMOS/pull/2374))
- **Dockerfile**: Remove unnecessary script copy for unprivileged image ([#2377](https://github.com/lulzbot3d/mainsail_AMOS/pull/2377))
- **Editor**: Trigger gotoLine only when change is from sidebar ([#2012](https://github.com/lulzbot3d/mainsail_AMOS/pull/2012))
- **Editor**: Fix editor width when sidebar is hidden ([#2014](https://github.com/lulzbot3d/mainsail_AMOS/pull/2014))
- **Editor**: Fix maximal height of the sidebar ([#2079](https://github.com/lulzbot3d/mainsail_AMOS/pull/2079))
- **Editor**: Fix docs link for Kalico ([#2080](https://github.com/lulzbot3d/mainsail_AMOS/pull/2080))
- **Editor**: Fix structure sidebar for files with values without a section ([#2139](https://github.com/lulzbot3d/mainsail_AMOS/pull/2139))
- **ExtruderPanel**: Restore mode after extruding/retracting ([#1965](https://github.com/lulzbot3d/mainsail_AMOS/pull/1965))
- **ExtruderPanel**: Fix extrude and speed factor output ([#2002](https://github.com/lulzbot3d/mainsail_AMOS/pull/2002))
- **ExtruderPanel**: Always show pressure advance option in cogs menu ([#2303](https://github.com/lulzbot3d/mainsail_AMOS/pull/2303))
- **Files**: Fix disk usage in new directories ([#2226](https://github.com/lulzbot3d/mainsail_AMOS/pull/2226))
- **Gcodefiles**: Fix context menu handling ([#2338](https://github.com/lulzbot3d/mainsail_AMOS/pull/2338))
- **HappHare**: Add missing sync-feedback bias ([#2323](https://github.com/lulzbot3d/mainsail_AMOS/pull/2323))
- **HappyHare**: Add missing Context Menu for gates ([#2310](https://github.com/lulzbot3d/mainsail_AMOS/pull/2310))
- **HappyHare**: Removed spin button from spool_id ([#2317](https://github.com/lulzbot3d/mainsail_AMOS/pull/2317))
- **HappyHare**: Fix errors in selected tool ([#2318](https://github.com/lulzbot3d/mainsail_AMOS/pull/2318))
- **HappyHare**: Clean up of clog meter for consistent sizing ([#2316](https://github.com/lulzbot3d/mainsail_AMOS/pull/2316))
- **HappyHare**: Add "loading" feedback to main action buttons ([#2315](https://github.com/lulzbot3d/mainsail_AMOS/pull/2315))
- **HappyHare**: Add "loading" feedback to gate context action buttons ([#2324](https://github.com/lulzbot3d/mainsail_AMOS/pull/2324))
- **HappyHare**: Fix unit gate wrapping ([#2312](https://github.com/lulzbot3d/mainsail_AMOS/pull/2312))
- **HappyHare**: Fix eject button disabling logic ([#2336](https://github.com/lulzbot3d/mainsail_AMOS/pull/2336))
- **HappyHare**: Clog detection meter dependent on encoder OR sync-feedback ([#2342](https://github.com/lulzbot3d/mainsail_AMOS/pull/2342))
- **HappyHare**: Fix color match in TTG Map ([#2341](https://github.com/lulzbot3d/mainsail_AMOS/pull/2341))
- **HappyHare**: Fixes animated filament position so filament doesn't go backwards ([#2347](https://github.com/lulzbot3d/mainsail_AMOS/pull/2347))
- **HappyHare**: Remove too much divider in print start dialog ([#2350](https://github.com/lulzbot3d/mainsail_AMOS/pull/2350))
- **HappyHare**: Fix EMU logo in dark mode ([#2369](https://github.com/lulzbot3d/mainsail_AMOS/pull/2369))
- **Heightmap**: Correct bed mesh coordinate calculation ([#2293](https://github.com/lulzbot3d/mainsail_AMOS/pull/2293))
- **History**: Adjust button tooltips to consistent style ([#2018](https://github.com/lulzbot3d/mainsail_AMOS/pull/2018))
- **History**: Fix count per page switch in the History List Panel ([#2133](https://github.com/lulzbot3d/mainsail_AMOS/pull/2133))
- **HistoryList**: Implement context menu close functionality using EventBus ([#2378](https://github.com/lulzbot3d/mainsail_AMOS/pull/2378))
- **HistoryPanel**: Fix History thumbnails of files in folders ([#2010](https://github.com/lulzbot3d/mainsail_AMOS/pull/2010))
- **Locale**: Add missing translation key in SettingsControlTab ([#2104](https://github.com/lulzbot3d/mainsail_AMOS/pull/2104))
- **MacroPrompt**: Fix margin between multi line buttons ([#2352](https://github.com/lulzbot3d/mainsail_AMOS/pull/2352))
- **MediaMTX**: Fix some connection issues ([#1979](https://github.com/lulzbot3d/mainsail_AMOS/pull/1979))
- **MoonrakerSensor**: Fix sensor name display logic ([#2356](https://github.com/lulzbot3d/mainsail_AMOS/pull/2356))
- **Settings**: Fix drag&drop sortable in Orcaslicer ([#2353](https://github.com/lulzbot3d/mainsail_AMOS/pull/2353))
- **Spoolman**: Only refresh spoolman db while opening dialog ([#2308](https://github.com/lulzbot3d/mainsail_AMOS/pull/2308))
- **Spoolman**: Fix init load from spool db ([#2340](https://github.com/lulzbot3d/mainsail_AMOS/pull/2340))
- **Spoolman**: Replace spoolman url to api hostname when localhost ([#2351](https://github.com/lulzbot3d/mainsail_AMOS/pull/2351))
- **StatusPanel**: Fix context menu handling ([#2333](https://github.com/lulzbot3d/mainsail_AMOS/pull/2333))
- **StatusPanel**: Fix autofocus in rename dialog from gcodefiles ([#2335](https://github.com/lulzbot3d/mainsail_AMOS/pull/2335))
- **StatusPanel**: Fix filename exists check in rename gcodefile dialog ([#2345](https://github.com/lulzbot3d/mainsail_AMOS/pull/2345))
- **Timelapse**: Fix count per page switch in the Timelapse Files Panel ([#2134](https://github.com/lulzbot3d/mainsail_AMOS/pull/2134))
- **Tools**: Use gcode commands instead of config gcode macros ([#2088](https://github.com/lulzbot3d/mainsail_AMOS/pull/2088))
- **Webcam**: Capitalize the connection state ([#2019](https://github.com/lulzbot3d/mainsail_AMOS/pull/2019))
- **Webcam**: Make webcam view non-draggable ([#2057](https://github.com/lulzbot3d/mainsail_AMOS/pull/2057))
- **Webcam**: Add ICE Candidates check to support older camera-streamer versions ([#2069](https://github.com/lulzbot3d/mainsail_AMOS/pull/2069))
- **Webcam**: Fix webcam settings form in light mode ([#2225](https://github.com/lulzbot3d/mainsail_AMOS/pull/2225))
- **Webcam**: Fix portrait webcam rotation in mjpegstreamer-adaptive ([#2258](https://github.com/lulzbot3d/mainsail_AMOS/pull/2258))
- **Webcam**: Add keepalive function to camera-streamer ([#2280](https://github.com/lulzbot3d/mainsail_AMOS/pull/2280))
- **Webcam**: Add error handling and fallback for camera-streamer ICE servers ([#2281](https://github.com/lulzbot3d/mainsail_AMOS/pull/2281))
- **console**: Trim output to remove spaces at first char ([#1962](https://github.com/lulzbot3d/mainsail_AMOS/pull/1962))
- **control**: Check set actionButton before display it ([#1953](https://github.com/lulzbot3d/mainsail_AMOS/pull/1953))
- **extruderPanel**: Add speed_factor to estimate extrusion calc ([#1913](https://github.com/lulzbot3d/mainsail_AMOS/pull/1913))
- **farm**: Fix switching to other printer function ([#1865](https://github.com/lulzbot3d/mainsail_AMOS/pull/1865))
- **gcodeviewer**: Update gcodeviewer to fix rendering issues ([#1926](https://github.com/lulzbot3d/mainsail_AMOS/pull/1926))
- **gcodeviewer**: Fix gcodeviewer simulation while printing ([#1954](https://github.com/lulzbot3d/mainsail_AMOS/pull/1954))
- **gcodeviewer**: Fix scarf seam in Gcodeviewer ([#2227](https://github.com/lulzbot3d/mainsail_AMOS/pull/2227))
- **history**: Add missing fields in detail dialog ([#1940](https://github.com/lulzbot3d/mainsail_AMOS/pull/1940))
- **history**: Fix filter reactivity ([#2129](https://github.com/lulzbot3d/mainsail_AMOS/pull/2129))
- **macro-prompts**: Preserve outer quotes ([#2076](https://github.com/lulzbot3d/mainsail_AMOS/pull/2076))
- **macroPromts**: Fix internal close function ([#1918](https://github.com/lulzbot3d/mainsail_AMOS/pull/1918))
- **maintenance**: Fix overdue check from printtime based entries ([#1871](https://github.com/lulzbot3d/mainsail_AMOS/pull/1871))
- **maintenance**: Add init entry to init store only one time ([#1914](https://github.com/lulzbot3d/mainsail_AMOS/pull/1914))
- **maintenance**: Fix filament trigger for maintenance entries ([#1941](https://github.com/lulzbot3d/mainsail_AMOS/pull/1941))
- **notifications**: Fix dismiss function for tmc warnings ([#1956](https://github.com/lulzbot3d/mainsail_AMOS/pull/1956))
- **screwsTiltCalculate**: Use the same direction on retry ([#1920](https://github.com/lulzbot3d/mainsail_AMOS/pull/1920))
- **spoolman**: Break long comments & support multiline comments ([#1781](https://github.com/lulzbot3d/mainsail_AMOS/pull/1781))
- **spoolman**: Fix search for spool-id ([#1872](https://github.com/lulzbot3d/mainsail_AMOS/pull/1872))
- **spoolman**: Save spool_id in lowercase variable ([#2160](https://github.com/lulzbot3d/mainsail_AMOS/pull/2160))
- **statusPanel**: Fix the thumbnail overlay in the light theme ([#1912](https://github.com/lulzbot3d/mainsail_AMOS/pull/1912))
- **systemLoads**: Fix temp output when no temp sensor was found in klipper ([#1907](https://github.com/lulzbot3d/mainsail_AMOS/pull/1907))
- **tempchart**: Fix select/unselect monitor sensors in tempchart ([#1903](https://github.com/lulzbot3d/mainsail_AMOS/pull/1903))
- **theme**: Fix color change on theme change ([#1933](https://github.com/lulzbot3d/mainsail_AMOS/pull/1933))
- **timelapse**: Add warning if snapshoturl is set in moonraker ([#1921](https://github.com/lulzbot3d/mainsail_AMOS/pull/1921))
- **updateManager**: Fix updatr for git_repos without semver ([#1925](https://github.com/lulzbot3d/mainsail_AMOS/pull/1925))
- **updatemanager**: Loosely parse package semver ([#2179](https://github.com/lulzbot3d/mainsail_AMOS/pull/2179))
- **updatemanager**: Only git repos can soft recover ([#2191](https://github.com/lulzbot3d/mainsail_AMOS/pull/2191))
- **webcam**: Fix fps output in light mode ([#1901](https://github.com/lulzbot3d/mainsail_AMOS/pull/1901))
- **webcam**: Fix memory leak in MJPEGStreamer client ([#1987](https://github.com/lulzbot3d/mainsail_AMOS/pull/1987))
- **webcam**: Fix some connection issues in Camera-Streamer ([#1981](https://github.com/lulzbot3d/mainsail_AMOS/pull/1981))
- **z-tilt**: Fix z_tilt check for older Klipper versions ([#2102](https://github.com/lulzbot3d/mainsail_AMOS/pull/2102))
- Fix commit list view on desktop and mobile devices ([#1785](https://github.com/lulzbot3d/mainsail_AMOS/pull/1785))
- Fix long M117 outputs in the status panel ([#1800](https://github.com/lulzbot3d/mainsail_AMOS/pull/1800))
- Fix long content lines in console ([#1799](https://github.com/lulzbot3d/mainsail_AMOS/pull/1799))
- Hide moonraker backups when "Hide backup files" is enabled ([#1801](https://github.com/lulzbot3d/mainsail_AMOS/pull/1801))
- Hide crowsnest backups when "Hide backup files" is enabled ([#1824](https://github.com/lulzbot3d/mainsail_AMOS/pull/1824))
- Fix typo issues with save zoffset for probes ([#1821](https://github.com/lulzbot3d/mainsail_AMOS/pull/1821))
- Fix case sensibility for printer power device ([#1827](https://github.com/lulzbot3d/mainsail_AMOS/pull/1827))
- Fix WebRTC(MediaMTX) webcam client ([#1843](https://github.com/lulzbot3d/mainsail_AMOS/pull/1843))
- Ignore wrong default.json file while resetting moonraker db ([#1829](https://github.com/lulzbot3d/mainsail_AMOS/pull/1829))
- Calc multiplicator for set_pin gcode ([#1870](https://github.com/lulzbot3d/mainsail_AMOS/pull/1870))
- Consecutive and leading whitespace is not shown in console ([#1896](https://github.com/lulzbot3d/mainsail_AMOS/pull/1896))
- Fix duration format function ([#1894](https://github.com/lulzbot3d/mainsail_AMOS/pull/1894))
- Update moonraker log path in TheConnectingDialog.vue ([#1909](https://github.com/lulzbot3d/mainsail_AMOS/pull/1909))
- Display "pause on layer"-button only when the macros exists ([#1876](https://github.com/lulzbot3d/mainsail_AMOS/pull/1876))
- Fix uuid request in MediaMTX webcam client ([#1968](https://github.com/lulzbot3d/mainsail_AMOS/pull/1968))
- Change Min Cruise Ratio to percent in MachineSettingsPanel ([#1992](https://github.com/lulzbot3d/mainsail_AMOS/pull/1992))
- Correct github commit after link in commit list ([#2000](https://github.com/lulzbot3d/mainsail_AMOS/pull/2000))
- Fix image viewer if the image is wider than the viewport ([#2020](https://github.com/lulzbot3d/mainsail_AMOS/pull/2020))
- Fix color picker for PCA9632 ([#2028](https://github.com/lulzbot3d/mainsail_AMOS/pull/2028))
- Tool rows in even lengths, and more visually tidy ([#2041](https://github.com/lulzbot3d/mainsail_AMOS/pull/2041))
- Fix reference link in editor while printing ([#2050](https://github.com/lulzbot3d/mainsail_AMOS/pull/2050))
- Fix save z offset in toolhead panel ([#2060](https://github.com/lulzbot3d/mainsail_AMOS/pull/2060))
- Keep macro prompt open for events older than 100 ([#2045](https://github.com/lulzbot3d/mainsail_AMOS/pull/2045))
- Escape all file URLs to support all kind of special chars ([#2065](https://github.com/lulzbot3d/mainsail_AMOS/pull/2065))
- Fix interface settings Control-Tab when printer is not available ([#2071](https://github.com/lulzbot3d/mainsail_AMOS/pull/2071))
- Fix print start from dashboard for subdirectory files ([#2074](https://github.com/lulzbot3d/mainsail_AMOS/pull/2074))
- Hide horizontal scrollbar in StartPrintDialog.vue ([#2075](https://github.com/lulzbot3d/mainsail_AMOS/pull/2075))
- Fix z_tilt button for z_tilt_ng with Kalico ([#2078](https://github.com/lulzbot3d/mainsail_AMOS/pull/2078))
- Update Gcode-Viewer lib from sindarius to fix G2/G3 visualisation ([#2127](https://github.com/lulzbot3d/mainsail_AMOS/pull/2127))
- Show system panel when Klipper is not ready ([#2149](https://github.com/lulzbot3d/mainsail_AMOS/pull/2149))
- Fix the axios up- & download rate ([#2172](https://github.com/lulzbot3d/mainsail_AMOS/pull/2172))
- Add light theme to codemirror ([#2234](https://github.com/lulzbot3d/mainsail_AMOS/pull/2234))
- Remove debug console output in MiscellaneousLightNeopixelDialog.vue ([#2277](https://github.com/lulzbot3d/mainsail_AMOS/pull/2277))
- Fix splitting gcode filament_names metadata ([#2337](https://github.com/lulzbot3d/mainsail_AMOS/pull/2337))
- Update page title in inactive browser tabs ([#2383](https://github.com/lulzbot3d/mainsail_AMOS/pull/2383))
- Use natural sort for caseInsensitiveSort to handle numeric suffixes correctly ([#2380](https://github.com/lulzbot3d/mainsail_AMOS/pull/2380))

### Performance

- Fix hang when leaving G-Code Preview page ([#1949](https://github.com/lulzbot3d/mainsail_AMOS/pull/1949))
- Fixed hanging in gcode viewer on render quality change when no file is loaded ([#2207](https://github.com/lulzbot3d/mainsail_AMOS/pull/2207))

### Refactor

- **ControlPanel**: Use SAVE/RESTORE STATE when moving ([#1988](https://github.com/lulzbot3d/mainsail_AMOS/pull/1988))
- **Dialogs**: Modernize with VModel and consolidate buttons ([#2372](https://github.com/lulzbot3d/mainsail_AMOS/pull/2372))
- **ExtruderPanel**: Add `_` prefix to gcode_state name ([#1989](https://github.com/lulzbot3d/mainsail_AMOS/pull/1989))
- **Gcodefiles**: Refactor gcodefiles panel and table ([#2212](https://github.com/lulzbot3d/mainsail_AMOS/pull/2212))
- **HappyHare**: Fix type issue and simplify SyncFeedback code ([#2327](https://github.com/lulzbot3d/mainsail_AMOS/pull/2327))
- **Machine**: Refactor endstop panel and add dockable_probe ([#2124](https://github.com/lulzbot3d/mainsail_AMOS/pull/2124))
- **Sidebar**: Simplify template structure and active state handling ([#2355](https://github.com/lulzbot3d/mainsail_AMOS/pull/2355))
- **StatusPanel**: Remove old/unused code in GcodefilesEntry ([#2334](https://github.com/lulzbot3d/mainsail_AMOS/pull/2334))
- **Theme**: Update Yumi logo ([#2357](https://github.com/lulzbot3d/mainsail_AMOS/pull/2357))
- **e-stop**: Remove fullscreen mode on mobile devices ([#1816](https://github.com/lulzbot3d/mainsail_AMOS/pull/1816))
- **macros**: Refactor gcode_macros getter ([#1889](https://github.com/lulzbot3d/mainsail_AMOS/pull/1889))
- **miscellaneous**: Refactor led/neopixel in MiscellaneousPanel.vue ([#2218](https://github.com/lulzbot3d/mainsail_AMOS/pull/2218))
- **timelapse**: Refactor the timelapse status panel ([#1982](https://github.com/lulzbot3d/mainsail_AMOS/pull/1982))
- **webcam**: Refactor Mjpegstreamer-Adaptive Webcam mode ([#1994](https://github.com/lulzbot3d/mainsail_AMOS/pull/1994))
- Refactor KlippyStatePanel ([#1826](https://github.com/lulzbot3d/mainsail_AMOS/pull/1826))
- Remove unused attribute in getPrinttimeAvgArray getter ([#1861](https://github.com/lulzbot3d/mainsail_AMOS/pull/1861))
- Refactor TheTopbar, remove unused gette, fix snackbar ([#1923](https://github.com/lulzbot3d/mainsail_AMOS/pull/1923))
- Refactor machine settings panel ([#1991](https://github.com/lulzbot3d/mainsail_AMOS/pull/1991))
- Refactor Console & MiniConsole ([#2031](https://github.com/lulzbot3d/mainsail_AMOS/pull/2031))
- Refactor files list in StatusPanel ([#2047](https://github.com/lulzbot3d/mainsail_AMOS/pull/2047))
- Refactor gcodeviewer page ([#2061](https://github.com/lulzbot3d/mainsail_AMOS/pull/2061))
- Remove duplicate PrinterStateLight definition ([#2171](https://github.com/lulzbot3d/mainsail_AMOS/pull/2171))
- Remove unused vue import in historyStats.ts ([#2209](https://github.com/lulzbot3d/mainsail_AMOS/pull/2209))
- Rename Ipcamera to HTML-Video ([#2257](https://github.com/lulzbot3d/mainsail_AMOS/pull/2257))
- Replace vue-resize with ResizeObserver ([#2348](https://github.com/lulzbot3d/mainsail_AMOS/pull/2348))
- Remove unused PrinterStateLight type in printer store ([#2370](https://github.com/lulzbot3d/mainsail_AMOS/pull/2370))
- Move HistoryListPanelCol interface to centralized type ([#2379](https://github.com/lulzbot3d/mainsail_AMOS/pull/2379))

### Styling

- **ESlint**: Fix attribute order in SettingsMacrosTabExpert.vue ([#2373](https://github.com/lulzbot3d/mainsail_AMOS/pull/2373))
- Run prettier in locale files
- Run prettier in locale files
- Run prettier and fix format in MmuFilamentStatus.vue ([#2385](https://github.com/lulzbot3d/mainsail_AMOS/pull/2385))

### Localization

- **Weblate**: Update translation files ([#2203](https://github.com/lulzbot3d/mainsail_AMOS/pull/2203))
- **cz**: Update Czech translations
- **da**: Update Danish translations
- **de**: Update german translation ([#1860](https://github.com/lulzbot3d/mainsail_AMOS/pull/1860))
- **de**: Update german locale ([#1928](https://github.com/lulzbot3d/mainsail_AMOS/pull/1928))
- **de**: Update german locale ([#2070](https://github.com/lulzbot3d/mainsail_AMOS/pull/2070))
- **de**: Update German translations
- **en**: Remove unused keys ([#1855](https://github.com/lulzbot3d/mainsail_AMOS/pull/1855))
- **en**: Add missing english locale ([#1890](https://github.com/lulzbot3d/mainsail_AMOS/pull/1890))
- **en**: Remove unused keys in english locale ([#1929](https://github.com/lulzbot3d/mainsail_AMOS/pull/1929))
- **en**: Remove unused key ([#2105](https://github.com/lulzbot3d/mainsail_AMOS/pull/2105))
- **es**: Update Spanish translations
- **fa**: Update French translations
- **fr**: Update French translate file
- **hu**: Update Hungarian translations
- **it**: Update italian translation ([#2049](https://github.com/lulzbot3d/mainsail_AMOS/pull/2049))
- **it**: Update Italian translations
- **ja**: Update Japanese translations
- **ko**: Update Korean translations
- **nl**: Update Dutch translations
- **pl**: Update Polish translations
- **pt**: Update Portuguese translations
- **ru**: Update russian translation ([#1846](https://github.com/lulzbot3d/mainsail_AMOS/pull/1846))
- **ru**: Update Russian translations ([#2128](https://github.com/lulzbot3d/mainsail_AMOS/pull/2128))
- **ru**: Update Russian translations
- **se**: Update Sami translations
- **sk**: Add Slovak locale file ([#2248](https://github.com/lulzbot3d/mainsail_AMOS/pull/2248))
- **sk**: Update Slovak translations
- **tr**: Update Turkish translations
- **uk**: Update ukrainian translation ([#1788](https://github.com/lulzbot3d/mainsail_AMOS/pull/1788))
- **uk**: Update ukrainian locale ([#1885](https://github.com/lulzbot3d/mainsail_AMOS/pull/1885))
- **uk**: Update Ukrainian translations
- **zh**: Update chinese locale ([#1791](https://github.com/lulzbot3d/mainsail_AMOS/pull/1791))
- **zh**: Update chinese locale ([#1877](https://github.com/lulzbot3d/mainsail_AMOS/pull/1877))
- **zh**: Update chinese locale ([#1951](https://github.com/lulzbot3d/mainsail_AMOS/pull/1951))
- **zh**: Update chinese locale ([#2081](https://github.com/lulzbot3d/mainsail_AMOS/pull/2081))
- **zh**: Update chinese locale ([#2302](https://github.com/lulzbot3d/mainsail_AMOS/pull/2302))
- **zh**: Update Chinese translations
- **zhTW**: Update Chinese translations
- Translations update from Hosted Weblate ([#1952](https://github.com/lulzbot3d/mainsail_AMOS/pull/1952))
- Update Hungarian locale with Weblate
- Update Spanish locale with Weblate
- Update Hungarian locale with Weblate
- Update Spanish locale with Weblate
- Update Hungarian locale with Weblate
- Update Spanish locale with Weblate
- Update Hungarian locale with Weblate
- Update Turkish locale with Weblate
- Update Dutch locale with Weblate
- Update Spanish locale with Weblate
- Update Hungarian locale with Weblate
- Update Spanish locale with Weblate
- Update Hungarian locale with Weblate
- Update Hungarian locale with Weblate
- Update Spanish locale with Weblate
- Update Chinese (Traditional Han script) locale with Weblate

### Documentation

- Add github sponsor link ([#1844](https://github.com/lulzbot3d/mainsail_AMOS/pull/1844))
- Remove broken badge on README.md ([#2288](https://github.com/lulzbot3d/mainsail_AMOS/pull/2288))
- Add translated badge to README.md ([#2291](https://github.com/lulzbot3d/mainsail_AMOS/pull/2291))

### Other

- **AI**: Add guidelines for AI-Agents ([#2304](https://github.com/lulzbot3d/mainsail_AMOS/pull/2304))
- **Docker**: Enable ipv6 in nginx.conf ([#2030](https://github.com/lulzbot3d/mainsail_AMOS/pull/2030))
- **Docker**: Remove default nginx files ([#2289](https://github.com/lulzbot3d/mainsail_AMOS/pull/2289))
- **Docker**: Remove mainsail.zip from docker image ([#2287](https://github.com/lulzbot3d/mainsail_AMOS/pull/2287))
- **ESLint**: Fix various ESLint errors ([#2228](https://github.com/lulzbot3d/mainsail_AMOS/pull/2228))
- **ci**: Update caniuse browser list ([#1832](https://github.com/lulzbot3d/mainsail_AMOS/pull/1832))
- **deps**: Update @sindarius/gcodeviewer ([#1755](https://github.com/lulzbot3d/mainsail_AMOS/pull/1755)) ([#1783](https://github.com/lulzbot3d/mainsail_AMOS/pull/1783))
- **prettier**: Add support to sort locale json files ([#1976](https://github.com/lulzbot3d/mainsail_AMOS/pull/1976))
- **websocket**: Add function to send and wait for response ([#2004](https://github.com/lulzbot3d/mainsail_AMOS/pull/2004))
- Fix typo/reword some parts of the pull request template ([#1850](https://github.com/lulzbot3d/mainsail_AMOS/pull/1850))
- Update gcodeviewer to v3.7.16 ([#2152](https://github.com/lulzbot3d/mainsail_AMOS/pull/2152))
- Update dependencies in package.json ([#2168](https://github.com/lulzbot3d/mainsail_AMOS/pull/2168))
- Remove deprecated @types/cypress package ([#2181](https://github.com/lulzbot3d/mainsail_AMOS/pull/2181))
- Update ISSUE_TEMPLATEs zu use the type field ([#2215](https://github.com/lulzbot3d/mainsail_AMOS/pull/2215))
- Update vite-plugin-pwa npm package and configuration ([#2371](https://github.com/lulzbot3d/mainsail_AMOS/pull/2371))

## [0.1.5](https://github.com/lulzbot3d/mainsail_AMOS/releases/tag/vv0.1.5) - 2024-04-16
### Features

- **history**: Add interrupted state to history job ([#1738](https://github.com/lulzbot3d/mainsail_AMOS/pull/1738))
- Add ability to re-arrange job queue's items ([#1692](https://github.com/lulzbot3d/mainsail_AMOS/pull/1692))
- Add sum + eta in jobqueue panel ([#1770](https://github.com/lulzbot3d/mainsail_AMOS/pull/1770))
- Add devices dialog in editor ([#1765](https://github.com/lulzbot3d/mainsail_AMOS/pull/1765))
- Add ability to add history items to job queue ([#1778](https://github.com/lulzbot3d/mainsail_AMOS/pull/1778))

### Bug Fixes and Improvements

- **console**: Fix color of autocomplete and command list ([#1733](https://github.com/lulzbot3d/mainsail_AMOS/pull/1733))
- **timelapse**: Fix issue with changing timelapse settings ([#1745](https://github.com/lulzbot3d/mainsail_AMOS/pull/1745))
- Show extruder extra menu without load/unload macros ([#1747](https://github.com/lulzbot3d/mainsail_AMOS/pull/1747))
- Fix ETA calculation from jobqueue during print preheat ([#1773](https://github.com/lulzbot3d/mainsail_AMOS/pull/1773))
- File upload rate displays `NaN` instead of an actual value ([#1777](https://github.com/lulzbot3d/mainsail_AMOS/pull/1777))

### Performance

- Batch gcode file metadata requests ([#1737](https://github.com/lulzbot3d/mainsail_AMOS/pull/1737))

### Refactor

- Refactor spoolman integration to support v2 response ([#1749](https://github.com/lulzbot3d/mainsail_AMOS/pull/1749))
- Refactor heightmap page ([#1759](https://github.com/lulzbot3d/mainsail_AMOS/pull/1759))

### Localization

- **da**: Update danish translation ([#1757](https://github.com/lulzbot3d/mainsail_AMOS/pull/1757))
- **de**: Update german locale ([#1772](https://github.com/lulzbot3d/mainsail_AMOS/pull/1772))
- **en**: Fix typo in DescriptionPreviouslyThrottled ([#1776](https://github.com/lulzbot3d/mainsail_AMOS/pull/1776))
- **it**: Update italian translation ([#1763](https://github.com/lulzbot3d/mainsail_AMOS/pull/1763))
- **zh**: Update chinese locale ([#1767](https://github.com/lulzbot3d/mainsail_AMOS/pull/1767))

### Other

- **deps**: Update @sindarius/gcodeviewer ([#1755](https://github.com/lulzbot3d/mainsail_AMOS/pull/1755))
- Fix typo in bot text ([#1748](https://github.com/lulzbot3d/mainsail_AMOS/pull/1748))

## [0.1.1](https://github.com/lulzbot3d/mainsail_AMOS/releases/tag/v0.1.1) - 2024-04-12

