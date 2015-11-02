set(UtilsIncludeDir ${COMPONENTS_DIR/utils/include)

include_directories (
  ${UtilsIncludeDir}
)


if (DEFINED QT_PORT)
    include_directories(${Qt5Core_INCLUDE_DIRS})
endif (DEFINED QT_PORT)
