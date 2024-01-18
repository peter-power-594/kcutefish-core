# Core

System backend and start session and more.

## Compile dependencies

For OpenMandriva:
```shell
sudo dnf in task-develop
sudo dnf install extra-cmake-modules lib64KF5CoreAddons-devel lib64KF5GlobalAccel-devel lib64KF5WindowSystem-devel lib64KF5IdleTime-devel polkit-qt5-1-devel qt5-linguist-tools lib64qt5core-devel lib64qt5dbus-devel lib64qt5gui-devel lib64qt5quick-devel lib64qt5quickwidgets-devel lib64qt5quickshapes-devel lib64qt5quickparticles-devel lib64Qt5QuickControls2-devel lib64qt5widgets-devel lib64qt5x11extras-devel lib64qt5xml-devel lib64qt5xmlpatterns-devel lib64pulseaudio-devel lib64sm-devel lib64polkit1-devel x11-server-devel lib64xcb-devel lib64xcb-composite0 lib64xcb-cursor-devel lib64xcb-damage0 lib64xcb-ewmh2 lib64xcb-icccm4 lib64xcb-util-keysyms-devel lib64xcb-randr0 lib64xcb-util-renderutil-devel lib64xcb-shm0 lib64xcb-util-devel lib64xcb-util-image-devel lib64xfixes-devel lib64xcursor-devel x11-driver-input-libinput-devel x11-server-devel x11-server-xorg x11-driver-input-synaptics-devel lib64xtst-devel
```

## Runtime

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.
