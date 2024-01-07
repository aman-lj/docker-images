FROM ghcr.io/ublue-os/kinoite-main:39

RUN rpm-ostree install zsh fish neovim vim emacs kitty alacritty distrobox -y

RUN rpm-ostree cleanup -m && \
ostree container commit
