cmake_minimum_required(VERSION 3.13)
project(dnsseeder)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(dnsseeder
        .idea/dnsseeder.iml
        .idea/encodings.xml
        .idea/misc.xml
        .idea/modules.xml
        .idea/vcs.xml
        .idea/workspace.xml
        cmake-build-debug/cmake_install.cmake
        cmake-build-debug/CMakeCache.txt
        cmake-build-debug/Makefile
        cmake-build-debug/Project.cbp
        .gitignore
        bitcoin.cpp
        bitcoin.h
        CMakeLists.txt
        combine.pl
        compat.h
        db.cpp
        db.h
        dns.c
        dns.h
        main.cpp
        Makefile
        netbase.cpp
        netbase.h
        protocol.cpp
        protocol.h
        README
        serialize.h
        strlcpy.h
        test.pl
        uint256.h
        util.cpp
        util.h)
