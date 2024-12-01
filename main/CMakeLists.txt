set(COMPONENT_REQUIRES "PMSA003I_Arduino_Library")
set(COMPONENT_REQUIRES "Bus_IO_Library")
idf_component_register(SRCS "i2ctools_example_main.c"
                        "cmd_i2ctools.c"
                    INCLUDE_DIRS ".")