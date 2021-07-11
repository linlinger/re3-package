# Maintainer: Your Name <youremail@domain.com>
pkgname=gtavc
pkgver=1.0
pkgrel=1
pkgdesc="Grand Theft Auto:Vice City . Using reVC to run"
arch=("x86_64")
url="https://github.com/GTAmodding/re3"
license=('custom')
depends=("sudo")
source=("$pkgname-$pkgver.tar.gz")
sha256sums=('5c3fd68d7314722bd47062f2e4f93114a82e29d7d140cc6a9456de6d5e9b996c')


package() {
    cd ${pkgdir}/
    cp -r ${srcdir}/usr ./
    chmod 755 ./usr/share/applications/"Grand Theft Auto:  Vice City.desktop"
}
