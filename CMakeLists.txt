idf_component_register(SRCS "esp_lcd_ssd1351.c" 
                       INCLUDE_DIRS "include"
                       REQUIRES "driver" "esp_lcd")

include(package_manager)
cu_pkg_define_version(${CMAKE_CURRENT_LIST_DIR})
