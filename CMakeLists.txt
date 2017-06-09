cmake_minimum_required (VERSION 2.6)

project(tegaki-zinnia-model)

set(MODEL_DATA
    jp/handwriting-ja.model)

set(META_DATA
    jp/handwriting-ja.meta)

install(FILES ${MODEL_DATA} ${META_DATA} DESTINATION ${HWR_MODEL_INSTALL_DIR})
