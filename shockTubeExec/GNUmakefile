#leave these alone
USE_EB = TRUE
ebase = navierDriver

#these you can change
DIM=3
#turns on or off symbol table
DEBUG=FALSE 
#optimization can be TRUE, FALSE or HIGH
OPT=HIGH
#parallel can be TRUE or FALSE
MPI=TRUE
#threading can be TRUE or FALSE
OPENMPCC =FALSE 

#leave these alone
CHOMBO_HOME = ../chombo_lib

LibNames = EBAMRTimeDependent EBAMRElliptic EBAMRTools Workshop EBTools AMRElliptic AMRTimeDependent AMRTools BoxTools
base_dir = .
src_dirs = ../src

INPUT = ramp.2d.inputs

include $(CHOMBO_HOME)/mk/Make.example

