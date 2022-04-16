cmake_minimum_required(VERSION 3.16)
project(hotspot8)

file(GLOB_RECURSE SOURCE_FILES "*.cpp" "*.hpp" "*.c" "*.h")

include_directories("/home/ziya/Documents/openjdk/build/linux-x86_64-normal-server-slowdebug/jdk/include/")
include_directories("/home/ziya/Documents/openjdk/build/linux-x86_64-normal-server-slowdebug/jdk/include/linux")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/prims")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/precompiled")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/runtime")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/utilities")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/classfile")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/oops")
include_directories("/home/ziya/Documents/openjdk/jdk/src/solaris/bin")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/cpu/x86/vm")
include_directories("/home/ziya/Documents/openjdk/hotspot/src/share/vm/interpreter")

add_executable(hotspot8 ${SOURCE_FILES})
