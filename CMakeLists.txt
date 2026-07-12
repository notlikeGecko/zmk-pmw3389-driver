zephyr_library()

zephyr_library_sources_ifdef(CONFIG_PMW3389 src/pmw3389.c)
zephyr_library_sources_ifdef(CONFIG_PMW3389 src/pmw3389_priv.c)
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)