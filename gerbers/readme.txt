https://forum.kicad.info/t/how-to-make-oval-or-slot-holes-on-pcb/645/14

sudo su
apt-get update
apt-get build-dep gerbv
apt-get install autopoint sp libcairo2-dev
git clone git://git.geda-project.org/gerbv.git
cd gerbv
sh autogen.sh
./configure
make
make install