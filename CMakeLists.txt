cmake_minimum_required(VERSION 3.13)

# set the project name
# project(Tutorial-env VERSION 1.0)

# add the executable
add_executable(tutorial-env tutorial-env.cxx)

configure_file(TutorialConfig.h.in TutorialConfig.h)
# target_include_directories(
#     Tutorial-env PUBLIC
#     "${PROJECT_BINARY_DIR}"
# )
