# (C) Copyright 2017-2018 UCAR.
#
# This software is licensed under the terms of the Apache Licence Version 2.0
# which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

set ( atmvertinterplay_files
    ObsAtmVertInterpLay.h
    ObsAtmVertInterpLay.cc
    ObsAtmVertInterpLay.interface.F90
    ObsAtmVertInterpLay.interface.h
    ufo_atmvertinterplay_mod.F90
    pindex.f90
)

PREPEND( _p_atmvertinterplay_files     "atmvertinterplay"     ${atmvertinterplay_files} )

set ( atmvertinterplay_src_files
      ${_p_atmvertinterplay_files}
      PARENT_SCOPE
)
