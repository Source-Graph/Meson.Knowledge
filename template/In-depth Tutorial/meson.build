project('c++ foolib', 'cpp',
  version : '1.0.0',
  license : 'MIT')
add_global_arguments('-DSOME_TOKEN=value', language : 'cpp')
glib_dep = dependency('glib-2.0')

inc = include_directories('include')

subdir('include')
subdir('src')
subdir('test')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : foolib,
                 version : '1.0',
                 name : 'libfoobar',
                 filebase : 'foobar',
                 description : 'A Library to barnicate your foos.')