project('uWebSocketsMeson', 'cpp',
      version : '1.0',
      default_options : ['cpp_std=c++17', 'warning_level=3'])

threads = dependency('threads')
uSocketsMeson = dependency('uSocketsMeson', fallback : ['uSocketsMeson', 'uSocketsMeson_dep'])

includes = include_directories('uWebSockets/src/')
deps = [threads, uSocketsMeson]

uWebSocketsMeson_dep = declare_dependency(include_directories : includes, dependencies : deps)
