idf_component_register(SRCS "src/TinyMqtt.cpp" "src/StringIndexer.cpp"
                    REQUIRES TinyConsole freertos esp_timer
                    INCLUDE_DIRS "./src")