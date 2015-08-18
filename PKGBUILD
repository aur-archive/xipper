# Maintainer: Red Squirrel <iam at redsquirrel87 dot com>

pkgname=xipper
pkgver=2.0
pkgrel=3
pkgdesc="A simple GUI for extract-xiso tool"
arch=('any')
url="http://www.redsquirrel87.com/Xipper.html"
license=('freeware')
depends=('extract-xiso' 'gambas3-gb-gtk' 'gambas3-gb-form' 'gambas3-gb-image')
optdepends=('gambas3-gb-qt4: if you need the QT support (KDE)')
install='xipper.install'
source=(https://bitbucket.org/Red_Squirrel/xipper/downloads/${pkgname}-AUR-${pkgver}.tar.gz)
md5sums=('3f9074dbfba1728e47478f2d41458a92')

package() {
  install -Dm755 "${srcdir}/${pkgname}-${pkgver}/xipper.gambas" "${pkgdir}/usr/bin/xipper"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/xipper.desktop" "${pkgdir}/usr/share/applications/xipper.desktop"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/32x32.png" "${pkgdir}/usr/share/icons/hicolor/32x32/apps/xipper.png"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/64x64.png" "${pkgdir}/usr/share/icons/hicolor/64x64/apps/xipper.png"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/128x128.png" "${pkgdir}/usr/share/icons/hicolor/128x128/apps/xipper.png"
}

