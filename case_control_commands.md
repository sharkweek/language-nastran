# Case Control Statements
The following are case control commands for result output results from Nastran
2016. All case control commands shown here are taken from the Nastran 2016
Quick Reference Guide (QRG) Revision 0, April 26, 2016.

## Subcase Definition
### Output Request Delimiters
    ENDCARDS
    OUTPUT
    SETS DEFINITION

### Subcase Delimiters
    REPCASE
    SUBCASE
    SUBCOM
    SYM
    SYMCOM

### Subcase Control
    MASTER
    MODES
    SUBSEQ
    SYMSEQ

## Data Selection
### Static Load Selection
    DEFORM
    CLOAD
    LOAD
    LOADNAME

### Dynamic Load Selection
    DLOAD
    LOADSET
    NONLINEAR

### Constant Selection
    AXISYMMETRIC
    AUTOSPC
    BC
    DSYM
    MPC
    SPC
    STATSUB
    SUPORT1

### Thermal Field Selection
    TEMPERATURE
    TSTRU

### Static Solution Conditions
    SMETHOD

### Dynamic Solution Conditions
    CMETHOD
    FREQUENCY
    FRF
    IC
    METHOD
    MODESELECT
    NSM
    RANDOM
    RESVEC
    RGYRO
    SDAMPING
    SMETHOD
    TSTEP

### Direct Input Matrix Selections
    A2GG
    B2GG
    B2PP
    K2GG
    K2PP
    K42GG
    M2GG
    M2PP
    MFLUID
    P2G
    TFL

### Nonlinear Analysis
    ENDSTEP
    ENDTIME
    NLHARM
    NLOPRM
    NLPARM
    SMETHOD
    STEP
    TSTEPNL

### Aerodynamic Analysis
    AECONFIG
    AESYMXY
    AESYMXZ
    AEUXREF
    CSSCHD
    DIVERG
    FMETHOD
    GUST
    TRIM

### Design Sensitivity and Optimization (SOL 200)
    ANALYSIS
    AUXCASE
    AUXMODEL
    DESGLB
    DESMOD
    DESOBJ
    DESSUB
    DESVAR
    DRSPAN
    DSAPRT
    MODTRAK

### p-Element and p-Adaptivity Analysis
    ADAPT
    DATAREC
    OUTRCV
    SET
    SETS DEFINITION
    VUGRID

### Adaptive Meshing
    HADAPT

### Fluid-Structure Analysis
    A2GG
    ACFPMRESULT
    ACPOWER
    FLSFSEL
    FLSPOUT
    FLSTCNT
    INTENSITY
    TRIMGRP

### Nastran/ADAMS Interface
    ADAMSMNF

### Contact
    BCHANGE
    BCMOVE
    BCONTACT
    BOUTPUT
    BSQUEAL*
    UNGLUE

\* Used in Bulk Data Miscellaneous section also (primary)

## Output Selection
### Output Control
    ECHO*
    ECHOOFF
    ECHOON
    LABEL
    LINE
    MAXLINES
    PAGE
    PLOTID
    POST
    SKIP
    SKIPON
    SKIPOFF
    SUBTITLE
    TITLE

\* Used in Executive Control section also (primary)

### Set Definition
    MAXMIN
    OFREQUENCY
    OMODES
    OTIME
    PARTN
    SET
    SURFACE
    VOLUME

### Physical Set Output Requests
    ACCELERATION
    BOUTPUT
    CMSENRGY
    DISPLACEMENT
    VECTOR
    PRESSURE
    EDE
    EKE
    ELSDCON
    ENTHALPY
    ESE
    EQUILIBRIUM
    FATIGUE
    FLUX
    FORCE
    ELFORCE
    GPFORCE
    GPKE
    GPSDCON
    GPSTRAIN
    GPSTRESS
    GVECTOR
    HDOT
    HISTOGRAM
    MCFRACTION
    MODALKE
    MODALSE
    MEFFMASS
    MPCFORCES
    NLSTRESS
    NOUTPUT
    OLOAD
    RCROSS
    SPCFORCES
    STRAIN
    STRESS
    ELSTRESS
    STRFIELD
    THERMAL
    VELOCITY

### Solution Set Output Requests
    AEROF
    APRESSURE
    HARMONICS
    HOUTPUT
    MPRES
    NLLOAD
    SACCELERATION
    SDISPLACEMENT
    SVECTOR
    SVELOCITY
    TRIMF

### Model Checkout
    ELSUM
    GROUNDCHECK
    WEIGHTCHECK

## Superelement Control
    EXTSEOUT
    SEALL
    SEDR
    SEDV
    SEEXCLUDE
    SEFINAL
    SEKREDUCE
    SELGENERATE
    SELREDUCE
    SEMGENERATE
    SEMREDUCE
    SERESP
    SUPER

## Miscellaneous
    BEGIN BULK
    END BULK
    INCLUDE
    NSM
    PARAM
    POST
    RIGID
