# Contributor: Noah Diewald <noah@diewald.me>

pkgname=ttf-aboriginal-sans
pkgver=9.602
pkgrel=1
pkgdesc="These fonts contain characters for Syllabics, Cherokee, and Latin Script (Roman orthography). Comes in Regular, Italic, Bold, and Bold Italic."
url="http://www.languagegeek.com"
license=('GPL-3')
depends=('fontconfig' 'xorg-font-utils')
install=ttf-aboriginal-sans.install
source=('http://www.languagegeek.com/font/AboriginalSans.zip')
arch=('any')
md5sums=('a05faa5e551a4c24508bcc8b452b087e')

 build() {
  install -Dm644 $srcdir/AboriginalSansBOLDITALIC.ttf $pkgdir/usr/share/fonts/TTF/AboriginalSansBOLDITALIC.ttf
  install -Dm644 $srcdir/AboriginalSansBOLD.ttf $pkgdir/usr/share/fonts/TTF/AboriginalSansBOLDITALIC.ttf
  install -Dm644 $srcdir/AboriginalSansITALIC.ttf $pkgdir/usr/share/fonts/TTF/AboriginalSansITALIC.ttf
  install -Dm644 $srcdir/AboriginalSansREGULAR.ttf $pkgdir/usr/share/fonts/TTF/AboriginalSansREGULAR.ttf
 }


