vanilla_logo_plymouth = configure_file(
  input: 'vanilla-logo.plymouth.in',
  output: '@BASENAME@',
  configuration: {
    'PLYMOUTH_THEME_PATH': plymouth_theme_path,
  },
  install: true,
  install_dir: plymouth_theme_path / 'vanilla-logo',
)

vanilla_logo_scale2_plymouth = configure_file(
  input: 'vanilla-logo-scale-2.plymouth.in',
  output: '@BASENAME@',
  configuration: {
    'PLYMOUTH_THEME_PATH': plymouth_theme_path,
  },
  install: true,
  install_dir: plymouth_theme_path / 'vanilla-logo',
)

install_subdir('logo_assets',
  install_dir:plymouth_theme_path / 'vanilla-logo',
  strip_directory: true,)
