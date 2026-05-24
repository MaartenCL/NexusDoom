if(UNIX AND NOT APPLE)
    install(FILES nexusdoom.desktop DESTINATION share/applications)
    install(FILES nexusdoom.svg DESTINATION share/icons/hicolor/scalable/apps)
endif()
