executable(
    meson.project_name(),
    'Objects/Box.vala',
    'Objects/Video.vala',
    'Services/DataBaseManager.vala',
    'Services/LocalFilesManager.vala',
    'Services/LibraryManager.vala',
    'Services/MovieDatabaseManager.vala',
    'Interfaces/Inhibitor.vala',
    'Interfaces/MediaKeys.vala',
    'Interfaces/Thubnailer.vala',
    'Widgets/Box.vala',
    'Widgets/SubTitleRow.vala',
    'Widgets/Video.vala',
    'Widgets/Playlist.vala',
    'Widgets/VideoTimeLine.vala',
    'Widgets/PreviewPopover.vala',
    'Widgets/Views/Welcome.vala',
    'Widgets/Views/BoxesView.vala',
    'Widgets/Views/BoxView.vala',
    'Widgets/Views/PlayerView.vala',
    'Utils/Utils.vala',
    'Utils/Pixbuf.vala',
    'Utils/MovieDatabase.vala',
    'Dialogs/Preferences.vala',
    'Settings.vala',
    'MainWindow.vala',
    'Application.vala',
    c_args: c_args,
    dependencies: [
        dependency('gio-2.0'),
        dependency('gobject-2.0'),
        dependency('glib-2.0'),
        dependency('gtk+-3.0'),
        dependency('libsoup-2.4'),
        dependency('granite'),
        dependency('sqlite3'),
        dependency('clutter-gtk-1.0'),
        dependency('clutter-gst-3.0'),
    ],
    link_args: ['-lm'],
    install : true
)
