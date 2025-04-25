project(test)

set(DART_TESTING_ENABLED FALSE)
enable_testing()

cmake_policy(SET CMP0110 NEW)

# add_executable(${PROJECT_NAME}
	# engine/math
	# engine_tst/math_tst/vector_tst.cpp
	# engine_tst/math_tst/matrix_tst.cpp
# )

# target_link_libraries(${PROJECT_NAME}
	# PRIVATE
	# Catch2::Catch2WithMain
	# math_lib
# )

## engine/math tests
# add_test(NAME math[Vector] COMMAND ${PROJECT_NAME} [math-vector])
# add_test(NAME math[Matrix] COMMAND ${PROJECT_NAME} [math-matrix])
