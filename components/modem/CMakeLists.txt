set(srcs "esp_modem.c"
         "esp_modem_dce_service.c"
         "esp_modem_netif.c"
         "esp_modem_compat.c"
         "sim800.c"
         "bg96.c")

idf_component_register(SRCS "${srcs}"
                       INCLUDE_DIRS ".")
