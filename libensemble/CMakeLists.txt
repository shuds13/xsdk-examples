# Example needs updating.
add_executable(test_persistent_aposmm_tao.py)

xsdk_add_test(
    NAME
    libEnsemble-persis_aposmm_tao
    MPI_NPROCS
    4
    COMMAND
    python
    $<TARGET_FILE:test_persistent_aposmm_tao.py>
)

