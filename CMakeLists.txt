cmake_minimum_required ( VERSION 3.1 )
#########################################################################################
#
#   Library: Goop
#
#########################################################################################
project ( goop VERSION 0.1.0 )
list (APPEND GOOP .lib/goop/src/Class.vala)
list (APPEND GOOP .lib/goop/src/Guid.vala)

set (VALA_SOURCES "${VALA_SOURCES};${GOOP}" PARENT_SCOPE)
