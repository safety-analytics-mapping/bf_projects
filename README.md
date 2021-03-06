# Project list to pass off

# Scrap vs documented readme for each individual project folder

## Red light camera report - requires work + parameter changes

-	Directory: E:\RIS\Requests\Citywide\RedLightCameraReport\2021 Report
    - Latest file: RLC Preliminary Analysis 2021.ipynb
    - Ayanthi pointed me to the shared drive directory when adding notes so I’m assuming that is more current than the repo.
-	Repo: https://github.com/safety-analytics-mapping/MiscRequests/tree/master/RLC

- Tasks
    - Manually check camera geometries from latest Signals source file and map to latest lion version.
        - There are cameras that are assigned multiple masterids.
    - Change year parameters
    - Output file is Excel with multiple sheets for Julia Kite.

## BQE Request - requires work + parameter changes
- ~~Directory: \\Dot55fp05\botplan\RIS\Staff Folders\Ayanthi\Requests\Highway Crashes 2021\Automated Tasks\Highway Crashes~~ 
    - ~~Latest file: highway_Month_only.py~~
- Repo: https://github.com/safety-analytics-mapping/MiscRequests/tree/master/BQE_monthly
- Seth updated the file in the repo, so more current than below.
- ~~Ayanthi pointed me to the shared drive directory when adding notes so I’m assuming that is more current than the repo.~~

- Tasks
    - Change month/year parameters, also some hardcoded params in query to change (from Ayanthi's script, might be outdated).
    - Manually check fatal data for crashes within bounding box (+10 ft buffer) to see if they occurred on stretch of BQE for request.  

## Bronx Escooter Request - requires no param changes, weekly email to working group 
- Repo: https://github.com/safety-analytics-mapping/MiscRequests/tree/bx_escooter_crashes/BX%20Escooter%20Crashes
- Tasks
    - Weekly email of excel/graph outputs to group
        - Seth is looped in on them 
    - Future task - limit number of weeks shown on graph 

## VZ Corridor Analysis - required parameter changes
- Directory: E:\RIS\Data\CrashData\RANKING\CLION_Ranking2019\QA\Severity
- Repo: To-do
- Tasks
    - ~~Required inputs (I didn't generate these, but needed for the process)~~
        - ~~VZ priority corridor creation for latest 5 years (16-20)~~
        - ~~_vz_vz_priority_corridors_yr1_yr2.shp~~
    - Don't use injury version of corridors
    - Change labels for outputs, code will still run regardless but outputs need to correspond to correct year range

## Severity Memo Analysis - requires param changes, code cleanup to generate outputs only, archive rest
- Directory: E:\RIS\Staff Folders\Bryant\Severity Memo
- Repo: to-do
- Tasks
    - Change year params at top of notebook
    - Table in memo requires manually updating from outputs in-line in notebook
    - Generate CRASHDATA/vz_priority_corridors_clion_2019_19d_unique for priority corridor analysis to run
    - Currently uses the early version of 2020 NYSDOT data in CRASHDATA, makes sense to keep in place when early version of 2021 data gets updated in that db

## Stop control intersection - required changes TBD
- Repo: https://github.com/safety-analytics-mapping/MiscRequests/tree/stop_control
- Tasks
    - Dates hardcoded for 2017-2021

## Speed camera equity - required changes TBD
- Directory: \\dotbotplan01\BOTPLAN\RIS\Requests\Citywide\Equity Assessment\speed cameras
- Repo: https://github.com/safety-analytics-mapping/speed-cameras (in speed_camera_equity branch for now)
- Tasks
    - Requires NTA table (Arthur knows where/how to create) 
    - State data, will need to transition to NYPD
    - 2014-2018, will need to update that, presumably pre-expansion years used for a specific reason

## PWA - stable for latest version that Signals wanted
- Directory: E:\RIS\Staff Folders\Samuel\Requests\SH\PWA\Code
- Repo: To-do
- This is the latest version I know of, since Sam created the run script that built on top of the crash identification logic that I built and the signal controller script that he built (which should be formalized in ris db now.

## Forms tams comparison - not sure what next steps are
 - Directory: E:\RIS\Staff Folders\Bryant\TAMS FORMS Comparison
 - Repo: To-do
 - This hit a dead end. Overarching working hypothesis is that we can take % change between tams and forms and compare to % change between nysdot and nysdot for same years and see if electronic reporting increased reported injuries/crashes. 

## Driver behavior study 
 - Directory: E:\RIS\Staff Folders\Bryant\Driver behavior
 - Repo: To-do
 - Tasks
    - Update to fit Rob's asks for the report.
- to-do: add comments to notebook 

## Tams remapping
 - Repo: https://github.com/safety-analytics-mapping/tams_remapping
 - Tasks
    - Re-run once each year to go with clion updates. 

## Speed camera code
   - Directory: E:\RIS\Data\SpeedCameras\CODE\PrioritizationCode_Current\Round1
   - To my best knowledge this is the clean version of the code.
 
