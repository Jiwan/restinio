project(tests)

add_subdirectory(default_constructed_settings)
add_subdirectory(ref_qualifiers_settings)
add_subdirectory(header)
add_subdirectory(buffers)
add_subdirectory(response_coordinator)
add_subdirectory(uri_helpers)
add_subdirectory(socket_options)
add_subdirectory(start_stop)
add_subdirectory(handle_requests)
add_subdirectory(http_pipelining)
add_subdirectory(sendfile)
add_subdirectory(router)
add_subdirectory(encoders)
add_subdirectory(string_view)
add_subdirectory(from_string)
add_subdirectory(websocket)

if ( OPENSSL_FOUND )
	add_subdirectory(socket_options_tls)
endif ()
