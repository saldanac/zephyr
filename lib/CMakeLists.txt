add_subdirectory(crc)
add_subdirectory_ifdef(CONFIG_JSON_LIBRARY json)
add_subdirectory(libc)
add_subdirectory_if_kconfig(ring_buffer)
