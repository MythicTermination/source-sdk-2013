cmake_minimum_required(VERSION 3.10)

project(SourceSDK-2013)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

if(ANDROID)
    set(CMAKE_SYSTEM_NAME Android)
    set(CMAKE_ANDROID_NDK ${ANDROID_NDK})
    set(CMAKE_ANDROID_ARCH_ABI arm64-v8a)
    set(CMAKE_ANDROID_STL_TYPE c++_shared)
    set(CMAKE_ANDROID_NDK_TOOLCHAIN_VERSION clang)
    set(CMAKE_ANDROID_API 21)
endif()

file(GLOB_RECURSE SOURCE_FILES "src/*.cpp" "src/*.c")

include_directories("include")

add_executable(SourceSDK-2013 ${SOURCE_FILES})
