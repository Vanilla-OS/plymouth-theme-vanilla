vanilla_bgrt_plymouth = i18n.merge_file(
  input: configure_file(
    input: 'vanilla-bgrt.plymouth.desktop',
    output: 'vanilla-bgrt.plymouth.desktop',
    configuration: {
      'PLYMOUTH_THEME_PATH': plymouth_theme_path,
    },
  ),
  output: 'vanilla-bgrt.plymouth',
  type: 'desktop',
  po_dir: po_dir,
  install: true,
  install_dir: plymouth_theme_path / 'vanilla-bgrt',
)

install_subdir('bgrt_assets',
  install_dir:plymouth_theme_path / 'vanilla-bgrt',
  strip_directory: true,)
