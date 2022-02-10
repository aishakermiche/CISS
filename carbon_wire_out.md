***************************************************************************
*                      M-SPARC v1.0.0 (Sep 20, 2021)                      *
*   Copyright (c) 2019 Material Physics & Mechanics Group, Georgia Tech   *
*           Distributed under GNU General Public License 3 (GPL)          *
*                Date: 07-Nov-2021  Start time: 12:01:50                  *
***************************************************************************
                           Input parameters                                
***************************************************************************
CELL: 14.000000 14.000000 6.000000 
LATVEC:
1.000000000000000 0.000000000000000 0.000000000000000 
0.000000000000000 1.000000000000000 0.000000000000000 
0.000000000000000 0.000000000000000 1.000000000000000 
FD_GRID: 28 28 12
FD_ORDER: 12
BC: D D P
KPOINT_GRID: 1 1 1
KPOINT_SHIFT: 0 0 0
SPIN_TYP: 1
ELEC_TEMP_TYPE: fermi-dirac
SMEARING: 0.007350000
CHEB_DEGREE: 17
NSTATES: 10
EXCHANGE_CORRELATION: LDA_PW
CALC_STRESS: 0
CALC_PRES: 0
MAXIT_SCF: 100
TOL_SCF: 1.00E-05
TOL_POISSON: 1.00E-07
TOL_LANCZOS: 1.00E-02
TOL_PSEUDOCHARGE: 1.00E-04
MIXING_VARIABLE: density
MIXING_PRECOND: kerker
MIXING_PRECOND_MAG: none
TOL_PRECOND: 2.50E-04
PRECOND_KERKER_KTF: 1.00
PRECOND_KERKER_THRESH: 0.10
MIXING_PARAMETER: 0.30
MIXING_PARAMETER_MAG: 0.30
MIXING_HISTORY: 7
PULAY_FREQUENCY: 1
PULAY_RESTART: 0
REFERENCE_CUTOFF: 0.50
RHO_TRIGGER: 4
FIX_RAND: 0
PRINT_FORCES: 1
PRINT_ATOMS: 1
PRINT_EIGEN: 0
PRINT_DENSITY: 0
OUTPUT_FILE: carbon_wire.out_9
***************************************************************************
                                Cell                                       
***************************************************************************
Lattice vectors:
14.000000000000000 0.000000000000000 0.000000000000000 
0.000000000000000 14.000000000000000 0.000000000000000 
0.000000000000000 0.000000000000000 6.000000000000000 
Volume                  :  1.1760000000E+03 (Bohr^3)
***************************************************************************
                             Initialization                                
***************************************************************************
Mesh spacing                       :  0.500000 (Bohr)
Number of symmetry adapted k-points:  1
Output printed to                  :  carbon_wire.out_9
Total number of atom types         :  1
Total number of atoms              :  2
Total number of electrons          :  8
Atom type 1  (valence electrons)   :  C 4
Pseudopotential                    :  ../../Pseudopotentials/psd_oncv_C.pot
lloc                               :  4
Pseudocharge radii of atom type 1  :  3.00 3.00 3.00
Number of atoms of type 1          :  2
Estimated total memory usage       :  34.34 MB
========================================================================================
                            Self Consistent Field (SCF#1)                     
========================================================================================
Iteration     Free Energy (Ha/atom)    Magnetization     SCF Error        Timing (sec)
1            -5.5389502226E+00         1.9927E+00        4.463E-01        0.392
2            -5.6945684730E+00         1.9842E+00        3.073E-01        0.282
3            -5.6827536490E+00         1.6624E+00        2.467E-01        0.272
4            -5.6806339421E+00         5.3989E-02        2.166E-01        0.239
5            -5.6437029048E+00         2.1342E-01        2.999E-01        0.217
6            -5.6474168389E+00        -2.1559E-03        8.717E-02        0.233
7            -5.6538863567E+00        -7.2244E-04        5.855E-02        0.217
8            -5.6406279051E+00         9.0421E-05        1.975E-02        0.242
9            -5.6407960855E+00         3.8844E-04        2.456E-02        0.228
10           -5.6418806015E+00         6.2747E-05        5.611E-03        0.214
11           -5.6419822149E+00        -3.3038E-05        3.723E-03        0.204
12           -5.6422284946E+00         2.5244E-05        1.603E-03        0.235
13           -5.6422530154E+00        -1.9512E-05        1.154E-03        0.193
14           -5.6422659891E+00         7.5818E-07        3.795E-04        0.198
15           -5.6422741473E+00        -2.3796E-07        1.750E-04        0.174
16           -5.6422768191E+00        -5.1390E-08        1.059E-04        0.184
17           -5.6422777507E+00        -1.8095E-07        7.323E-05        0.190
18           -5.6422782255E+00        -3.4647E-08        5.152E-05        0.207
19           -5.6422784813E+00         8.7647E-08        2.834E-05        0.179
20           -5.6422785148E+00         4.1928E-09        1.833E-05        0.185
21           -5.6422785225E+00        -2.7252E-08        7.020E-06        0.187
Total number of SCF: 21    
====================================================================
                                Energy                              
====================================================================
Free energy per atom               : -5.6422785225E+00 (Ha/atom)
Total free energy                  : -1.1284557045E+01 (Ha)
Band structure energy              : -3.7376399470E+00 (Ha)
Exchange correlation energy        : -3.0565371247E+00 (Ha)
Self and correction energy         : -2.9397874103E+01 (Ha)
Entropy*kb*T                       : -7.9363730253E-05 (Ha)
Fermi level                        : -2.7539164922E-01 (Ha)
Net Magnetization                  : -2.7251820356E-08 
Average force                      :  3.4591430074E-02 (Ha/Bohr)
Maximum force                      :  3.4591430074E-02 (Ha/Bohr)
Time for force calculation         :  0.078 (sec)
***************************************************************************
                               Timing info                                 
***************************************************************************
Total walltime                     :  5.191 sec
___________________________________________________________________________

***************************************************************************
*             Material Physics & Mechanics Group, Georgia Tech            *
*                       PI: Phanish Suryanarayana                         *
*                Main Developers: Qimen Xu, Abhiraj Sharma                *
*     Acknowledgements: U.S. DOE (DE-SC0019410); NSF (1333500,1553212)    *
***************************************************************************