cmake_minimum_required(VERSION 3.0)  # CMake version check
project(pico)                     # Create project
set(C_STANDARD 1)                    # Set C11 standard

add_executable(pico attach.c basic.c bind.c browse.c buffer.c composer.c display.c file.c fileio.c line.c main.c osdep.c pico_os.c pico.c random.c region.c search.c tcap_old.c unixdirs.c unixfiles.c window.c word.c)
