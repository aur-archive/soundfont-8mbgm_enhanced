pkgname=soundfont-8mbgm_enhanced
pkgver=1.8
pkgrel=1
pkgdesc="Improved soundfont for Creative sound cards for better game midi music"
arch=(any)
url="http://home.arcor.de/hbredel/Soundfonts/Soundfonts-English/soundfonts-english.html"
license=("Public Domain")
source=("http://www.descent2.de/files/sound/8mbgm_enhanced${pkgver//./}.7z")
md5sums=('a3ad963f707aae49d8ff9a1f2cd8a71f')

package() {
 install -Dm644 "$srcdir/8mbgm_enhanced${pkgver//./}.sf2" "$pkgdir/usr/share/soundfonts/8mbgm_enhanced${pkgver//./}.sf2"
}
