cmake_minimum_required(VERSION 3.13)
set(DTK_VERSION
    "5.6.12"
    CACHE STRING "DTK version."
)
project(
    dtk
    VERSION ${DTK_VERSION}
    DESCRIPTION  "DTK version control repo"
    HOMEPAGE_URL "https://github.com/linuxdeepin/dtk"
    LANGUAGES CXX C
)
