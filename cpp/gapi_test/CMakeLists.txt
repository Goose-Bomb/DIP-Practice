set(target_name "gapi_test")

add_executable(${target_name}
    main.cpp
)

target_include_directories(${target_name} PRIVATE ${OpenCV_INCLUDE_DIRS})
target_link_libraries(${target_name} PRIVATE ${OpenCV_LIBS})