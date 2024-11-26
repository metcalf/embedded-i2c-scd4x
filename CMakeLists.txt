idf_component_register(
    SRCS scd4x_i2c.c sensirion_common.c sensirion_i2c.c sensirion_i2c_hal.c
    INCLUDE_DIRS "."
    PRIV_REQUIRES i2c_manager driver
)
