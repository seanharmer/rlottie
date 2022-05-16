add_executable(lottie2gif "lottie2gif.cpp")

target_compile_features(lottie2gif PRIVATE cxx_std_14)

target_link_libraries(lottie2gif rlottie)

target_include_directories(lottie2gif
                           PRIVATE
                           "${CMAKE_CURRENT_LIST_DIR}/../inc/")
