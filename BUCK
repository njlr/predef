prebuilt_cxx_library(
  name = 'boost-predef',
  header_only = True,
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.h'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)