# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-khabarovsk
pkgver=26
pkgrel=1
pkgdesc="Map of Khabarovsk for 2GIS, January 2013"
arch=('i686' 'x86_64')
url="http://khabarovsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Khabarovsk-26.orig.zip")
md5sums=('48efa5fde3b2a4883283275a35a7e202')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Khabarovsk.dgdat "${startdir}/pkg/opt/2gis/khabarovsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Khabarovsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Khabarovsk.dglf" || return 1
     
}

