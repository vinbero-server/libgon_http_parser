add_library(gon_http_parser SHARED gon_http_parser.c)
set_target_properties(gon_http_parser PROPERTIES PUBLIC_HEADER "gon_http_parser.h")
install(TARGETS gon_http_parser
         LIBRARY DESTINATION lib
         PUBLIC_HEADER DESTINATION include)
