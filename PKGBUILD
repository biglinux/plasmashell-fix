# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=plasmashell-fix-git
pkgver=1.0.0_$(date +"%Y_%m_%d")
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/plasmashell-fix"
pkgdesc="Automatic re-open plasmashell if thats crash"
depends=('plasma-workspace')
source=("git+https://gitlab.com/biglinux/plasmashell-fix.git")
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/plasmashell-fix/plasmashell-fix/usr/" "${pkgdir}/"
    cp -r "${srcdir}/plasmashell-fix/plasmashell-fix/etc/" "${pkgdir}/"
}


