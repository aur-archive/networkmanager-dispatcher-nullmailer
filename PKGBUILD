# Maintainer : Martin Wimpress <code@flexion.org>
# Contributor: Frederik "Freso" S. Olesen <freso.dk@gmail.com>

pkgname=networkmanager-dispatcher-nullmailer
pkgver=1.0
pkgrel=2
pkgdesc="Dispatcher Script for nullmailer"
arch=(any)
license=('MIT')
url="http://www.gnome.org/projects/NetworkManager"
depends=('networkmanager' 'nullmailer')
backup=(etc/NetworkManager/dispatcher.d/10-nullmailer)
changelog=ChangeLog
source=("10-nullmailer")
sha256sums=('0cc49b15d71781a9fbc84d07b6f5221f62fae1d23c93c7a61ad75f7d22ec8baf')

package() {
    install -Dm700 "${srcdir}/10-nullmailer" "${pkgdir}/etc/NetworkManager/dispatcher.d/10-nullmailer"
}
