# set(WALL_JPG_PATH ${CMAKE_CURRENT_SOURCE_DIR}/wall.jpg PARENT_SCOPE)

FILE(COPY model DESTINATION ../src)

install(DIRECTORY model DESTINATION ${CMAKE_INSTALL_BINDIR})