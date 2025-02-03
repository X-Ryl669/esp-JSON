set(srcs)

list(APPEND srcs "lib/JSON.tpp")


idf_component_register(SRCS ${srcs}
                       INCLUDE_DIRS "lib" "config"
                      )
