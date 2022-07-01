
# How to install CutyCapt on RHEL/CentOS/Fedora

```bash
git clone git@github.com:hoehrmann/CutyCapt.git ~/.local/src/CutyCapt
sudy yum-builddep -y CutyCapt
sudo yum install -y qt5-qtsensors qt5-qtsensors-devel qt5-qtlocation qt5-qtlocation-devel qt5-qtwebchannel qt5-qtwebchannel-devel qt5-qtwebkit-devel qt5-qtsvg-devel
qmake-qt5
make
mv ~/.local/src/CutyCapt/CutyCapt ~/.local/bin/
```

