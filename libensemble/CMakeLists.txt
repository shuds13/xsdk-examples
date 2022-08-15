# Example needs updating.

find_package(Python REQUIRED)

xsdk_add_test(
    NAME
    libEnsemble-persis_aposmm_tao
    MPI_NPROCS
    4
    COMMAND
    ${Python_EXECUTABLE} ${CMAKE_CURRENT_SOURCE_DIR}/test_persistent_aposmm_tao.py
)

