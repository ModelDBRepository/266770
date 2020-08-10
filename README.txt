
This folder contains matlab source code for the E-I and E-I-E models described in:

   Heitmann & Ermentrout (2020) Direction-selective motion discrimination
     by traveling waves in visual cortex. PLOS Computational Biology.

   Heitmann & Ermentrout (2016) Propagating Waves as a Cortical Mechanism
    of Direction-Selectivity in V1 Motion Cells. Proc of BICT'15. New York.

The models require the Brain Dynamics Toolbox which can be downloaded for free
from https://bdtoolbox.org. They were implemented using Version 2019a of the toolbox.

The files are as follows:
   EI0D.m     is the point E-I model
   EI1D.m     is the ring  E-I model
   EIE0D.m    is the point E-I-E model
   EIE1D.m    is the ring  E-I-E model

All source code was written by Stewart Heitmann <s.heitmann@victorchang.edu.au>.
Each program has its own HELP text which describes how to run it. For example:

>> help EI0D

   EI0D Point model of E-I cells with Wilson-Cowan dynamics 
   for the Brain Dynamics Toolbox (https://bdtoolbox.org)
 
   EXAMPLE:
      addpath ~/bdtoolkit
      sys = EI0D();
      gui = bdGUI(sys);
 
   AUTHOR
     Stewart Heitmann (2018,2019,2020)
 
   REFERENCES
     Heitmann & Ermentrout (2020) Direction-selective motion discrimination
        by traveling waves in visual cortex. PLOS Computational Biology.
     Heitmann & Ermentrout (2016) Propagating Waves as a Cortical Mechanism
        of Direction-Selectivity in V1 Motion Cells. Proc of BICT'15. New York.

Refer to the Handbook for the Brain Dynamics Toolbox (Heitmann & Breakspear,
2017-2019) for instructions on installing and running the toolbox itself.
