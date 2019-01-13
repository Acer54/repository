Es wird die Library "libpng12.so.0" benötigt.
Diese ist ab Ubuntu 16.04 nicht mehr in den offiziellen Quellen enthalten. Um diese dennoch zu installieren muss noch (vor oder nach der Installation) folgender Befehl ausgeführt werden:

wget -q -O /tmp/libpng12.deb http://mirrors.kernel.org/ubuntu/pool/main/libp/libpng/libpng12-0_1.2.54-1ubuntu1_amd64.deb \
  && sudo dpkg -i /tmp/libpng12.deb \
  && rm /tmp/libpng12.deb
