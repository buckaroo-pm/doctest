load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'doctest', 
  header_namespace = '', 
  exported_headers = subdir_glob([
    ('doctest', '**/*.h'), 
  ]), 
  srcs = glob([
    'doctest/**/*.cpp', 
  ]), 
  visibility = [
    'PUBLIC', 
  ], 
)
