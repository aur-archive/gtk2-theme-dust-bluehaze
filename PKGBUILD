# Contributor: Chad Davis <archlinux at davtek DOT com>

pkgname=gtk2-theme-dust-bluehaze
pkgver=0.4.0
pkgrel=1
pkgdesc="Dust-BlueHaze was modified by S. Christian Collins from the original Ubuntu Dust 0.4 theme."
arch=(i686 x86_64)
url="http://www.gnome-look.org/content/show.php/Dust-BlueHaze?content=111950"
license=('Creative Commons Attribution')
groups=('gtk2-themes')
depends=('gtk-engine-murrine' 'gtk-engines')
optdepends=('hydroxygen-iconset: The theme calls hydroxygen as its default icon set')
source=("http://www.gnome-look.org/CONTENT/content-files/111950-Dust-BlueHaze-0.4.tar.gz")
md5sums=('307377ac681f1e3f8b0e324f5d064da4')

build() {
  cd ${srcdir}/
  tar zxf Dust-BlueHaze.tar.gz
  mkdir -p $pkgdir/usr/share/themes/
  cp -r $srcdir/Dust-BlueHaze $pkgdir/usr/share/themes/
}
