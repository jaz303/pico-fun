add_executable(main
        main.c
        )

# Pull in our pico_stdlib which pulls in commonly used features
target_link_libraries(main pico_stdlib)

# create map/bin/hex file etc.
pico_add_extra_outputs(main)
