cmake_minimum_required( VERSION 2.6 )
project( es_common )

include_directories( Common/Include )

find_library( OPENGLES3_LIBRARY GLESv2 "OpenGL ES v3.0 library")
find_library( EGL_LIBRARY EGL "EGL 1.4 library" )

SUBDIRS( Common
    )
