if udev_hwdb_dir != ''
    # This file has to be updated using
    # ninja -C <builddir> libfprint/sync-udev-hwdb

    install_data('autosuspend.hwdb',
        rename: '60-autosuspend-@0@.hwdb'.format(versioned_libname),
        install_dir: udev_hwdb_dir,
    )
endif
