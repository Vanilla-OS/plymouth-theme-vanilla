project('plymouth-theme-vanilla',
  meson_version: '>= 0.61',
  version: '0.0.7',
  license : 'GPL3',
  default_options: ['prefix=/usr']
)
       
# Modules
i18n = import('i18n')

# Path variables
plymouth_theme_path = get_option('prefix') / get_option('datadir') / 'plymouth' / 'themes'

# config
conf = configuration_data()
conf.set_quoted('PLYMOUTH_THEME_PATH', plymouth_theme_path)

# Subdirectories
subdir('po')
subdir('src')
