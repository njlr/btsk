cxx_library(
  name = 'btsk',
  header_namespace = 'btsk',
  exported_headers = subdir_glob([
    ('', '*.h'),
  ],
  excludes = glob([
    'Test.h',
  ])),
  srcs = glob([
    '*.cpp',
  ],
  excludes = glob([
    'Test.cpp',
  ])),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  header_namespace = '',
  headers = [
    'Test.h',
  ],
  srcs = [
    'Test.cpp',
  ],
)
