add_library(dr_libs INTERFACE)

target_include_directories(dr_libs
        INTERFACE
        $<BUILD_INTERFACE:${CMAKE_CURRENT_LIST_DIR}>
        )

target_sources(dr_libs
        INTERFACE
        dr_flac.h
        dr_mp3.h
        dr_wav.h
        )
