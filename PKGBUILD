# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-khabarovsk
pkgver=9
pkgrel=1
pkgdesc="Map of Khabarovsk for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Khabarovsk-${pkgver}.orig.zip")
md5sums=('05932634f23d1a4c2bb4c308313d457e')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Khabarovsk.dgdat "${startdir}/pkg/opt/2gis/khabarovsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Khabarovsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Khabarovsk.dglf" || return 1
     
}

