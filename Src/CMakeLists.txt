
set(HEADERS         config.h
                    environmentoptions.h
                    gl_const.h
                    ilogger.h
                    map.h
                    mission.h
                    node.h
                    node_comparator.h
                    search.h
                    searchresult.h
                    tinyxml2.h
                    xmllogger.h)

set(SOURCES         config.cpp
                    environmentoptions.cpp
                    map.cpp
                    mission.cpp
                    node.cpp
                    node_comparator.cpp
                    search.cpp
                    tinyxml2.cpp
                    xmllogger.cpp)

add_executable(PathFinding ${HEADERS} ${SOURCES} main.cpp)

add_library(PPLIB ${HEADERS} ${SOURCES})

install(TARGETS PathFinding 
        CONFIGURATIONS Debug
        DESTINATION Bin/Debug)

install(TARGETS PathFinding 
        CONFIGURATIONS Release
        DESTINATION Bin/Release)
