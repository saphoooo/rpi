FROM rpi-xenial
MAINTAINER de13 <stephane.beuret@data-essential.com>
ENV DEBIAN_FRONTEND noninteractive
ADD sources.list /etc/apt/sources.list
RUN apt-get update -y && \
    apt-get install -y adduser apt apt-transport-https base-files base-passwd bash bzip2 ca-certificates \
    coreutils curl dash dbus-user-session debconf debianutils dpkg findutils gcc-6-base gnupg-agent \
    gnupg2 gpgv2 grep gzip hostname init-system-helpers jq libacl1 libapt-pkg5.0 \
    libassuan0 libattr1 libaudit-common libaudit1 libblkid1 libbz2-1.0 libc-bin \
    libc6 libdb5.3 libgcc1 libgcrypt20 libgpg-error0 \
    libksba8 liblz1 liblz4-1 liblzma5 libmount1 libncursesw5 libnpth0 libonig2 \
    libpam-modules libpam-modules-bin libpam-runtime libpam0g libpcre3 libreadline6 \
    libseccomp2 libselinux1 libsemanage-common libsemanage1 libsepol1 libsmartcols1 \
    libsqlite3-0 libstdc++6 libtinfo5 libudev1 libustr-1.0-1 libuuid1 locales login \
    lsb-base mawk multiarch-support ncurses-base openssl passwd perl-base pinentry-curses plzip \
    psmisc readline-common runit sed sensible-utils sysvinit-utils tar \
    tzdata ubuntu-keyring unzip util-linux zlib1g && \
    update-rc.d dbus defaults && update-rc.d dbus enable
