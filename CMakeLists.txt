project(kdeedu-data)
cmake_minimum_required(VERSION 3.16)

find_package(ECM 5.90 REQUIRED NO_MODULE)
set(CMAKE_MODULE_PATH ${ECM_MODULE_PATH})

include(FeatureSummary)
include(KDEInstallDirs)

add_subdirectory(icons)
add_subdirectory(data)

feature_summary(WHAT ALL INCLUDE_QUIET_PACKAGES FATAL_ON_MISSING_REQUIRED_PACKAGES)
