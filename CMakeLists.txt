cmake_minimum_required(VERSION 2.8)
SET_PROPERTY(GLOBAL PROPERTY USE_FOLDERS ON)
project(deps)
 

include_directories(
   ./libjpeg-turbo
   ./libjpeg-turbo/include
)

 
 
set(thridParty_IDE_FOLDER ${PROJECT_NAME})


add_subdirectory(abseil-cpp)
add_subdirectory(libjpeg_turbo)
add_subdirectory(libyuv)
add_subdirectory(jsoncpp/source)
add_subdirectory(libcurl)
add_subdirectory(libsrtp)
add_subdirectory(yaml-cpp)
#add_subdirectory(libev)
add_subdirectory(libuv)
#add_subdirectory(zmalloc)
#add_subdirectory(libredis)
add_subdirectory(opus)
#add_subdirectory(ffmpeg)
#add_subdirectory(libsip)
add_subdirectory(faad2)
#add_subdirectory(h264bitstream)
#add_subdirectory(usrsctplib)

add_subdirectory(usrsctp/usrsctplib)
 
 