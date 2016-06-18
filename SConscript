#--------------------------------------------------------------------------
# File and Version Information:
#  $Id$
#
# Description:
#  SConscript file for package openmpi
#------------------------------------------------------------------------

# Do not delete following line, it must be present in 
# SConscript file for any SIT project
Import('*')

from SConsTools.standardCondaPackage import standardCondaPackage

REQUIRED_PKGLIBS='mpi'
EXPECTED_PKGLIBS='mca_common_sm mpi_cxx mpi_mpifh mpi_usempi ompitrace open-pal open-rte open-trace-format oshmem otfaux'
standardCondaPackage('openmpi', **locals())

