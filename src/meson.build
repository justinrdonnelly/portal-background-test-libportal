portal_background_test_libportal_sources = [
  'main.c',
  'portal-background-test-libportal-application.c',
  'portal-background-test-libportal-window.c',
]

portal_background_test_libportal_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1', version: '>= 1.4'),
  dependency('libportal', version: '>= 0.9.1'),
]

portal_background_test_libportal_sources += gnome.compile_resources('portal-background-test-libportal-resources',
  'portal-background-test-libportal.gresource.xml',
  c_name: 'portal_background_test_libportal'
)

executable('portal-background-test-libportal', portal_background_test_libportal_sources,
  dependencies: portal_background_test_libportal_deps,
       install: true,
)
