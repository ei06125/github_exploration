cmake_minimum_required(VERSION 3.21)
project(github_exploration_solution)


add_executable(main)
target_sources(main PRIVATE "src/main.cpp")

execute_process(
    COMMAND git "config --local core.hooksPath tools/scripts/git/hooks"
    COMMENT "Configuring git hooks"
)
