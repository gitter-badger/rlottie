
target_sources(rlottie
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/lottieitem.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/lottieloader.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/lottiemodel.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/lottieparser.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/lottieanimation.cpp"
    )

target_include_directories(rlottie
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}"
    )
