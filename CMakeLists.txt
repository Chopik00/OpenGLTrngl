cmake_minimum_required(VERSION 2.8)  

set(sources 
"main.cpp"
) 
add_executable(main ${sources} )		

target_include_directories(main PRIVATE "headers")