PROJECT(adbase)
ADD_SUBDIRECTORY(adbase adbase)
#ADD_SUBDIRECTORY(example example)
ADD_SUBDIRECTORY(test test)
ADD_SUBDIRECTORY(seed seed)

ENABLE_TESTING()
ADD_TEST(TEST_ALL ${PROJECT_BINARY_DIR}/test/test_all)
