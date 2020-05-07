project('simpleini',
    'c',
    license : 'MIT',
)

simpleini_lib = static_library('simpleini',
                               'ConvertUTF.c',
                                override_options: ['warning_level=0'])

simpleini_dep = declare_dependency(link_with: simpleini_lib,
                                   include_directories: include_directories('.')
)
