pkgname=rebornos-grub2-theme-vimix-git-fix
pkgver=1.0
pkgrel=1.0
pkgdesc="RebornOS grub2-theme-vimix-git-fix"
arch=('any')
url="https://github.com/RebornOS-Developers/rebornos-grub2-theme-vimix-git-fix"
license=('GPL3')
source=('theme.txt' 
        'unifont-regular-16.pf2')
sha256sums=('f41847031e57f4b286f2df99e0a561d5c169739594d2d65d6d60c873b10c773b'
            '2c76695c6dbb3736a13a4b65b720aabe9595dce39cf5795aebbd74ba63901907')

package() {
  mkdir -p ${pkgdir}/boot/grub/themes/Vimix
  install -Dm644 ${srcdir}/theme.txt ${pkgdir}/boot/grub/themes/Vimix/
  install -Dm644 ${srcdir}/unifont-regular-16.pf2 ${pkgdir}/boot/grub/themes/Vimix/
}

