# Bulk Data Entries
The following are bulk data entries for MSC Nastran 2016. All items shown here
are taken from the MSC Nastran 2016 Quick Reference Guide (QRG) Revision 0,
April 26 2016.

## Constraints and Partitioning
### Component Mode Boundary Conditions
    BNDFIX
    BNDFIX1
    BNDFREE
    BNDFRE1
    BSET
    BSET1
    CSET
    CSET1
    QSET
    QSET1
    SEBSET
    SEBSET1
    SECSET
    SECSET1
    SENQSET
    SEQSET
    SEQSET1
    SESUP

### Free Body Supports
    CYSUP
    SUPAX
    SUPORT
    SUPORT1
    SUPORT6

### Multipoint Constraints
    MONSUM
    MPC
    MPCADD
    MPCD
    MPCY
    MPCAX
    POINTAX
    RBAR
    RBE1
    RBE2
    RBE3
    RROD
    RSPLINE
    RTRPLT

### p-Element Geometry Constrains
    GMBC
    GMSPC

### Partitioning
    ASET
    ASET1
    CSUPEXT
    GRID
    OMIT
    OMIT1
    OMITAX
    RELEASE
    SEELT
    SESET

### Single-Point Constraints
    FLSYM
    GRID
    GRIDB
    GRDSET
    SPC
    SPC1
    SPCADD
    SPCAX
    SPCOFF
    SPCOFF

### User Sets
    DEFUSET
    SEUSET
    SEUSET1
    USET
    USET1

## Elements
### Aerodynamic Elements
    AEFACT
    AELINK
    AELIST
    AEQUAD4
    AESTAT
    AESURF
    AESURFS
    AETRIA3
    CAERO1
    CAERO2
    CAERO3
    CAERO4
    CAERO5
    CSSCHD
    PAERO1
    PAERO2
    PAERO3
    PAERO4
    PAERO5
    AELISTC
    SET1
    SET2
    SET3
    SPBLND1
    SPBLND2
    SPLINE1
    SPLINE2
    SPLINE3
    SPLINE4
    SPLINE5
    SPLINE6
    SPLINE7
    SPLINEX
    SPLINRB
    SPRELAX

### Axisymmetric Elements
    CAXISYM
    CCONEAX
    CQUADX
    CTRIAX
    CTRIAX6
    MREVERS
    PCONEAX

### Cohesive Zone Modeling Elements
    CIFHEX
    CIFPENT
    CIFQDX
    CIFQUAD
    MCOHE
    PCOHE

### Connector Elements
    CFAST*
    CSEAM
    CSLOT3**
    CSLOT4**
    CWELD
    PFAST
    PSEAM
    PWELD
    SWLDPRM

\* Line elements (primary)
\*\* Fluid elements (primary)

### Sidelines Contact (SOL 106, 129)
    BCONP
    BFRlC
    BLSEG
    BWIDTH

### Gap Elements
    CGAP
    PGAP

### Crack Tip Elements
    CRAC2D
    CRAC3D
    PRAC2D
    PRAC3D

### Damping Elements
    CBUSH1D*
    CDAMP1
    CDAMP1D
    CDAMP2
    CDAMP2D
    CDAMP3
    CDAMP4
    CDAMP5
    CVISC
    DAMPING
    HYBDAMP
    PBUSH1D
    PDAMP
    PDAMP5
    PDAMPT
    PVISC
    ROTHYBD
\* Scalar and bushing element (primary)

### Dummy elements
    ADUM1
    ADUM2
    ADUM3
    ADUM4
    ADUM5
    ADUM6
    ADUM7
    ADUM8
    ADUM9
    CDUM1
    CDUM2
    CDUM3
    CDUM4
    CDUM5
    CDUM6
    CDUM7
    CDUM8
    CDUM9
    PDUM1
    PDUM2
    PDUM3
    PDUM4
    PDUM5
    PDUM6
    PDUM7
    PDUM8
    PDUM9
    PLOTEL

### Fluid Acoustic Elements
    CAABSF
    CACINF3
    CACINF4
    CAXIF2
    CAXIF3
    CAXIF4
    CAXISYM*
    CFLUID2**
    CFLUID3**
    CFLUID4**
    CHACAB
    CHACBR
    CHEXA***
    CPENTA***
    CSLOT3
    CSLOT4
    CTETRA
    ELIST
    MAT10
    PAABSF
    PACABS
    PACBAR
    PACINF
    PANEL
    PSOLID
    SET1

\* Assymetric elements (primary)
\*\* Fluid elements (primary)
\*\*\* Solid elements (primary)

### Equivalent Radiated Power
    ERPPNL

### Poroelasticity (PEM)
    ACTRIM
    ACLOAD
    MATPE1
    MATF1

### Heat Transfer Elements
    BDYOR
    CHBDYE
    CHBDYG
    CHBDYP
    CONTRLT
    PHBDY

### Line Elements
    BAROR*
    BEAMOR*
    CBAR
    CBEAM
    CBEAM3
    CBEND
    CBUSH1D**
    CFAST
    CINTC
    CMREBAI
    CMREBAR
    CONROD
    CROD
    CTUBE
    CWELD
    PBAR
    PBARL
    PBARN1
    PBCOMP
    PBEAM
    PBEAM3
    PBEAML
    PBEMN1
    PBEND
    PFAST
    PBMSECT
    PBRSECT
    PBUSH1D
    PBUSH2D
    PMREBAI
    PMREBAR
    PROD
    PRODN1
    PTUBE
    PWELD

\* Coordinate System (primary)
\*\* Scalar and bushing elements (primary)

### Mass Elements
    CMASS1
    CMASS2
    CMASS3
    CMASS4
    CONM1
    CONM2
    PMASS
    NSM
    NSM1
    NSMADD
    NSML
    NSML1

### p-Element Interface Elements
    GMINTC
    GMINTS
    PINTC
    PINTS

### Rigid Elements
    RBAR
    RBAR1
    RBE1
    RBE2
    RBE2A
    RBE2D
    RBE2F
    RBE3
    RJOINT
    RROD
    RSPLINE
    RSSCON
    RTRPLT
    RTRPLT1

### Scalar and Bushing Elements
    CBUSH
    CBUSH1D
    CBUSH2D
    CELAS1
    CELAS1D
    CELAS2
    CELAS2D
    CELAS3
    CELAS4
    GENEL
    MGRSPR
    PBUSH
    PBUSHT
    PBUSH1D
    PELAS
    PELAST

### Solid Elements
    CHEXA
    CPENTA
    CTETRA
    PCOMPLS
    PLSOLID
    PSLDN1
    PSOLID
    PSOLIDD

### Surface Elements
    CQUAD
    CQUAD4
    CQUAD8
    CQUADR
    CSHEAR
    CTRIA3
    CTRIA6
    CTRIAR
    PCOMP
    PCOMPF
    PCOMPG
    PLCOMP
    PLPLANE
    PSHELL
    PSHLN1
    PSHLN2
    PSHEAR
    PSHEARN
    SNORM

## Geometry
### Adaptive Meshing
    HADACRI
    HADAPTL

### Aeroelastic Control Points
    AECOMP
    AECOMPL
    MONPNT1
    MONPNT2
    MONPNT3
    UXVEC

### Axisymmetry
    AXIC
    AXIF
    AXSLOT
    FLSYM
    POINTAX
    RINGAX
    SECTAX

### Coordinate Systems
    BAROR
    BEAMOR
    CORD1C
    CORD2C
    CORD1R
    CORD2R
    CORD3R
    CORD1RX
    CORD2RX
    CORD3RX
    CORD1S
    CORD2S
    CORD3G

### Cyclic Symmetry
    CYAX
    CYJOIN
    NLCYSYM

### Fluid Points
    ACMODL
    FREEPT
    FSLIST
    GRID
    GRIDB
    GRIDF
    GRIDS
    PRESPT
    RINGFL
    SLBDY

### Grid Points
    AEGRID
    GRID
    GRIDB
    GRDSET
    SEQGP

### p-Element and p-Adaptivity Analysis
    FEEDGE
    FEFACE
    GMBNDC
    GMBNDS
    GMCORD
    GMCURV
    GMINTC
    GMINTS
    GMSURF
    PINTC
    PINTS
    POINT

### Scalar Points
    EPOINT
    SEQGP
    SPOINT

### Superelement Analysis
    CSUPER
    CSUPEXT
    EXTRN
    GRID
    RELEASE
    SEBNDRY
    SEBULK
    SECONCT
    SEDLINK
    SEDRSP2
    SEDRSP3
    SEELT
    SEEXCLD
    SELABEL
    SELOC
    SEMPLN
    SEQSEP
    SESET
    SETREE

## Loads
### Dynamic Loads
    ACSRCE
    DAREA
    DELAY
    DLOAD
    DPHASE
    LOADCYH
    LOADCYN
    LSEQ
    NOLIN1
    NOLIN2
    NOLIN3
    NOLIN4
    NLRGAP
    RBE3U
    RLOAD1
    RLOAD2
    TABLED1
    TABLED2
    TABLED3
    TABLED4
    TABLED5
    TLOAD1
    TLOAD2

### Heat Transfer Loads
    CONV
    CONVM
    PCONV
    PCONVM
    QBDY1
    QBDY2
    QBDY3
    QHBDY
    QVECT
    QVOL
    RADBC
    RADBND
    RADCAV
    RADLST
    RADMTX
    RADSET
    SLOAD
    SLOADN1
    TEMP
    TEMPB3
    TEMPBC
    TEMPD
    TEMPN1
    VIEW
    VIEW3D

### p-Element Loads
    GMBC
    GMCONV
    GMLOAD
    GMQVOL
    TEMPF

### Static Loads
    ACCEL
    ACCEL1
    CLOAD*
    DEFORM
    FORCE
    FORCE1
    FORCE2
    FORCEAX
    FORCEi
    GRAV
    GRIDA
    LOAD
    LOADCLID
    LOADCNAM
    LOADCSUB
    LOADCYH
    LOADCYN
    LOADCYT
    LOADOF
    LOADT
    LSEQ
    MOMAX
    MOMENT
    MOMENT1
    MOMENT2
    PLOAD
    PLOAD1
    PLOAD2
    PLOAD4
    PLOADB3
    PLOADX1
    PRESAX
    RBE3U
    RFORCE
    SLOAD
    SPCD
    SPCR
    TEMP
    TEMPD
    TEMPP1
    TEMPP3
    TEMPRB
    TEMPAX

\* Case control (primary)

## Materials
### Anisotropic
    MAT2
    MAT3
    MAT5
    MAT8
    MAT9
    MATORT

### Fatigue
    MATFTG

### Fluid
    AXIF*
    AXSLOT*
    BDYFORC
    CFLUID2
    CFLUID3
    CFLUID4
    CSLOT3
    CSLOT4
    FSLIST
    MAT10
    MFLUID
    SLBDY

\* Geometry (primary)

### Isotropic
    MAT1
    MAT4
    MATHP
    RADM

### Stress Dependent
    CREEP
    MATS1
    NLMOPTS
    TABLES1

### Temperature Dependent
    MATT1
    MATT2
    MATT3
    MATT4
    MATT5
    MATT8
    MATT9
    RADMT
    TABLEM1
    TABLEM2
    TABLEM3
    TABLEM4
    TABLEST
    TEMP
    TEMPAX
    TEMPD
    TEMPP1
    TEMPP2
    TEMPRB

## Miscellaneous
### Brake Squeal (SOL 400)
    BSQUEAL

### Direct Matrix Input
    CONM1*
    DMI
    DMIG
    DMIG
    UACCEL
    DMIAX
    TF

\* Mass element (primary)

### Direct Matrix Input for Elasticity
    DMIJ
    DMIJI
    DMIK
