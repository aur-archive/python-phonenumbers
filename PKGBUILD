# Maintainer: Felix Yan <felixonmars@gmail.com>

pkgname=python-phonenumbers
_pkgname=phonenumbers
pkgver=6.2.0
pkgrel=1
pkgdesc="Python version of Google's common library for parsing, formatting, storing and validating international phone numbers"
arch=('any')
url="https://github.com/daviddrysdale/python-phonenumbers"
license=('APACHE')
makedepends=("python-setuptools")
depends=('python')
source=("https://pypi.python.org/packages/source/p/$_pkgname/$_pkgname-$pkgver.tar.gz")

package() {
  cd $_pkgname-$pkgver
  python setup.py install -O1 --root "${pkgdir}"
}

sha512sums=('785dc6724f4f9ef1a27be1eb35f6d93039767b908b404e128a3b3f520fb5987689650540d56a76bd1dc10c60a6da61a6e47d1dfc29963f5b3ff976c60cfe8f77')
