FROM rpi-xenial
MAINTAINER de13 <stephane.beuret@data-essential.com>
ENV DEBIAN_FRONTEND noninteractive
ADD sources.list /etc/apt/sources.list
RUN apt-get update -y && \
    apt-get install -y adduser apt apt-transport-https base-files base-passwd bash bzip2 ca-certificates \
    coreutils curl dash debconf debianutils dpkg findutils gcc-6-base gnupg-agent \
    gnupg2 gpgv2 grep gzip hostname libacl1 libapt-pkg5.0 \
    libassuan0 libattr1 libaudit-common libaudit1 libblkid1 libbz2-1.0 libc-bin locales login \
    lsb-base mawk multiarch-support ncurses-base openssl passwd perl-base pinentry-curses plzip \
    psmisc readline-common sed sensible-utils tar tzdata ubuntu-keyring unzip util-linux zlib1g
