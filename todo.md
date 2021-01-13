# List of things we have to do

Code                  |Set at    | Label                       | Comment           | Prequisities | Status
----------------------|----------|-----------------------------|-------------------|--------------|-------
[13012101](#13012101) | 13/01/21 | SQL Server                  |                   |              | [ ]
[13012102](#13012102) | 13/01/21 | Apache Server               |                   |              | [ ]
[13012103](#13012103) | 13/01/21 | Processing Server(s)        |                   |              | [ ]
[13012104](#13012104) | 13/01/21 | Redundant Processing Server |                   |              | [ ]
[13012105](#13012105) | 13/01/21 | DSO Website                 |                   | 13012101     | [ ]
[13012106](#13012106) | 13/01/21 | Upgrade Bernese AP          |                   | 13012103     | [ ]
[13012107](#13012107) | 13/01/21 | Test Bernese AP             |                   | 13012106     | [ ]
[13012108](#13012108) | 13/01/21 | Process old data            |                   | 13012107     | [ ]
[13012111](#13012111) | 13/01/21 | Automate SINEX distribution |                   | 13012107     | [ ]
[13012109](#13012109) | 13/01/21 | Time-Series SW              |                   |              | [ ]
[13012110](#13012110) | 13/01/21 | EUREF Velocities WG         |                   | 13012109     | [ ]


## SQL Server <a id="13012101"></a>
Setup an SQLServer for automatic processing

## Apache Server <a id="13012102"></a>
Setup an Apache Server to host DSOs activities

## Processing Server(s) <a id="13012103"></a>
Update/Upgrade Processing Servers | Setup two (clones) processing servers to host automatic processing activities

## Redundant Processing Server <a id="13012104"></a>
Setup one processing server to act a redundant (backup) processing host

## DSO Website <a id="13012105"></a>
Setup DSO processing website (probably Django)

## Upgrade Bernese Automatic Processing <a id="13012106"></a>
Update/Upgrade all automatic processing scripts and programs. All updated routines to be placed in [autobern](https://github.com/DSOlab/autobern.git)

## Test Bernese Automatic Processing <a id="13012107"></a>
Test that the automatic processing works for **final** and **ultra rapid** solutions and for all networks

## Process olda data <a id="13012108"></a>
Process data for years 2019 and 2020 of network "greece"

## TimeSeries Software <a id="13012109"></a>
Design and develop a (python?) time-series software tool

## EUREF Velocities WG <a id="13012110"></a>
Contact the EUREF Velocities Working Group and try to contribute. We need to have velocity estimates for that (as dense as possible). They (Dr. Brockmann) are very interested in [StrainTool](https://github.com/DSOlab/StrainTool.git)

## Automate SINEX distribution <a id="13012111"></a>
Automate the publishing of SINEX files to EUREF Densification WG. E.g. once every two weeks
