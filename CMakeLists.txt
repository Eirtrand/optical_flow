cmake_minimum_required( VERSION 2.8 )
project( DisplayImage )
set( OpenCV_DIR "/usr/share/OpenCV/" )
find_package( OpenCV REQUIRED )
add_executable( DisplayImage main.cpp )
target_link_libraries( DisplayImage ${OpenCV_LIBS} )
