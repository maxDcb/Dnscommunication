add_executable(testsDns "main.cpp" )
target_link_libraries(testsDns Dnscommunication nlohmann_json::nlohmann_json)


