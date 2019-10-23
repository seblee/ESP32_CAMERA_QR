set(COMPONENT_SRCS "my_http_server.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")

set(COMPONENT_PRIV_REQUIRES esp_http_server) 
register_component()