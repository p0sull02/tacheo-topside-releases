TACHEO TOPSIDE 1.6.119 (28 Nov 2026) - the Tacheo's program for Windows 10 and 11
=====================================================================

INSTALL (nothing to install, really)
1. Download "Tacheo Topside for Windows.zip" (1.6.119) from this folder.
2. Right-click it > Extract All... > Extract. Put the "Tacheo Topside" folder anywhere
   you like (Documents is fine). Don't run it from inside the zip. If you had an older
   Tacheo Topside folder, you can delete it (keep its "Shot downloads", "SAP6 backups" and
   "SAP5 backups" folders if you want them: copy them into the new folder).
3. Open the folder and double-click "Tacheo Topside.exe".
   The first time, Windows may say "Windows protected your PC" (the program isn't signed
   by a paid certificate): click "More info", then "Run anyway". It only asks once.
4. Connect the unit:
   - Tacheo, or a SAP6 running Tacheo: plug it in with a USB-C DATA cable (some cables
     only charge). It connects by itself. Or click "Bluetooth" (top right): the unit must be
     switched ON with Settings > Bluetooth > Phone link on. Two or more units (a pair) can
     be connected at once, by USB, Bluetooth or both (1.5.7).
   - SAP6 on Phil Underwood's firmware: switch it on and plug it in.
   - SAP5: switch the SAP5 OFF, then plug it in by USB. It shows on the Overview by itself
     (1.5.9); details on Devices > the SAP5 (1.6.5); update it on Updates and Upgrades > SAP5 (1.6.32). With SAP5 firmware 2.2.9 Topside also stores this
     computer's time on it: unplug it, then switch it on, and it sets its clock.
   - Cavway X1 or BRIC4 / BRIC5: plug it in by USB; a DistoX: pair it in Windows' Bluetooth
     settings (PIN 0000). Then Devices > "Read a device" (1.6.5, read only).

Keep the whole folder together: firmware\, manuals\, sap5\, sap6\, tools\ and support.txt are used.
support.txt holds where "Send to Sully" / "Send beta-test report" email the reports.

UPDATES FROM NOW ON (1.5.2 and newer)
Topside checks this folder for a newer Topside a few seconds after it starts. When there is
one, the Overview page shows an UPDATE AVAILABLE card with what's in it (1.5.4 and newer)
and a bar at the top says so: click "Install update" and it downloads it, closes, replaces
its own files and opens again (your shot downloads, backups and logs are kept). It reads one
small file ("Tacheo Topside - latest version.txt") and sends nothing. Switch it off, or
"Check now", on Updates and Upgrades > Topside. Older copies (1.5.1 and before) don't check:
download this zip once by hand.

NEW IN 1.6.106 - Tacheo 1 firmware 1.17.9: CrossTalk no longer gets stuck on "Waiting:"
- Two Tacheo 1s could both say yes to CrossTalk and then sit on "Waiting:" for ever. A connection the radio refused left
  the connecting unit deaf until it was switched off and on. Now it listens again at once, a connection that hasn't gone
  through in 6 s is tried again, and two units on 1.17.9 link whichever one connects. Nothing to set.
- Install 1.17.9 on both units (Updates and Upgrades), then pair as usual.
- Unchanged: SAP5 with the colour screen 1.17.8, SAP6 1.16.30.5. Topside itself is as 1.6.105.

NEW IN 1.6.92 - 1.6.105 - one-file projects, precise declination, entrance finder, messages to your Tacheo
- CartoTable projects are one file, <cave>.ctproj: the survey data, sketch scans and your Illustrator and PDF map drafts
  in it. File > Share Project writes that one file to hand to someone. .ctproj files have their own icon and open with a
  double-click; Topside is in "Open with" for Walls, Compass, Survex and Therion files.
- Declination is worked out for every trip from its date with the most precise model: IGRF-14 plus NOAA's WMMHR2025
  crustal field (the rocks' own magnetism, which IGRF and WMM leave out - about half a degree at Mammoth Cave).
- No GPS for an entrance? Place on the map > Find it on a map: type a town or address, then click the entrance on the
  lidar hillshade. Look it up fills in the elevation (USGS 3DEP lidar in the US, a world terrain model elsewhere).
- Opening a big cave can be cancelled, or switched to another cave. Big caves open much faster.
- Drafted PDF / Illustrator maps line up under the line plot by themselves; a heat map of the ground; Publish to web.
- Phone link: the Topside phone app (Android 1.7) connects to this computer - send it caves, get its trips and photos.
  The app also connects to two or more Tacheos at once and sends them messages.
- Unit firmware: Tacheo 1.17.8 (cave, cavec, sap5xc) and SAP6 1.16.30.5 - messages from the phone pop up on the unit.
- Updates now come from GitHub (no more antivirus warnings from the old update script).

NEW IN 1.6.89 - 1.6.91 - CartoTable: one viewer, field books, layers at hand, corrections the loops agree with
  One viewer: tick "Rotate in 3-D" on the view bar and the plot becomes the 3-D cave, starting straight down from where
  you were, in the same colours; untick it for the line plot. What you turn on stays on as you change pages. Layers (top
  left of the plot) turns station names, leads, the blunder marks, lead search areas and each map layer on or off.
  3-D: the wheel flies you into a passage at a steady pace; Headlamp or Whole cave lighting; a clicked station shows how
  far off it could be (95%, in feet) - the line plot shows it too. The ground shows in 3-D on every page, see-through.
  Survey data opens on your surveys as field books (letters and number on the cover, date, team, length, grade, leads);
  open one to read its shots, and the small map goes to it - click the map to make it big.
  Trips: every trip graded (from its loops, else its backsights), a .srv with several dates split by date, and a right-click
  to inspect it or check it with Reckon. Data clinic: the closure score on top, and "Draw round an area for Reckon" (whole
  .srv files, never cut). Reckon's corrections are only offered when the loops close better with them (some had made the
  score worse). Clicking a station or shot narrows the tables to it. No text is cut off anywhere: hover or click to read it.
  The Back button is yellow, and CartoTable opens the last cave you had open. Unit firmware unchanged.

NEW IN 1.6.85 - 1.6.88 - CartoTable: a 3-D cave, the ground over it, a better trip planner, text you can read
  3-D cave (a tile on the cave's Home page): solid passages from the LRUDs that you can turn, fly through and cut; click a
  station and the cave lights up from it and turns round it; find stations, trips or people; a shots table. SURFACE shows
  the ground from the elevation you got online (Map and GIS > Get elevation online), see-through or solid, with contours.
  Trip planner (now a tile on Home): time by how you're moving - walking, stooping, hands-and-knees and belly crawling,
  breakdown, climbing and on rope; click a lead for its whole text, when it was last pushed and by whom (save their phone
  or email from the card); Resurvey picks the stretch of a bad loop worth redoing in one trip, on your route where it can;
  Change, Previous trip and Swap fix a wrong pick; Print or save the brief as a PDF from any view. Entrances that are only map
  labels in the data are matched to the surveyed entrance, so routes from them work.
  Any table: point at cut-off text to read it, or click the row to see the whole row. Home scrolls on a small window and
  its tiles show all their words. Fixed: the plot could stop drawing (a red cross) when zoomed in close on a short stretch.
  Unit firmware unchanged.

NEW IN 1.6.78 - 1.6.84 - CartoTable: correction preview and report, survey prefixes, trip planner
  After Reckon corrects, the plot shows the old and new survey together; OK keeps it, and Export report makes a PDF of what
  changed for your data team. Every survey needs a prefix: a cave with surveys that have none asks for one per survey before it
  opens (Walls files get a #Prefix line, a .bak is kept), so two surveys using the same station names can't get mixed up.
  Trip planner: pick a start and a destination for the route with times by passage size, rigging, leads you'll pass with what to
  expect at each, stretches worth resurveying, trip ideas and a printable trip brief. Click a shot, then "Float its traverse" to
  see it hung from either end (it names a misnamed tie). Trip reports print into the cave report. Map symbols stay paper-map size.
  On a Mac, clicking a card on the welcome screen no longer closes Topside.

NEW IN 1.6.73 - 1.6.77 - CartoTable: compile on save, Exports, Trip review, ground over the cave
  Saving a typed trip compiles it, as Walls does: Reckon lists what it found in the trip - tick to fix, untick to accept, or open the line.
  Enter a trip starts in feet with the book prefix filled in. Exports: the whole cave or a box drawn on the plot, in every survey, plot and GIS
  format, plus a printout of the map with its layers. Trip review: each trip's file, book pages, report and photos; sort a folder of book scans
  into trips. With elevation loaded, each station shows how far below the ground it is, and Profile cut draws the hillside over the cave.
  A dark Home with one tile per job; Map and GIS as its own workspace; the welcome screen's messages rewritten.

NEW IN 1.6.71 - CartoTable reads book pages
  Enter a new trip > Read this page: the numbers on the book data page on show go into the grid; any cell it isn't sure of, or that fails
  a check, is amber. Check every row against the book before saving. Also: a folder opens as a cave; the ground draws about 7x faster;
  lead search areas on the Map page; seasonal water and sump symbols; pit depths in circles and dome heights in squares.

NEW IN 1.6.67 - elevation online in CartoTable
  Map and GIS > Get elevation online: the ground around the cave from USGS 3DEP (lidar, 1 m where it has been flown, in the US) or the free
  global terrain tiles elsewhere. It asks first, then makes the hillshade, a colour relief, contours with labelled index lines, sinks and
  cliffs, and keeps the elevation as a GeoTIFF in Documents\CartoTable\<cave>\elevation for next time. The Rock units dialog explains itself.

NEW IN 1.6.66 - Reckon is part of CartoTable
  Reckon's own page is gone: "Cartography and GIS" at the bottom of the left menu opens CartoTable, and a .wpj or .srv dropped on Topside
  opens there. CartoTable's Compile runs Reckon, and Repair the data (beside the closure score) steps through every problem worst first.
  Also new in CartoTable: the cave's own line plot on its Home page, a Back button, satellite and other base maps, a dark plot, a legend,
  loops listed in the inspector, lead sizes, the Trip page (trip report template, book, survey file, side by side, photos), photos at
  stations, and the Distance, Ruler and Box tools.

NEW IN 1.6.65 - CartoTable: survey reduction, maps and drafting, built into Topside
  - The welcome screen's CartoTable card now opens CartoTable inside Topside: open a Walls, Compass, Survex or Therion
    project (or start one), compile it, and see the closure score (100 = a perfect closure), the loops, blunders found and
    explained with what each fix gains, Reckon's checks, the map with lidar and the sinkhole finder, sketches laid on the
    survey, cross sections, annotations (leads, water, airflow, digs), and Start drafting - a to-scale page for Illustrator or
    Inkscape. Nothing is sent anywhere; cave positions stay on your computer.
  - Reckon fixes: quadrant bearings (S79E) read; files with no #Units read as metres, as in Walls; shots with a missing reading
    or a vertical well no longer send the survey hundreds of km away; much faster on big caves.
  - Unit firmware is the same as 1.6.64.

NEW IN 1.6.64 - SAP6 firmware 1.16.30.4: no more battery drain while switched off, simpler menus
  - A SAP6 running Tacheo stays in its low-power standby when switched off, instead of going fully off after 2 hours - fully
    off was what ran the battery down. A double-click brings it straight back. It goes fully off only when the cell is nearly
    flat (under 3.45 V). Update the SAP6 (Updates and Upgrades > SAP6).
  - Simpler SAP6 menus: Survey, Tools, Calibrate, Bluetooth, Settings, Device, Turn off; the rarely used settings are under
    Settings > Advanced.
  - Topside itself is the same as 1.6.63.

NEW IN 1.6.63 / 1.6.62 - a welcome screen, Reckon fixes, unit firmware 1.17.6 (Tacheo 1 OLED: no more battery drain while off)
  - 1.6.63: the welcome screen's intro shows a shot log (FROM, TO, DIST, AZI, INC) at the top left as the line plot draws. Macs get 1.6.63 too.
  - Topside opens on a welcome screen: pick Topside or Reckon (Enter / T, or R). Reckon opens on its own, without the unit pages;
    "Back to Topside" brings them back.
  - Reckon: a leg shot both ways with no loop is now flagged when its front sight and backsight disagree (it needed twice the
    disagreement before); one declination finding per project instead of one per file; a shot whose comment starts with ? is
    read as an estimate and weighted down.
  - Tacheo 1 with the OLED, firmware 1.17.6: switched off, it stays in its low-power standby instead of going fully off after
    2 hours - fully off was what ran the battery flat. A double-click brings it straight back to READY. It goes fully off only
    when the cell is nearly flat (under 3.45 V). Update the unit.
  - Tacheo 1 with the colour screen, firmware 1.17.5: bench-test commands for the builder; nothing changes for you.

NEW IN 1.6.60 - cross sections closed, unit firmware 1.17.4 (Tacheo 1 colour screen and OLED, SAP5 colour screen)
  - FIXED: the colour screen restarted on every front shot (firmware 1.16.93 - 1.17.1). Update the unit.
  - The laser is off at every switch-on: the first press lights the dot, the next takes the shot.
  - Cross sections are always drawn closed, on the unit and in Topside (sections saved before too).
  - A crash or freeze now keeps its record through the restart: send a Topside report to Sully if it ever happens.
  - Firmware 1.16.98 - 1.17.0 stays withdrawn; 1.17.4 replaces it.

NEW IN 1.6.59 - unit firmware 1.17.0 for the Tacheo 1 (colour screen and OLED)
  - The laser dot stays lit on READY. On some units the laser module put its own dot out after about 13 seconds; the Tacheo
    now tells it to stay on every 5 seconds while READY.
  - If a unit restarts unexpectedly (a crash), it now records where it happened. Send a Topside report to Sully.

NEW IN 1.6.58 - unit firmware 1.16.99 for the Tacheo 1 (colour screen and OLED), 1.16.98 for the SAP5 with the colour screen
  - Autoflip is Off by default on the Tacheo 1, and switched off once on units already set up: on the Tacheo it only ever turned
    the picture over when the unit was stood on its tail. Set the picture for your hand in Settings > Screen (Right hand / Left
    hand). Turned back On in Settings > Autoflip, it stays On.
  - The laser dot stays lit on READY - no time-out. Take a shot to put it out (1.16.98).
  - The colour unit stays in its low-power standby when switched off, and logs its time off for Sully (1.16.97 - 1.16.98).

NEW IN 1.6.57 - unit firmware 1.16.95 for the Tacheo 1 (colour screen and OLED)
- The laser stays powered while the compass is read; only the dot goes out. Fixes the OLED unit's dim dot (first shot of
  each set, calibration marks) and the colour unit's restart on a quick-press shot.
- The report no longer mixes up storage repairs and failed shots.

NEW IN 1.6.56 - unit firmware 1.16.94 for the Tacheo 1 (colour screen and OLED)
  - The axes are set by the firmware: Factory > Axes is no longer needed on a Tacheo 1. A unit that said "Axes are not set"
    gets them at the first switch-on after the update; then do Normal > All sensors outdoors. Axes set by hand are kept.

NEW IN 1.6.55 - unit firmware 1.16.93 for the Tacheo 1 (colour screen AND the OLED) and the SAP5 with the colour screen
  (SAP6 1.16.30.1 and SAP5 2.2.16 unchanged).
  - FIXED: a calibration that "failed to save" or was gone after the next restart. On some units the internal storage stopped
    taking writes. Now a save that fails repairs the storage on the spot (wipes it and writes back what the unit has in memory:
    settings with the new calibration, serial number, owner) and saves again, and the storage is checked at every switch-on.
    If your unit says "Axes are not set" or has no calibration: Factory > Axes, then Normal > All sensors outdoors.
  - Tacheo 1 with the OLED: the battery no longer runs down while switched off (the standby fix the colour units got in 1.16.87),
    plus the shared fixes since 1.16.73. After installing, do a Normal calibration outdoors.
  - Topside: the report says when a unit's storage repaired itself.

NEW IN 1.6.54 - unit firmware 1.16.92 for the Tacheo 1 with the colour screen and the SAP5 with a XIAO and the colour screen
  (Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30.1 and SAP5 2.2.16 unchanged).
  - IRON INVADERS, the calibration game, for the time spent waiting on the sketcher: Menu > Calibrate, the first row (PLAY,
    green, with a saucer). Tip and turn the unit to roll the sight onto an alien ship and hold still - it fires itself. Each
    ship shot down is a quiet compass reading. Once enough are down the MOTHERSHIP comes: if the readings show the compass has
    drifted, the unit offers a compass-only top-up, proved first with 4 shots on a real mark (Save starts on No; Undo top-up
    is in the game's Options). It never touches the laser aim, the clino or distances. Steel nearby jams it. Unplug USB to play.
  - The colour screen's large fonts now live on the unit's 2 MB storage chip (room for the game). Topside 1.6.54 puts them
    there the first time the unit is plugged in, as it does the start-up animations; until then the pages use plainer fonts.
  - Fixes: a calibration that ended with "Out of memory" (nothing was lost - the old calibration stayed in use); a shot held
    still that asked "Moved 2924 deg" (the Tacheo 1's microsecond clock went back to 0 every 67 s).
  - A new start-up message: "I DON'T LIKE SMART WATCHES."

NEW IN 1.6.53 - unit firmware: Tacheo 1 with the colour screen 1.16.90, the SAP5 with a XIAO and the colour screen 1.16.90,
  and the SAP6 1.16.30.1 (Tacheo 1 with the OLED 1.16.73 and SAP5 2.2.16 unchanged).
  - Colour screen 1.16.90: the battery % when plugged in is read with each unit's own charging lift (a unit with 4 cells read
    about 10 % low on USB). The report's "while switched off" battery figure leaves out time spent charging, and a unit that
    froze right after switching on now shows in the report.
  - SAP6 1.16.30.1: the standby battery drain fix (as the Tacheo got in 1.16.87).
NEW IN 1.6.52 - rescue a unit whose firmware has frozen (unit firmware unchanged: Tacheo 1 with the colour screen 1.16.87,
SAP5 with the colour screen 1.16.87, Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30, SAP5 2.2.16).
- A frozen unit (an update that went wrong can leave one so) is still listed by Windows but answers nothing. Topside used to
  show nothing and hang on it until the unit was unplugged. Now the top of the window says "A unit on COMx isn't answering".
- Rescue it on Updates and Upgrades: "Force update mode" (Tacheo tab, and now SAP6 > Updates too), then install - or the
  install button straight away ("Install on the unit that isn't answering"). The Tacheo tab's which-unit question offers the
  SAP6 too. Settings, calibration, serial number and stored shots are kept.
- "Update firmware only.cmd" does the same rescue without Topside; it closes Topside first (Topside holds the unit's port).
- Help: "Windows sees my unit but Topside doesn't. How do I rescue it?"

NEW IN 1.6.51 - unit firmware: Tacheo 1 with the colour screen 1.16.87, and the SAP5 with a XIAO and the colour screen 1.16.87
(Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30 and SAP5 2.2.16 unchanged). Nothing else changes in Topside.
- The battery drain while switched off, found and fixed. A meter in the battery lead showed about 13 mA in standby: the log
  flash chip and the chip's hardware blocks were left running. Switched off and unplugged for 2 s, the unit now closes the flash
  and switches those blocks off (about 0.15 mA on the same meter), and sets them back when it is plugged in or double-clicked
  on. Nothing you see or do changes.
- Colour screen Tacheo 1 also: Settings > POWER > Standby 30 min / Off (Off goes fully off 2 s after Power off - for testing;
  30 min is the default), and Device > Drain test (for a meter in the battery lead; its steps show in the Diagnosis report).

NEW IN 1.6.50 - Install update gets past Google Drive's "Download anyway" page by itself. Drive sends that page in place of
a file too big for its virus scan (the Mac download is), and Topside stopped with "Google Drive sent a web page instead of
the file". If Drive still sends a page (too many downloads today, for example), the message now says which page it was.
On a Mac, "Open the download page" opens the Mac folder. Unit firmware unchanged (Tacheo 1 colour screen 1.16.83, OLED
1.16.73, SAP6 1.16.30, SAP5 2.2.16).

NEW IN 1.6.49 - unit firmware: Tacheo 1 with the colour screen 1.16.83 (Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30 and
SAP5 2.2.16 unchanged). Nothing else changes in Topside.
- Tacheo 1 colour screen 1.16.83 - the LRUD slot: along the bottom of READY and of each result, the station's name, then L, R,
  U and D with their distances ("--" for one not taken yet), so you can read all four off to the sketcher at once.
  - Leg track on: the LRUDs of the station the unit is At. Taking one again replaces it. A leg that moves the unit on starts
    the next station's slot empty. Switched off and on again, the slot comes back.
  - Leg track off: the LRUDs since the last long shot, labelled LRUD; the next long shot clears it.
  - Not shown in Recall, or on a result with a warning.

NEW IN 1.6.48 - unit firmware: Tacheo 1 with the colour screen 1.16.82 (Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30 and
SAP5 2.2.16 unchanged).
- Tacheo 1 colour screen 1.16.82 - switched off and unplugged, the unit now goes fully off after 30 minutes in standby (was
  2 hours), so it stops drawing battery much sooner. A double-click still turns it on (a cold start, a little slower; the
  survey in progress ends there, as it did after 2 hours). Plugged in, it never goes fully off.
- Tacheo 1 colour screen 1.16.80 - HOW YOU TAKE A SHOT CHANGES AGAIN: on a result, one tap goes back to READY, and a tap on
  READY starts the countdown (1.16.79 started it straight from the result). A half-second hold on a result is still an LRUD,
  and two taps still open the menu.
- 1.16.81 - fixes from the beta reports:
  - Survey > Recall shots: a long tap leaves from any shot, and a tap goes to the next older shot (round to the newest after
    the oldest). Before, you could get stuck in it until the unit switched itself off.
  - LRUD Left and Right after a backsight are judged the way the survey runs. Before, every L and R after a backsight came
    out swapped. The same on the CrossTalk BS unit.
  - Calibration, "Target lost" with the display down: the roll on a mark now allows 12 deg between holds before the unit is
    calibrated and 8 deg after (was 8 and 5).
  - NEW: a good backsight (within the backshot angle and 0.10 ft) plays the happy beep, as FSx3 Good does. A backsight off in
    distance still gets the sad beep.

NEW IN 1.6.47 - unit firmware: Tacheo 1 with the colour screen 1.16.79 (Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30 and
SAP5 2.2.16 unchanged).
- Tacheo 1 colour screen 1.16.79 - HOW YOU TAKE A SHOT CHANGES (Sully: hand tremors while holding the button make shots less
  accurate):
  - On READY, a result or a tool's shot page, ONE TAP starts the countdown and the leg is measured with your hand off the
    button. The countdown is Settings > Shot timer (the old Shot hold, same 1.5 - 5 s).
  - Any press during the countdown calls it off. Hold the button half a second for an LRUD. Two quick taps: the menu.
  - The old 3-second hold for a leg is gone.
- Tools > Cross section opens again (since 1.16.74 picking it from the Tools tab went back to the menu). Its Options have a
  Mode: Manual (each shot by hand, the default) or Timer (the continuous sweep, 30 s to start).
- NEW Tools > Lineplot assistant: your survey's linked legs drawn on the sketch sheet, page by page, with a check-your-book
  table first, a 10 ft margin either side of each station, North left or top, and splays from any station.
- FIX: pressing the unit's button while it was plugged in with Topside open could freeze it (the screen could change colours).
- FIX: settings saved blank (no angles on any shot) now put themselves right at start-up (CALIBRATION RESET).
Topside:
- Updates and Upgrades > Tacheo > "Force update mode": puts the plugged-in Tacheo in update mode without its reset button
  (a frozen unit too). Then "Install on the unit in update mode" asks which unit it is, so any build can go on it.
- In that question "Tacheo 1, colour screen" is first and highlighted (Enter picks it).
- Builder's computer only (Build a unit): "Install the LCD firmware" puts the colour screen's firmware on a new unit in one
  click - a XIAO straight from the bag, one in update mode, or one given the black-and-white screen's build.

NEW IN 1.6.46 - unit firmware: Tacheo 1 with the colour screen 1.16.75 (Tacheo 1 with the OLED 1.16.73, SAP6 1.16.30 and
SAP5 2.2.16 unchanged). Nothing else changes in Topside.
- The off-drain finder. Units lose a few mA switched off, where it should be microamps. 1.16.75 records why on every unit,
  and changes nothing you see or do:
  - each wake from fully off, also those that find no double-click and go straight back off, with the pin that woke it;
  - every pin's state as the unit is switched off and as it goes fully off;
  - how much of standby the processor is awake (measured for 10 s, a minute in, off USB).
  Going fully off now also lets go of every plain input pin.
- Testers: switch the unit off and leave it off overnight (or longer), then switch it on, plug it into Topside and send a
  Diagnosis report (Diagnosis > Check the Tacheo > Send to Sully).
- Coming from 1.16.72 or older: after installing, do a Normal calibration (see 1.6.45 below).

NEW IN 1.6.45 - unit firmware: Tacheo 1 with the OLED 1.16.73, Tacheo 1 with the colour screen 1.16.74 (SAP6 1.16.30 and
SAP5 2.2.16 unchanged). Nothing else changes in Topside.
- AFTER INSTALLING 1.16.73 or 1.16.74 ON A UNIT, DO A NORMAL CALIBRATION. The compass is now read with things switched off
  that were running during the old calibration, so the old offsets no longer match. Until you do, the unit shows RECALIBRATE
  at start-up (any press skips it).
- Quiet compass reads: Bluetooth advertising and scanning pause for every compass reading (a connected phone or partner stays
  connected); for held legs, phone / Sketch shots and calibration holds the laser's regulator is switched off too.
- A held leg reads its 12 compass samples, then keeps reading until the average settles (0.05 deg), up to 50 samples or 1.5 s.
- Noise test (Tacheo 1 with the OLED: Info > Noise test; colour screen: Device > SENSORS > Noise test). Set the unit down and
  let go. Testers: run it once at home and once in the cave and send the report from Topside.
- Cross sections: one tap per aimed shot, and every shot that passes its check is kept (no outlier rule).
- Colour screen only: Tools > Temperature, after Live tape - the chip's temperature (the one to go by), the tilt sensor's,
  the temperature at the last calibration and how far it has moved since (green within 5 C, orange to 15 C, red past 15 C,
  where every shot carries TEMP). The page keeps the unit on for 30 minutes so you can watch it settle.
- Colour screen only (1.16.72): USB command FSFORMAT, for a unit whose saves all fail.

NEW IN 1.6.44 (everything since 1.6.33) - unit firmware: Tacheo 1 with the OLED 1.16.64, Tacheo 1 with the colour
screen 1.16.70, SAP6 1.16.30; SAP5 firmware 2.2.16
- Survey is a main section of the left menu, under Overview: Shots, Cross sections, Survey performance and Reckon.
- Cross sections (Tools > Cross section on the unit) download with the shots into Shot downloads\<unit>\Cross sections\:
  a .csv of every reading and an .svg ready for a map - the outline to scale (1 in = 20 ft unless the unit says another),
  real size, the height bar on its left and the station's name under it. The outline is 1 px in Illustrator, the bar 0.54 pt,
  Arial 7 pt; the groups outline, scale-bar and station come in as layers. Survey > Cross sections lists every section saved
  on this computer, with or without a unit plugged in, and shows each on its field-book sheet with every reading.
- The Tacheo 1 with the colour screen has its own firmware (the cavec build). Plugged in and running, every unit is offered
  only its own build. A unit in update mode: pick "Tacheo 1, colour screen" for it ("Cave unit" is the Tacheo 1 with the
  black-and-white OLED).
- Check the Tacheo (Help > Diagnosis) reads the unit's usage log and sums it up in the report; the trip log flags a
  CrossTalk link that keeps dropping and says why each link dropped.
- Unit firmware: Tacheo 1 with the OLED 1.16.64 - a gentler power-up for the screen and compass, against the static some
  units showed at start-up; cross sections are shot by hand (SHOT for each wall, hold SHOT to finish). Tacheo 1 with the
  colour screen 1.16.70 - the start-up animation plays, the screen's power is drained before every switch-on so it resets
  cleanly, and 8 quick taps restart a blank or scrambled screen without switching off. SAP6 1.16.30 (its last) - a
  calibration of 0.10 or better ends on a GOLD page. What each one changes is in the .txt beside its zip in firmware\;
  update on Updates and Upgrades > Tacheo (or SAP6).

NEW IN 1.6.33 - unit firmware 1.16.12 (Tacheo and SAP6) and SAP5 firmware 2.2.16
- Tools > Sketch: every shot leaves a small solid square (2 x 2 pixels) where its line ends. The square stays when you clear
  the line, so the features you shoot from a station build up on the page, each where it lies. Options > Clear squares
  clears them (it asks first).
- The Tools menu is in a new order: Sketch, Field meter, Strike & dip, then the rest. Depth is now called Elevation (the
  same tool). Turnaround is gone.
- SAP5 firmware 2.2.16 (Updates and Upgrades > SAP5 > Update this SAP5): the same Sketch squares, Tools order and Elevation,
  plus the charge screen - on USB the Timeout shows a dim battery bar with the % and the battery's LIFE and charge cycles
  instead of turning the SAP5 off (off when unplugged, or 10 minutes after it is charged).
- Update a Tacheo or SAP6 on Updates and Upgrades (Tacheo or SAP6 tab).

NEW IN 1.6.32 - unit firmware 1.16.9 (Tacheo and SAP6)
- The SAP5 update is inside Topside: switch the SAP5 off, plug it in, then Updates and Upgrades > SAP5 > "Update this SAP5".
  Topside reads it, says what it has and what is kept (settings, calibration, health log, owner name), saves a backup,
  installs the firmware and checks every byte - about a minute, no browser needed. "Open the upgrader page" still opens the
  web-page version (the one you can send to a friend).
- Firmware 1.16.9 (Tacheo and SAP6): charging while switched off, the screen shows a big battery bar with the % under it
  (a lightning bolt while it charges) and the battery's life left and charge cycles. It is dim and moves a little each
  minute. Charged: 100 % for 10 minutes, then dark (a press shows it again). Unplugged: dark at once, and fully off after
  2 hours as before; a unit plugged in while fully off wakes quietly into the charge screen and goes fully off again when
  unplugged. Update it on Updates and Upgrades (Tacheo or SAP6 tab).
- Battery life left = the smaller of 300 charge cycles and the cell's health from how long a charge takes (the first
  charge after the update is the 100 % reference).
- Fixed: on Diagnosis, one check at a time; the SAP6 Upgrade card says that converting replaces Phil's files on the SAP6's
  drive (the backup is their only copy).

NEW IN 1.6.29
- Reckon (survey correction), at the bottom of the left menu: drop a Walls survey - .srv files, or a whole cave's .wpj
  project - anywhere on Topside (or click "Open .wpj / .srv"). It finds slips of the pen (swapped digits, 180 off, a dropped
  minus sign), legs shot the wrong way round at junctions, wrong or missing declinations, backsight settings that don't
  match the book, a steady FS/BS split between two instruments, a clino index error, and - from your Tacheo shot downloads
  - each calibration's own small error. Problem numbers are boxed in red (amber = check the book), you can edit numbers in
  the table, and "Apply ... fixes" writes a corrected copy ("<name> corrected.srv", or a corrected copy of the whole project).
  Your original files are never changed unless you click "Save my edits" (a backup is kept first).
- The left menu in groups that drop down when you rest the mouse on them (Devices: Devices, Shots, Calibration, Survey
  performance, Manuals; Settings: Settings, Owner; Updates: Updates and Upgrades, Test new firmware; Help: Help and how-to,
  Diagnosis, Suggestions), with Reckon below a line.
- Help: "Search help" at the top of the left menu (or F1 anywhere) answers questions about Topside as you type. Each answer
  has "Go there", and "Show me" walks you through it on the screen, outlining each button. Help and how-to lists every topic.
- Shot downloads (.csv) have two more columns: spread_deg and health (the unit's steadiness and sensor warnings per shot).
- FIX: double-clicking the Calibration column on the Shots page opens that calibration.

NEW IN 1.6.28
- Devices > a unit > Shots shows your surveys by day (find a station such as FSB123, or a series), each with the calibration
  it was shot with, its backsights' compass error and every shot.
- Click any calibration ID for everything about it: the magnetic field and dip it saw, its figures, each hold, the
  calibration before it and how far the two differ in bearing, the surveys shot with it, the correction and the raw holds.

NEW IN 1.6.27
- Test new firmware (the last page in the list): try unit firmware that hasn't been released yet on your own unit - if you
  are not Sully, at your own risk. Start the test, use the unit as long as you like, then Finish and save: Topside writes
  what it saw to "Firmware tests\" next to it. A SAP5 works too (read while it is off and plugged in, before and after).
- Diagnosis > Check a BRIC (its card drive, read only). The Beta test page is now part of Diagnosis: the trip log is at the
  bottom; Check the Tacheo, then Send to Sully.
- Unit firmware 1.16.7 (Tacheo and SAP6): Tools > Sketch - the bearing scale numbered at N, 90, 180 and 270 only; beside the
  page the azimuth, Dist (the distance as shot) and HD (the horizontal distance); the Draw line is gone.
- SAP5 firmware 2.2.12 (in sap5\): the same Sketch change, plus 2.2.11's Sketch, Live tape, Depth, Strike & dip and battery %.

NEW IN 1.6.25
- Nothing changes on your computer. On Sully's PC only: new unit firmware is now tried on his own units (a real
  restart and a self-test) before it is released to anyone. Unit firmware unchanged (1.16.6).

NEW IN 1.6.24 - unit firmware 1.16.6 (Tacheo and SAP6)
- FIX: firmware 1.16.5 crashed every time it started, so a unit updated to it stays dark and the computer doesn't see it.
  To bring it back: plug it in, press the XIAO's reset button twice quickly (like a fast double-click) - its LED pulses
  and a drive called XIAO-SENSE appears - then Updates and Upgrades > SAP6 (or Tacheo) > "Install on the unit in update
  mode". Do not install 1.16.5 again.

NEW IN 1.6.23 - unit firmware 1.16.5 (Tacheo and SAP6)
- One battery percentage everywhere: READY, the charge screen, Info > Battery and Topside show the same figure. On
  battery it only goes down, so it no longer reads 75 % straight after unplugging and then falls to 55 %. A full charge
  reads 100 %: the unit learns what its battery reads when full (Info > Battery, "Full").
- Calibration resume: if the unit freezes or crashes in a calibration, it keeps the holds you took and asks to carry on
  from the next one after the restart.
- If the unit ever freezes, it now records where it was stuck. Send the Topside report to Sully.
- FIX: a laser reply that never ended could freeze the unit until the safety restart.
- The screen starts the right-hand way, with the buttons on the right of the picture. Units on the old default turn
  round once; Settings > Screen reads Right hand / Left hand.
- Survey performance > Statistics to date: the Footage card's big figure is now your average footage a trip.

NEW IN 1.6.22 - unit firmware 1.16.4 (Tacheo and SAP6)
- The battery percentage while charging is honest now: it starts where it was on battery when you plug in and only
  goes up, so it no longer drops 10-15 % within a minute of unplugging (the SAP6's charger lifts the voltage ~0.15 V).
- Tools > Sketch: the scale is feet to the inch, as on a cave sketch (1 in = 20 ft by default, 5 to 100 ft in the
  options). A 14 ft shot at 1 in = 20 ft draws 0.7 in, inside one grid square. "Draw" is in inches. No scale or button
  hints on the page.
- The button hints ("2:next", "1 = leave" ...) are gone from menus, lists, tools and questions. They stay on the
  calibration screens and in the tutorial (Menu > Tutorial).

NEW IN 1.6.21 - unit firmware 1.16.3 (Tacheo and SAP6)
- Trip review is now SURVEY PERFORMANCE, and it opens on a new STATISTICS TO DATE tab: the average of all your trips -
  the time between shots (with your best, average and last trip, and whether you are getting faster), the FS/BS
  agreement over every backsight, footage and feet per hour, the average trip, personal bests and trip-by-trip charts.
  Pick one unit or All units. Each trip is on the TRIPS tab, as before.
- Firmware 1.16.3, Tools > Sketch: shots taken while moving are kept, the screen doesn't turn over, the page is shaped
  like a Rite in the Rain survey sheet with a dotted 1-inch grid and a bearing scale round the edge, one line from the
  station (1 clears it), and Exit Sketch in the options (2).
- SAP6 running Tacheo: firmware 1.16.3 keeps the shots and logs on the XIAO's 2 MB flash chip, as the Tacheo does (the
  newest 10,000-20,000 shots, was 200-400; existing ones are moved across). That chip held Phil Underwood's original
  files, which are replaced: Topside backed them up when it converted the unit ("SAP6 backups"), and that backup is
  what you copy back if you ever return the SAP6 to Phil's firmware.

NEW IN 1.6.20 - unit firmware 1.16.2 (Tacheo and SAP6)
- Tools > Sketch: the screen becomes a sketch page (always sideways). Press 1 to light the laser, press 1 again for an
  instant shot: a line from the centre of the page along the azimuth, to scale (1:20; 1:10 to 1:500 in the options),
  labelled with the horizontal distance; the bottom row says how long to draw it on paper. North on any side of the page
  (left by default). 2 = options (scale, North side, undo, clear), hold 2 = out.
- READY is cleaner: no "1: tap LRUD / hold shot", "2: menu" or "Laser on / off" lines.

NEW IN 1.6.19 - unit firmware 1.16.1 (Tacheo and SAP6)
- READY shows the battery percentage under the battery symbol, always known at a glance, also while charging
  (under CHG; it stops at 99 % until the charger says it is done).

NEW IN 1.6.18 - unit firmware 1.16.0
- SAP6: if yours is on firmware older than 1.14.2, update it (Updates and Upgrades > SAP6 > Updates): it then switches
  itself fully off 2 hours after you turn it off, so the battery no longer runs down while it's put away.
- Tacheo cave units: shots and logs move to the XIAO's 2 MB flash chip (the newest 10,000-20,000 shots are kept; your
  existing shots are moved across at the first start); the buzzer no longer hums between beeps; the lit SHOT button.
- Topside: the breadboard Tacheo option is gone, and the firmware folder is read again before every install.

NEW IN 1.6.17
- The credit line now reads "by Phillip Sullivan (Sully)".

NEW IN 1.6.16 - unit firmware 1.15.1 (Tacheo and SAP6)
- The Crosscheck pair page shows your own shot in big figures, as every result screen does: distance, azimuth,
  inclination. On the right of each, small: the other unit's reading with its role, and under it BS minus FS, inverted
  when out of tolerance. The Tacheo and SAP6 manuals are updated for 1.15.1.

NEW IN 1.6.15 - unit firmware 1.15.0 (Tacheo and SAP6)
- Crosscheck pair page: once a shot is paired with the other unit's, the result screen shows the FS shot and the BS shot
  (azimuth, inclination, distance) and, in big figures, how far they are from a perfect foresight/backsight: azimuth
  BS - (FS + 180), inclination BS + FS, distance BS - FS. A figure out of tolerance is inverted; the bottom line says
  Good or Check azimuth / clino / distance. READY shows the pair for 15 seconds, agreeing or not.
- Menu > Pairing > Role: Auto, FS or BS - which end of each leg the unit shoots. Set it on one unit and the other Tacheo
  takes the other role. Settings page > Crosscheck role sets it from Topside too. Update both units of a team.
- FIX: the other unit's first shot of the next leg was compared with your shot of the leg before (a wild Check). Two new
  shots are still always compared.
- The Tacheo and SAP6 manuals are updated for 1.15.0. SAP5 firmware unchanged (2.2.10).

NEW IN 1.6.14 - unit firmware 1.14.2 (Tacheo and SAP6) and SAP5 firmware 2.2.10
- FIX: switching a Tacheo or SAP6 on from standby restarted it once every time (since firmware 1.12.0): the start-up
  screen came twice and the second calibration screen was upside down. Firmware 1.14.2 starts once, and its start-up
  screens follow Autoflip. Update with Updates and Upgrades > Tacheo (or > SAP6 > Updates).
- Fully off: 2 hours after it is switched off the unit now switches itself fully off and draws almost nothing, so the
  battery no longer runs down while it is put away. Double-click turns it on as always (a moment slower; it starts
  afresh, so Topside sets its clock again when it is next plugged in), and plugging in USB also turns it on. Not while it
  is plugged into USB or has a turnaround alarm set.
- A survey ends after 2 hours with no shot (was 4 hours), on the unit and in Trip review.
- The full report and Devices > Trips and events show each time the unit was switched off: how long, the battery
  before and after, and whether it went fully off; the report says if the battery runs down while switched off.
- SAP5 firmware 2.2.10: the start-up pages turn over with the unit (Autoflip), like every other screen.
- The Tacheo and SAP6 manuals are updated for 1.14.2.

NEW IN 1.6.13
- Every Tacheo gets only its own firmware build. The Tacheo's own cave units (v1.5 / v2) will run a "cave" build
  (firmware 1.14.1 and later), which switches on their screen, compass and laser; Topside never offers them the
  breadboard build. This Topside doesn't carry the cave build yet. A unit in update mode, or one that doesn't answer,
  can't say which it is: Topside (and "Update firmware only.cmd") now asks first. SAP6 and SAP5 updates are unchanged.
- Unit firmware is the same as 1.6.12 (Tacheo and SAP6 1.14.0, SAP5 2.2.9).

NEW IN 1.6.12 - unit firmware 1.14.0
- Crosscheck with other instruments: on the Tacheo, Menu > Pairing > Other instr. finds a BRIC4/5, Cavway X1, Disto XBLE,
  SAP6 (Phil's firmware) or SAP5 nearby (switched on, not linked to a phone), connects to it and checks its shots against
  yours, as with a second Tacheo: the backsight check, its shot under DEV 2, Leg track's pairs. Its splays are left out.
  Shots it had waiting are skipped and count as sent: download them to its own app first. A DistoX2 / A3 can't be read
  (classic Bluetooth).
- The phone link (SexyTopo, TopoDroid) now takes the acknowledgement those apps send.
- Update the unit on Updates and Upgrades. The Tacheo and SAP6 manuals are for firmware 1.14.0.

NEW IN 1.6.11
- The compass checks are on the Diagnosis page now: "Bearings drifting?" - Check for metal and drift, and Find the magnet
  (they were on the Calibration page). The Tacheo and SAP6 manuals say so, and describe Find the magnet.

NEW IN 1.6.10
- "Find the magnet" (unit firmware 1.13.1, by USB; on the Diagnosis page since 1.6.11): for bearings that drift days after a calibration.
  SPIN TEST - turn the unit every way for 40 s away from steel: how far its own magnetism has moved since the calibration,
  kept day by day, so you can see whether it grows, settles or jumps (and test storing it away from other instruments).
  GUIDED PART TEST - about 3 minutes with an ordinary fridge magnet (not a neodymium one): finds which part of the unit holds
  magnetism and says what to do about it; recalibrate afterwards. LIVE METER - the change from a still baseline.
  Send the results to Sully from the Diagnosis page.
- Firmware 1.13.1 for the Tacheo and for SAP6s running Tacheo: adds the quick compass reading Find the magnet uses; nothing
  else changes. Update the unit on Updates and Upgrades (or with "Update firmware only.cmd").

NEW IN 1.6.9
- "Check for metal and drift" (Diagnosis page since 1.6.11): finds metal near the unit during a calibration, tells whether the compass's own
  magnetism has changed since (the usual reason bearings drift a few degrees days after a good calibration), and how far
  marks shot again - a home course - have moved. Send the result to Sully from the Diagnosis page.
- Manuals: the Tacheo and SAP6 manuals for firmware 1.13.0 (station names, the Stations menu, End survey, storage),
  and a new manual for the DistoX2 / Disto XBLE running Tacheo's own firmware (a test version).
- A DistoX2 or Disto XBLE running Tacheo's own firmware is recognised: its firmware shows as "Tacheo <version>",
  and Diagnosis > Check a DistoX adds that firmware's figures (calibration, last Check, backsights, restarts) and
  its trip log. Still read only.

NEW IN 1.6.8
- Disto XBLE (CaveDevice's DistoX2 board on Bluetooth LE): Devices > Read a device > "Find and read the XBLE" - no
  pairing in Windows. Its report, calibration, calibration mode off and firmware backup work as for the DistoX2.
- Fixed: the DistoX firmware backup called a real DistoX2's layout "no program found" (the backup was complete).

NEW IN 1.6.7
- One full report: the Beta test page and Diagnosis > Check the Tacheo now send the same report - the self-test, the
  trip log, the calibration and its records, the storage, station names, trips, every stored shot and this computer's
  history of the unit.
- Diagnosis > Check a DistoX: a report on a DistoX (read only, by Bluetooth) - firmware and board, calibration and how
  well its last calibration run fits it, modes, unsent shots, every shot.
- Devices > the DistoX > Back up its firmware: a copy of the DistoX's whole memory on this computer, read in its
  installer mode (hold PLUS and MINUS, press DIST). Nothing on the DistoX is changed.

NEW IN 1.6.6
- Trip review: on a smaller window the text no longer runs off the cards (the shot-rhythm key wraps
  onto a second line; long lines are shortened).
- DistoX: works with the DistoX2 (X310) and the original A3 over their Bluetooth serial port. The
  newer Disto XBLE kit (Bluetooth LE) can't be read yet.

NEW IN 1.6.5
- Tacheo firmware 1.13.0, for the Tacheo and for SAP6s running Tacheo (Updates and Upgrades >
  Tacheo / SAP6). Station names: with Settings > Leg track On every shot gets a FROM and TO
  station, named the way the book has them (A12 to A13). Hold MENU on the ready screen or a
  result for the new Stations menu: Side lead (a new series off this one - off A it is AA, then
  AB), fix a shot taken for the wrong thing, move the station number, and End survey (footage,
  time, feet per hour and time between shots; 4 hours with no shot starts a new survey too).
  At 95 % full the unit makes room by itself, oldest logs first; the calibration and settings
  are never touched.
- Shots > "Stations": type the trip's designators (A, B, SC ...) and send them to the unit.
  Downloads carry the unit's station names.
- Devices: one page for every instrument (the SAP5 and SAP6 pages are now "SAP5 tools" and
  "SAP6 tools" on that unit's page). Saved devices in a drop-down; Read a device.
- Other instruments, read only (their own firmware is never changed): a Cavway X1 and a BRIC4 /
  BRIC5 by USB, a DistoX / DistoX2 by Bluetooth (it has no USB data port). Shots, calibration
  status, trips and footage. A Cavway's clock can be set; a DistoX can be calibrated in Topside,
  without TopoDroid (56 shots; the old calibration is saved first and can be put back).
- Trip review (new page): how each trip went - the time between shots first, then the FS/BS
  agreement, then the footage; waits counted, breaks (unit switched off) left out; a next-trip
  estimate. The Overview's FOOTAGE tile: footage last trip and average per trip.
- Storage: click the Overview's Storage tile to see what is on the unit and clear what the
  calibration does not need (saved on this computer first). Warns from 88 %.
- Restart check: each kind of unexpected restart is listed once, with how many times and its cause
  (reset button, lost power, software restart, or the freeze / crash firmware 1.12.1 records).
- The manuals are still those for firmware 1.12.1 (the Stations menu is described above and in
  README.txt).

NEW IN 1.6.4
- Tacheo firmware 1.12.1, for the Tacheo and for SAP6s running Tacheo (Updates and Upgrades >
  Tacheo / SAP6). If the unit crashes it now restarts by itself instead of going dark, and says
  RESTARTED; if it freezes for 20 seconds it restarts too. Shots, settings and the calibration
  are kept. During a Precision calibration it notes its progress, battery and temperature every
  30 seconds, so a problem can be traced.
- Restart check: when a unit that crashed, froze or restarted without being turned off is
  plugged in, Topside says so and offers the beta-test report (it shows where the unit stopped).
- Storage: the Overview shows how full the unit's memory is. From 95 % Topside offers to clear
  the logs. Shots > "Clear logs" saves new shots and the trip log on this computer first, then
  empties the unit's shot log and trip log; the calibration, its records and the settings stay.
- Diagnosis report: shows the storage, and counts unlabelled shots on their own (they were
  counted as LRUDs).
- Manuals for firmware 1.12.1 (Manuals page).

NEW IN 1.6.2
- Tacheo firmware 1.11.1, for the Tacheo and for SAP6s running Tacheo (Updates and Upgrades >
  Tacheo / SAP6). New tools: Rigging (a pitch's drop and the rope it needs), Live tape, a
  Turnaround alarm (calls every 2 minutes when due, even switched off) and Strike & dip.
- Settings > Leg track on the unit (Off by default): it follows the survey leg by leg, on one
  unit or a Crosscheck pair, for Tools > Depth (depth and distance from a zero station) and
  loop closures: within 1 ft it chimes; worse, it names the leg most likely to be wrong and the
  leg with the worst FS/BS agreement. The distance decides whether a shot is the same leg again,
  a redo, a backsight or a new leg.
- Fixed: a unit with Settings > Bluetooth > Phone link and Crosscheck detection both Off froze
  at READY on every start (buttons dead, not seen on USB). If yours does: press the reset button
  twice quickly (update mode), then install 1.11.1 from Updates and Upgrades in this Topside.
- Fixed: backing out of a tool shot (Rigging, Point to point, Benchmark) or leaving Live tape
  left the laser dot on over the menus.
- Manuals for firmware 1.11.1 (Manuals page), with the new tools.

NEW IN 1.6.0
- Devices page (under Overview): every Tacheo, SAP6 and SAP5 this computer has seen, with its
  history, built up by itself each time a unit connects: Summary, Shots (every download merged),
  Calibrations, Trips and events (one row per power-on from the trip log), Usage (one row per
  connection). "Full history of this unit" on the Shots and Calibration pages opens it.
- A SAP5 plugged in (switched off) shows on the Overview by itself: firmware, owner, serial
  number, calibration ID, and its clock.
- SAP5 firmware 2.2.9 (Updates and Upgrades > SAP5): Info opens on a Device info page (owner,
  serial number, calibration ID, firmware, clock), the raw numbers moved to Info > Raw data, and
  the clock is set from this computer.

NEW IN 1.5.8
- Bluetooth works: Topside 1.2-1.5.7 said "Bluetooth needs Windows 10 or 11" on every Windows 10
  and 11 computer, so it never looked for the unit. Fixed. There is no pairing in Windows'
  Bluetooth settings: click "Bluetooth" in Topside and pick the unit.
- EXCELLENT, above GOOD, in gold with a star (Calibration page, Overview, calibration records): a
  calibration under 0.15 deg, or the FS/BS agreement averaging under 0.20 deg over 5+ pairs.
- A green "Up to date" bar on Updates and Upgrades when the unit already has the newest firmware.
- Tacheo firmware 1.10.5 (Tacheo and SAP6 builds): LRUD shots read straight away (the laser starts
  when the button goes down); EXCELLENT on the unit's screens; legs keep their beep on time when
  the laser is slow. Printable manuals updated to 1.10.5.

NEW IN 1.5.7
- Manuals: the printable manuals have their own page, last in the list on the left (they
  were at the bottom of each Updates and Upgrades tab). The one for the connected unit is
  marked.
- Calibration recognises the unit by itself: a Tacheo, a SAP6 (running Tacheo or on Phil's
  firmware) or a SAP5 / Tacheo-SAP5 (switched OFF, then plugged in), and shows its calibration
  and health.
- Several units at once: every Tacheo plugged in by USB connects, and more can be added by
  Bluetooth. A "Units:" row under the top bar picks which one the pages show. Shots >
  "Download from all units" saves the new shots of all of them in one go, each in its own
  folder, plus one spreadsheet for the pair ("Shot downloads\Pair <date time>.csv").
  Firmware installs go only to the unit picked; other Tacheos can stay plugged in.

NEW IN 1.5.6
- Printable instruction manuals: each tab of Updates and Upgrades (Tacheo, SAP6, SAP5) has
  that unit's manual as a PDF, with pictures of the screens - open it, print it, or show it
  in the "manuals" folder.
- Tacheo-SAP5 2.2.8 (the SAP5 upgrader in the SAP5 tab): calibration holds now work as on
  the Tacheo - each hold waits for your click, then a 3-second countdown with your hand off
  the button. Holding the button for 1 second asks "Exit cal?" instead of a stray press
  throwing the calibration away.

NEW IN 1.5.5
- Calibration records (with Tacheo firmware 1.10.4, included): every calibration has an ID -
  the serial number and a number, e.g. TCH-5D8413F6-C008 - and every shot carries the ID it
  was taken with (shot downloads). The Calibration page lists them; Topside keeps each record
  (its figures, the correction it applies, the raw holds) in "Calibration records", with one
  spreadsheet per instrument and one for all instruments, so instruments and calibrations
  can be compared.

NEW IN 1.5.4
- Overview: when a newer Topside is out, an UPDATE AVAILABLE card at the top shows the new
  version and what's in it - each change tagged TOPSIDE, TACHEO, SAP6 or SAP5, any newer
  unit firmware inside it, and a note when the plugged-in unit would get newer firmware -
  with a large "Install update now" button and the progress on the card.

NEW IN 1.5.3
- Tacheo firmware 1.10.3 (Tacheo and SAP6 builds): fixes a calibration that could "collapse"
  so every shot read the same compass and clino whichever way the unit pointed. Holds taken
  next to metal or electronics are now named (COMPASS DISTURBED) and can be retaken or left
  out; a collapsed calibration is thrown away at start-up (CALIBRATION RESET - calibrate again,
  away from metal). Start-up screen 4 s with "by Sully", health screen 4 s.
- Tacheo-SAP5 2.2.7 upgrader: start-up screen 4 s with "by Sully", health screen 4 s.

NEW IN 1.5.2
- Updates and Upgrades has a tab for each kind of unit: Tacheo, SAP6 (Updates and Upgrade),
  SAP5, and Topside itself. It opens on the tab for the unit plugged in; no more "Which unit
  is it?" question.
- Tacheo firmware 1.10.2 (Tacheo and SAP6 builds): fixes calibration freezing on "Computing
  the calibration..." (it now shows a progress bar and the time left); calibration points are
  taken with a 3-second timer after pressing 1 (no holding the button); the laser stays off
  after switching on until 1 is pressed; feet by default.
- Fixed: a firmware update could stop with "Could not open COM.." just as the unit switched
  to update mode (the update now carries on).

NEW IN 1.5 / 1.5.1
- Updates and Upgrades page (was Updates): Tacheo firmware 1.10.1, the SAP6 upgrade
  (convert Phil's SAP6 to Tacheo, or put his firmware back), and the Tacheo-SAP5 2.2.6
  upgrader. Every install writes a step-by-step log in "Update logs".
- SAP6 page: health, settings and backups for a SAP6, on Phil's firmware or running Tacheo.
- Diagnosis: "Check a SAP6". Suggestions: a SAP6 topic.
- Settings: "Shot hold" (how long to hold the shot button, 1.5 to 5 s; firmware 1.10.1).
- Fixed: the Update button didn't respond after a unit connected.

WHAT'S IN IT
- Overview, Devices (Tacheo, SAP6, SAP5, DistoX, Cavway, BRIC), Trip review, Shots (download as
  .csv and Survex .svx), Calibration, Beta test, Owner, Settings, Updates and Upgrades,
  Diagnosis, Suggestions, Manuals.
- Tacheo firmware 1.13.0 is included (Tacheo and SAP6 builds): Updates and Upgrades >
  Tacheo, or SAP6 > Updates (by cable). Settings, calibration and stored shots are kept.

CONVERTING A SAP6: Updates and Upgrades > SAP6 > Upgrade > "Convert this SAP6 to Tacheo".
It backs up the SAP6's drive first and can be undone. Then calibrate with Tacheo:
Menu > Calibrate > Normal > All sensors, then Menu > Calibrate > Check.

BETA TESTERS: after every trip, connect the Tacheo, open the Beta test page, write how the
trip went and click "Send beta-test report". Thank you!

The full description of every page is in README.txt inside the folder.
Questions: Sully, p0sull02@gmail.com
