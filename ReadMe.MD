
# ========================================
# Pre-Launch Thermal Analysis of Two-Stage Reusable Launch Vehicle:
# ========================================

## Pre-Launch Thermal Analysis of Two-Stage Reusable Launch Vehicle using SindaG.

##
## I. Operation: "./run_sinda180a.bat"


##
## II. SindaG Input File: "./k1_pre_launch_f.sin"

    ==================================
    START: Input File: "k1_pre_launch_f.sin"
    ==================================
    ... content removed ...
      This model contains all of the physical connection that were
      modeled in the Thermal Analysis.

      The model units are Metric:
      Length:		Meters
      Mass:		Kilograms
      Time:		Seconds
      Temperature:	deg C
      
      
      A brief description of the Node IDs is given below

      NAME                               First Node   Last Node
      ---------------------------------  ----------   ---------
      OV STRUCTURES LRU                        1        1735
      OV LOX TANK                           2001        2197
      OV PROPULSION LRU                     2201        2665
      OV LANDING LRU                        2701        2749
      OV ELECTRONICS LRU                    2801        2941
      OV TPS                                3001        7066
      ADD'L ARITHMETIC NODES                8001        8137
      OV OPPENHEIM ELEMENTS (RADIATION)    40001       47066
      OV OPPENHEIM ELEMENTS (RADIATION)    60073       42938

      LAP STRUCTURES LRU                    10001       11356
      LAP LOX TANK                          11501       11752
      LAP RP TANK                           11801       12064
      LAP LANDING LRU                       12101       12167
      LAP PROPULSION LRU                    12201       12756
      LAP PROPULSION LRU - AVIONCS          12801       12857
      LAP ELECTRONICS LRU                   12901       13011
      LAP TPS                               13101       17126
      ADD'L ARITHMETIC NODES                18001       18410
      ADD'L ARITHMETIC NODES (BOOTS)        18411       18538
      LAP OPPENHEIM ELEMENTS (RADIATION)    50001       57126
      LAP OPPENHEIM ELEMENTS (RADIATION)    70001       73008
    ... content removed ...
    ==================================
    END: Input File: "k1_pre_launch_f.sin"
    ==================================

##
## III. PreProcessor Output FORTRAN: "./k1_pre_launch_f.for"
##
## IV. PreProcessor Output Listing: "./k1_pre_launch_f.lis"
##
## V. SindaG Output File: "./k1_pre_launch_f.out"

## 
## *Note: 
## 1. Thermal Analysis performed using SINDA-G, ( http://www.mscsoftware.com/product/sinda )
