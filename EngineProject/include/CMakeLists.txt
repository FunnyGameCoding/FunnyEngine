file(GLOB VECTORMATH_SOURCES "vectormath/ppu/cpp/*.*", "vectormath/scalar/cpp/*.*", "vectormath/spu/cpp/*.*", "vectormath/SSE/cpp/*.*")

message("sources = ${sources}")
message("AllSources = ${AllSources}")
list(APPEND ${AllSources} ${VECTORMATH_SOURCES})

message("AllSources = ${AllSources}")
