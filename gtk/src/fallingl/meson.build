theme_dir = join_paths(get_option('datadir'), 'themes', meson.project_name()+'-fallingl')

conf_data = configuration_data()
conf_data.set('ThemeName', meson.project_name())
conf_data.set('VariantThemeName', meson.project_name()+' Falling Leaves')
configure_file(input : '../index.theme.in',
               output : 'index.theme',
               configuration : conf_data,
               install_dir: theme_dir)

subdir('gtk-2.0')
subdir('gtk-3.0')