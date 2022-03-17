set(COMPONENT_SRCS main.c )
set(COMPONENT_ADD_INCLUDEDIRS ".")

register_component()
idf_component_register(
  SRCS
    "ssd1306.c"
    "ssd1306_i2c.c"
    "ssd1306_spi.c"
)