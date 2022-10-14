# hermopolis discord bot cmakelists.txt

# generals
cmake_minimum_required(VERSION 3.9)
project(discord-bot)

# setters
set(CMAKE_CXX_STANDARD 20)
set(bot_source bot.cpp)

# inclusions
include_directories(src)

# executables
add_executable(bot ${bot_source})