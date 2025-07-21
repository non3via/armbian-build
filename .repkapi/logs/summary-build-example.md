<details><summary>Build: PREFER_DOCKER=no BUILD_MINIMAL=yes NAMESERVER=9.9.9.9 BUILD_DESKTOP=no ARMBIAN_BUILD_UUID=35dcd83d-82ed-4ce3-b5fa-464a9d08daf4 ARMBIAN_RELAUNCHED=yes BRANCH=legacy BOARD=repkapi3 SKIP_LOG_ARCHIVE=yes SET_OWNER_TO_UID=1000 RELEASE=bookworm KERNEL_CONFIGURE=yes build</summary>
<p>

### Armbian logs for 35dcd83d-82ed-4ce3-b5fa-464a9d08daf4
#### Armbian build at Mon Jul 21 07:46:12 UTC 2025 on ffe179e38ab4
#### Repeat build: ./compile.sh build BOARD=repkapi3 BRANCH=legacy BUILD_DESKTOP=no BUILD_MINIMAL=yes KERNEL_CONFIGURE=yes NAMESERVER=9.9.9.9 RELEASE=bookworm
#### ARGs: `'PREFER_DOCKER=no' 'BUILD_MINIMAL=yes' 'NAMESERVER=9.9.9.9' 'BUILD_DESKTOP=no' 'ARMBIAN_BUILD_UUID=35dcd83d-82ed-4ce3-b5fa-464a9d08daf4' 'ARMBIAN_RELAUNCHED=yes' 'BRANCH=legacy' 'BOARD=repkapi3' 'SKIP_LOG_ARCHIVE=yes' 'SET_OWNER_TO_UID=1000' 'RELEASE=bookworm' 'KERNEL_CONFIGURE=yes' 'build'`


</p></details>


<details><summary>Aggregation: debootstrap: 5; rootfs: 47; image: 2; desktop: 0; apt-sources: 0; hash: fdc18e13e7a4a8a3</summary>
<p>

### `AGGREGATED_PACKAGES_DEBOOTSTRAP`
- `apt-utils`: *added*
  - `initial:config/cli/bookworm/debootstrap/packages:1:symlink->config/cli/common/debootstrap/packages`
- `locales`: *added*
  - `initial:config/cli/bookworm/debootstrap/packages:2:symlink->config/cli/common/debootstrap/packages`
- `console-setup`: *added*
  - `initial:config/cli/bookworm/debootstrap/packages:3:symlink->config/cli/common/debootstrap/packages`
- `gnupg2`: *added*
  - `initial:config/cli/bookworm/debootstrap/packages:4:symlink->config/cli/common/debootstrap/packages`
- `ca-certificates`: *added*
  - `initial:config/cli/bookworm/debootstrap/packages:5:symlink->config/cli/common/debootstrap/packages`
- `software-properties-common`: *remove*
  - `remove::395`
  - `remove::395`
- `software-properties-gtk`: *remove*
  - `remove::395`
### `AGGREGATED_PACKAGES_ROOTFS`
- `alsa-utils`: *added*
  - `initial:config/cli/bookworm/main/packages:1:symlink->config/cli/common/main/packages`
- `bash-completion`: *added*
  - `initial:config/cli/bookworm/main/packages:2:symlink->config/cli/common/main/packages`
- `bc`: *added*
  - `initial:config/cli/bookworm/main/packages:3:symlink->config/cli/common/main/packages`
- `console-setup`: *added*
  - `initial:config/cli/bookworm/main/packages:4:symlink->config/cli/common/main/packages`
- `cron`: *added*
  - `initial:config/cli/bookworm/main/packages:5:symlink->config/cli/common/main/packages`
- `curl`: *added*
  - `initial:config/cli/bookworm/main/packages:6:symlink->config/cli/common/main/packages`
- `dbus-user-session`: *added*
  - `initial:config/cli/bookworm/main/packages:7:symlink->config/cli/common/main/packages`
- `dialog`: *added*
  - `initial:config/cli/bookworm/main/packages:8:symlink->config/cli/common/main/packages`
- `debconf-utils`: *added*
  - `initial:config/cli/bookworm/main/packages:9:symlink->config/cli/common/main/packages`
- `debsums`: *added*
  - `initial:config/cli/bookworm/main/packages:10:symlink->config/cli/common/main/packages`
- `dosfstools`: *added*
  - `initial:config/cli/bookworm/main/packages:11:symlink->config/cli/common/main/packages`
- `fake-hwclock`: *added*
  - `initial:config/cli/bookworm/main/packages:12:symlink->config/cli/common/main/packages`
- `fdisk`: *added*
  - `initial:config/cli/bookworm/main/packages:13:symlink->config/cli/common/main/packages`
- `figlet`: *added*
  - `initial:config/cli/bookworm/main/packages:14:symlink->config/cli/common/main/packages`
- `htop`: *added*
  - `initial:config/cli/bookworm/main/packages:15:symlink->config/cli/common/main/packages`
- `iputils-ping`: *added*
  - `initial:config/cli/bookworm/main/packages:16:symlink->config/cli/common/main/packages`
- `init`: *added*
  - `initial:config/cli/bookworm/main/packages:17:symlink->config/cli/common/main/packages`
- `initramfs-tools`: *added*
  - `initial:config/cli/bookworm/main/packages:18:symlink->config/cli/common/main/packages`
- `iproute2`: *added*
  - `initial:config/cli/bookworm/main/packages:19:symlink->config/cli/common/main/packages`
- `iw`: *added*
  - `initial:config/cli/bookworm/main/packages:20:symlink->config/cli/common/main/packages`
- `jq`: *added*
  - `initial:config/cli/bookworm/main/packages:21:symlink->config/cli/common/main/packages`
- `logrotate`: *added*
  - `initial:config/cli/bookworm/main/packages:22:symlink->config/cli/common/main/packages`
- `less`: *added*
  - `initial:config/cli/bookworm/main/packages:23:symlink->config/cli/common/main/packages`
- `linux-base`: *added*
  - `initial:config/cli/bookworm/main/packages:24:symlink->config/cli/common/main/packages`
- `lsof`: *added*
  - `initial:config/cli/bookworm/main/packages:25:symlink->config/cli/common/main/packages`
- `man-db`: *added*
  - `initial:config/cli/bookworm/main/packages:26:symlink->config/cli/common/main/packages`
- `mmc-utils`: *added*
  - `initial:config/cli/bookworm/main/packages:27:symlink->config/cli/common/main/packages`
- `ncurses-term`: *added*
  - `initial:config/cli/bookworm/main/packages:28:symlink->config/cli/common/main/packages`
- `nano`: *added*
  - `initial:config/cli/bookworm/main/packages:29:symlink->config/cli/common/main/packages`
- `openssh-server`: *added*
  - `initial:config/cli/bookworm/main/packages:30:symlink->config/cli/common/main/packages`
- `parted`: *added*
  - `initial:config/cli/bookworm/main/packages:31:symlink->config/cli/common/main/packages`
- `psmisc`: *added*
  - `initial:config/cli/bookworm/main/packages:32:symlink->config/cli/common/main/packages`
- `rsync`: *added*
  - `initial:config/cli/bookworm/main/packages:33:symlink->config/cli/common/main/packages`
- `rsyslog`: *added*
  - `initial:config/cli/bookworm/main/packages:34:symlink->config/cli/common/main/packages`
- `sudo`: *added*
  - `initial:config/cli/bookworm/main/packages:35:symlink->config/cli/common/main/packages`
- `systemd-resolved`: *added*
  - `initial:config/cli/bookworm/main/packages:36:symlink->config/cli/common/main/packages`
- `toilet`: *added*
  - `initial:config/cli/bookworm/main/packages:37:symlink->config/cli/common/main/packages`
- `tzdata`: *added*
  - `initial:config/cli/bookworm/main/packages:38:symlink->config/cli/common/main/packages`
- `u-boot-tools`: *added*
  - `initial:config/cli/bookworm/main/packages:39:symlink->config/cli/common/main/packages`
- `usbutils`: *added*
  - `initial:config/cli/bookworm/main/packages:40:symlink->config/cli/common/main/packages`
- `wget`: *added*
  - `initial:config/cli/bookworm/main/packages:41:symlink->config/cli/common/main/packages`
- `wireguard-tools`: *added*
  - `initial:config/cli/bookworm/main/packages:42:symlink->config/cli/common/main/packages`
- `wireless-regdb`: *added*
  - `initial:config/cli/bookworm/main/packages:43:symlink->config/cli/common/main/packages`
- `wpasupplicant`: *added*
  - `initial:config/cli/bookworm/main/packages:44:symlink->config/cli/common/main/packages`
- `gpiod`: *added*
  - `initial:config/optional/architectures/arm64/_config/cli/_all_distributions/main/packages:1`
  - `initial:config/optional/architectures/arm64/_config/cli/bookworm/main/packages:1:symlink->config/optional/architectures/arm64/_config/cli/sid/main/packages`
- `mtd-utils`: *added*
  - `initial:config/optional/architectures/arm64/_config/cli/_all_distributions/main/packages:2`
  - `initial:config/optional/architectures/arm64/_config/cli/bookworm/main/packages:2:symlink->config/optional/architectures/arm64/_config/cli/sid/main/packages`
- `nocache`: *added*
  - `initial:config/optional/architectures/arm64/_config/cli/_all_distributions/main/packages:3`
- `software-properties-common`: *remove*
  - `remove::395`
  - `remove::395`
- `software-properties-gtk`: *remove*
  - `remove::395`
### `AGGREGATED_PACKAGES_IMAGE`
- `systemd-timesyncd`: *added*
  - `initial:timesyncd.sh:6`
- `netplan.io`: *added*
  - `initial:networkd.sh:11`
- `software-properties-common`: *remove*
  - `remove::395`
  - `remove::395`
- `software-properties-gtk`: *remove*
  - `remove::395`
### `AGGREGATED_PACKAGES_DESKTOP`
- `software-properties-common`: *remove*
  - `remove::395`
  - `remove::395`
- `software-properties-gtk`: *remove*
  - `remove::395`
### `AGGREGATED_APT_SOURCES`
## Potential paths 
- `config/cli/_all_distributions/debootstrap/components`
- `config/cli/_all_distributions/debootstrap/config_cli_minimal/components`
- `config/cli/_all_distributions/debootstrap/config_cli_minimal/packages`
- `config/cli/_all_distributions/debootstrap/config_cli_minimal/packages.remove`
- `config/cli/_all_distributions/debootstrap/packages`
- `config/cli/_all_distributions/debootstrap/packages.remove`
- `config/cli/_all_distributions/main/config_cli_minimal/packages`
- `config/cli/_all_distributions/main/config_cli_minimal/packages.external`
- `config/cli/_all_distributions/main/config_cli_minimal/packages.remove`
- `config/cli/_all_distributions/main/packages`
- `config/cli/_all_distributions/main/packages.external`
- `config/cli/_all_distributions/main/packages.remove`
- `config/cli/bookworm/debootstrap/components`
- `config/cli/bookworm/debootstrap/config_cli_minimal/components`
- `config/cli/bookworm/debootstrap/config_cli_minimal/packages`
- `config/cli/bookworm/debootstrap/config_cli_minimal/packages.remove`
- `config/cli/bookworm/debootstrap/packages`
- `config/cli/bookworm/debootstrap/packages.remove`
- `config/cli/bookworm/main/config_cli_minimal/packages`
- `config/cli/bookworm/main/config_cli_minimal/packages.external`
- `config/cli/bookworm/main/config_cli_minimal/packages.remove`
- `config/cli/bookworm/main/packages`
- `config/cli/bookworm/main/packages.external`
- `config/cli/bookworm/main/packages.remove`
- `config/desktop/_all_distributions/environments/_all_environments/packages`
- `config/desktop/_all_distributions/environments/_all_environments/packages.additional`
- `config/desktop/_all_distributions/environments/_all_environments/packages.external`
- `config/desktop/_all_distributions/environments/_all_environments/packages.remove`
- `config/desktop/_all_distributions/environments/packages`
- `config/desktop/_all_distributions/environments/packages`
- `config/desktop/_all_distributions/environments/packages.additional`
- `config/desktop/_all_distributions/environments/packages.additional`
- `config/desktop/_all_distributions/environments/packages.external`
- `config/desktop/_all_distributions/environments/packages.external`
- `config/desktop/_all_distributions/environments/packages.remove`
- `config/desktop/_all_distributions/environments/packages.remove`
- `config/desktop/bookworm/environments/_all_environments/packages`
- `config/desktop/bookworm/environments/_all_environments/packages.additional`
- `config/desktop/bookworm/environments/_all_environments/packages.external`
- `config/desktop/bookworm/environments/_all_environments/packages.remove`
- `config/desktop/bookworm/environments/packages`
- `config/desktop/bookworm/environments/packages`
- `config/desktop/bookworm/environments/packages.additional`
- `config/desktop/bookworm/environments/packages.additional`
- `config/desktop/bookworm/environments/packages.external`
- `config/desktop/bookworm/environments/packages.external`
- `config/desktop/bookworm/environments/packages.remove`
- `config/desktop/bookworm/environments/packages.remove`
- `config/optional/_any_board/_config/cli/_all_distributions/debootstrap/components`
- `config/optional/_any_board/_config/cli/_all_distributions/debootstrap/config_cli_minimal/components`
- `config/optional/_any_board/_config/cli/_all_distributions/debootstrap/config_cli_minimal/packages`
- `config/optional/_any_board/_config/cli/_all_distributions/debootstrap/config_cli_minimal/packages.remove`
- `config/optional/_any_board/_config/cli/_all_distributions/debootstrap/packages`
- `config/optional/_any_board/_config/cli/_all_distributions/debootstrap/packages.remove`
- `config/optional/_any_board/_config/cli/_all_distributions/main/config_cli_minimal/packages`
- `config/optional/_any_board/_config/cli/_all_distributions/main/config_cli_minimal/packages.external`
- `config/optional/_any_board/_config/cli/_all_distributions/main/config_cli_minimal/packages.remove`
- `config/optional/_any_board/_config/cli/_all_distributions/main/packages`
- `config/optional/_any_board/_config/cli/_all_distributions/main/packages.external`
- `config/optional/_any_board/_config/cli/_all_distributions/main/packages.remove`
- `config/optional/_any_board/_config/cli/bookworm/debootstrap/components`
- `config/optional/_any_board/_config/cli/bookworm/debootstrap/config_cli_minimal/components`
- `config/optional/_any_board/_config/cli/bookworm/debootstrap/config_cli_minimal/packages`
- `config/optional/_any_board/_config/cli/bookworm/debootstrap/config_cli_minimal/packages.remove`
- `config/optional/_any_board/_config/cli/bookworm/debootstrap/packages`
- `config/optional/_any_board/_config/cli/bookworm/debootstrap/packages.remove`
- `config/optional/_any_board/_config/cli/bookworm/main/config_cli_minimal/packages`
- `config/optional/_any_board/_config/cli/bookworm/main/config_cli_minimal/packages.external`
- `config/optional/_any_board/_config/cli/bookworm/main/config_cli_minimal/packages.remove`
- `config/optional/_any_board/_config/cli/bookworm/main/packages`
- `config/optional/_any_board/_config/cli/bookworm/main/packages.external`
- `config/optional/_any_board/_config/cli/bookworm/main/packages.remove`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/_all_environments/packages`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/_all_environments/packages.additional`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/_all_environments/packages.external`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/_all_environments/packages.remove`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages.additional`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages.additional`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages.external`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages.external`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages.remove`
- `config/optional/_any_board/_config/desktop/_all_distributions/environments/packages.remove`
- `config/optional/_any_board/_config/desktop/bookworm/environments/_all_environments/packages`
- `config/optional/_any_board/_config/desktop/bookworm/environments/_all_environments/packages.additional`
- `config/optional/_any_board/_config/desktop/bookworm/environments/_all_environments/packages.external`
- `config/optional/_any_board/_config/desktop/bookworm/environments/_all_environments/packages.remove`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages.additional`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages.additional`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages.external`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages.external`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages.remove`
- `config/optional/_any_board/_config/desktop/bookworm/environments/packages.remove`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/debootstrap/components`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/debootstrap/config_cli_minimal/components`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/debootstrap/config_cli_minimal/packages`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/debootstrap/config_cli_minimal/packages.remove`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/debootstrap/packages`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/debootstrap/packages.remove`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/main/config_cli_minimal/packages`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/main/config_cli_minimal/packages.external`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/main/config_cli_minimal/packages.remove`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/main/packages`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/main/packages.external`
- `config/optional/architectures/arm64/_config/cli/_all_distributions/main/packages.remove`
- `config/optional/architectures/arm64/_config/cli/bookworm/debootstrap/components`
- `config/optional/architectures/arm64/_config/cli/bookworm/debootstrap/config_cli_minimal/components`
- `config/optional/architectures/arm64/_config/cli/bookworm/debootstrap/config_cli_minimal/packages`
- `config/optional/architectures/arm64/_config/cli/bookworm/debootstrap/config_cli_minimal/packages.remove`
- `config/optional/architectures/arm64/_config/cli/bookworm/debootstrap/packages`
- `config/optional/architectures/arm64/_config/cli/bookworm/debootstrap/packages.remove`
- `config/optional/architectures/arm64/_config/cli/bookworm/main/config_cli_minimal/packages`
- `config/optional/architectures/arm64/_config/cli/bookworm/main/config_cli_minimal/packages.external`
- `config/optional/architectures/arm64/_config/cli/bookworm/main/config_cli_minimal/packages.remove`
- `config/optional/architectures/arm64/_config/cli/bookworm/main/packages`
- `config/optional/architectures/arm64/_config/cli/bookworm/main/packages.external`
- `config/optional/architectures/arm64/_config/cli/bookworm/main/packages.remove`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/_all_environments/packages`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/_all_environments/packages.additional`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/_all_environments/packages.external`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/_all_environments/packages.remove`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages.additional`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages.additional`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages.external`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages.external`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages.remove`
- `config/optional/architectures/arm64/_config/desktop/_all_distributions/environments/packages.remove`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/_all_environments/packages`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/_all_environments/packages.additional`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/_all_environments/packages.external`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/_all_environments/packages.remove`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages.additional`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages.additional`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages.external`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages.external`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages.remove`
- `config/optional/architectures/arm64/_config/desktop/bookworm/environments/packages.remove`
- `userpatches/cli/_all_distributions/debootstrap/components`
- `userpatches/cli/_all_distributions/debootstrap/config_cli_minimal/components`
- `userpatches/cli/_all_distributions/debootstrap/config_cli_minimal/packages`
- `userpatches/cli/_all_distributions/debootstrap/config_cli_minimal/packages.remove`
- `userpatches/cli/_all_distributions/debootstrap/packages`
- `userpatches/cli/_all_distributions/debootstrap/packages.remove`
- `userpatches/cli/_all_distributions/main/config_cli_minimal/packages`
- `userpatches/cli/_all_distributions/main/config_cli_minimal/packages.external`
- `userpatches/cli/_all_distributions/main/config_cli_minimal/packages.remove`
- `userpatches/cli/_all_distributions/main/packages`
- `userpatches/cli/_all_distributions/main/packages.external`
- `userpatches/cli/_all_distributions/main/packages.remove`
- `userpatches/cli/bookworm/debootstrap/components`
- `userpatches/cli/bookworm/debootstrap/config_cli_minimal/components`
- `userpatches/cli/bookworm/debootstrap/config_cli_minimal/packages`
- `userpatches/cli/bookworm/debootstrap/config_cli_minimal/packages.remove`
- `userpatches/cli/bookworm/debootstrap/packages`
- `userpatches/cli/bookworm/debootstrap/packages.remove`
- `userpatches/cli/bookworm/main/config_cli_minimal/packages`
- `userpatches/cli/bookworm/main/config_cli_minimal/packages.external`
- `userpatches/cli/bookworm/main/config_cli_minimal/packages.remove`
- `userpatches/cli/bookworm/main/packages`
- `userpatches/cli/bookworm/main/packages.external`
- `userpatches/cli/bookworm/main/packages.remove`
- `userpatches/desktop/_all_distributions/environments/_all_environments/packages`
- `userpatches/desktop/_all_distributions/environments/_all_environments/packages.additional`
- `userpatches/desktop/_all_distributions/environments/_all_environments/packages.external`
- `userpatches/desktop/_all_distributions/environments/_all_environments/packages.remove`
- `userpatches/desktop/_all_distributions/environments/packages`
- `userpatches/desktop/_all_distributions/environments/packages`
- `userpatches/desktop/_all_distributions/environments/packages.additional`
- `userpatches/desktop/_all_distributions/environments/packages.additional`
- `userpatches/desktop/_all_distributions/environments/packages.external`
- `userpatches/desktop/_all_distributions/environments/packages.external`
- `userpatches/desktop/_all_distributions/environments/packages.remove`
- `userpatches/desktop/_all_distributions/environments/packages.remove`
- `userpatches/desktop/bookworm/environments/_all_environments/packages`
- `userpatches/desktop/bookworm/environments/_all_environments/packages.additional`
- `userpatches/desktop/bookworm/environments/_all_environments/packages.external`
- `userpatches/desktop/bookworm/environments/_all_environments/packages.remove`
- `userpatches/desktop/bookworm/environments/packages`
- `userpatches/desktop/bookworm/environments/packages`
- `userpatches/desktop/bookworm/environments/packages.additional`
- `userpatches/desktop/bookworm/environments/packages.additional`
- `userpatches/desktop/bookworm/environments/packages.external`
- `userpatches/desktop/bookworm/environments/packages.external`
- `userpatches/desktop/bookworm/environments/packages.remove`
- `userpatches/desktop/bookworm/environments/packages.remove`


</p></details>
<details><summary>kernel patching: 502 total patches; 502 applied; 0 with problems</summary>
<p>

| Status | Patch  | Diffstat Summary | Files patched | Author / Subject |
| :---:    | :---   | :---   | :---   | :---  |
|  🤖  ✅  | `[kernel-drivers/]` `sha1_36790ef5e00b69ccb92817f95ba1928eea24eebb_sunxi64_legacy_7b0b02a6_618e2a29-01ba4719` | `(+0/-0)[]` | `?` | `Armbian Autopatcher` _[AUTOGEN] /armbian/cache/patch/kernel-drivers/sha1_36790ef5e00b69ccb92817f95ba1928eea24eebb_sunxi64_legacy_7b0b02a6_618e2a29-01ba4719_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-Set-maximum-P-and-M-factors-to-1-for-H3-pll-cpux-c` | `(+15/-9)[1M]` | `ccu-sun8i-h3.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _clk: sunxi-ng: Set maximum P and M factors to 1 for H3 pll-cpux clock_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-Don-t-use-CPU-PLL-gating-and-CPUX-reparenting-to-H` | `(+0/-21)[1M]` | `ccu-sun8i-h3.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _clk: sunxi-ng: Don't use CPU PLL gating and CPUX reparenting to HOSC_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-h3-Use-my-own-more-aggressive-OPPs-on-H3` | `(+36/-0)[1M]` | `sun8i-h3.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-h3: Use my own more aggressive OPPs on H3_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-h5-Use-my-own-more-aggressive-OPPs-on-H5` | `(+22/-22)[1M]` | `sun50i-h5-cpu-opp.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-h5: Use my own more aggressive OPPs on H5_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-h3-orange-pi-pc-Increase-max-CPUX-voltage-to-1.4V` | `(+2/-1)[1M]` | `sun8i-h3-orangepi-pc.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-h3-orange-pi-pc: Increase max CPUX voltage to 1.4V_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-h5-orangepi-pc2-Add-CPUX-regulator-enable-cpuf` | `(+30/-0)[1M]` | `sun50i-h5-orangepi-pc2.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-h5-orangepi-pc2: Add CPUX regulator, enable cpufreq_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-leds-Add-a-binding-for-AXP813-charger-led` | `(+24/-0)[1A]` | `leds-axp20x.yaml` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _dt-bindings: leds: Add a binding for AXP813 charger led_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Improve-CPU-OPP-tables-go-up-to-1.8GHz` | `(+22/-58)[1M]` | `sun8i-a83t.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t: Improve CPU OPP tables (go up to 1.8GHz)_ |
|  📜  ✅  | `[patches.megous/]` `leds-axp20x-Support-charger-LED-on-AXP20x-like-PMICs` | `(+274/-0)[3M, 1A]` | `leds-axp20x.c`, `Kconfig`, `axp20x.c`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _leds: axp20x: Support charger LED on AXP20x like PMICs_ |
|  📜  ✅  | `[patches.megous/]` `cpufreq-sun50i-Show-detected-CPU-bin-for-easier-debugging` | `(+1/-0)[1M]` | `sun50i-cpufreq-nvmem.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _cpufreq: sun50i: Show detected CPU bin, for easier debugging_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-axp813-Add-charger-LED` | `(+5/-0)[1M]` | `axp81x.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: axp813: Add charger LED_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Enable-charging-LED` | `(+4/-0)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Enable charging LED_ |
|  📜  ✅  | `[patches.megous/]` `nfc-pn544-Add-support-for-VBAT-PVDD-regulators` | `(+29/-2)[1M]` | `i2c.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _nfc: pn544: Add support for VBAT/PVDD regulators_ |
|  📜  ✅  | `[patches.megous/]` `bluetooth-bcm-Restore-drive_rts_on_open-true-behavior-on-bcm207` | `(+6/-1)[1M]` | `hci_bcm.c` | `Ondrej Jirman` _bluetooth: bcm: Restore drive_rts_on_open = true behavior on bcm20702a1_ |
|  📜  ✅  | `[patches.megous/]` `mmc-add-delay-after-power-class-selection` | `(+4/-0)[1M]` | `mmc.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _mmc: add delay after power class selection_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-input-gpio-vibrator-Don-t-require-enable-gpios` | `(+6/-1)[1M]` | `gpio-vibrator.yaml` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _dt-bindings: input: gpio-vibrator: Don't require enable-gpios_ |
|  📜  ✅  | `[patches.megous/]` `input-gpio-vibra-Allow-to-use-vcc-supply-alone-to-control-the-v` | `(+13/-5)[1M]` | `gpio-vibra.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: gpio-vibra: Allow to use vcc-supply alone to control the vibrator_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-support-for-the-vibrator-motor` | `(+5/-0)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Add support for the vibrator motor_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Increase-voltage-on-the-vibrator` | `(+2/-2)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Increase voltage on the vibrator_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-PN544-NFC-support` | `(+15/-3)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Add PN544 NFC support_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-powerup-down-support-for-the-3G` | `(+12/-1)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Myl=C3=A8ne=20Josserand?=` _ARM: dts: sun8i-a83t-tbs-a711: Add powerup/down support for the 3G modem_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Add-cedrus-video-codec-support-to-A83T-untes` | `(+10/-0)[1M]` | `sun8i-a83t.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t: Add cedrus video codec support to A83T [untested]_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-suni-a83t-Add-i2s0-pins` | `(+5/-0)[1M]` | `sun8i-a83t.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: suni-a83t: Add i2s0 pins_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-sound-support-via-AC100-codec` | `(+85/-0)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Add sound support via AC100 codec_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-regulators-to-the-accelerometer` | `(+2/-0)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Add regulators to the accelerometer_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-camera-sensors-HM5065-GC2145` | `(+99/-2)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Add camera sensors (HM5065, GC2145)_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Add-flash-led-support` | `(+9/-0)[1M]` | `sun8i-a83t-tbs-a711.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Add flash led support_ |
|  📜  ✅  | `[patches.megous/]` `media-sun6i-csi-Add-support-for-RGB565-and-RGB555` | `(+7/-1)[3M]` | `sun6i_csi.c`, `sun6i_video.c`, `sun6i_csi.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: sun6i-csi: Add support for RGB565 and RGB555_ |
|  📜  ✅  | `[patches.megous/]` `media-sun6i-csi-Add-support-for-missing-16bit-color-formats` | `(+3/-0)[1M]` | `sun6i_csi.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: sun6i-csi: Add support for missing 16bit color formats_ |
|  📜  ✅  | `[patches.megous/]` `mailbox-Allow-to-run-mailbox-while-timekeeping-is-suspended` | `(+24/-4)[1M]` | `mailbox.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _mailbox: Allow to run mailbox while timekeeping is suspended_ |
|  📜  ✅  | `[patches.megous/]` `media-sun6i-csi-Make-the-video-device-respect-user-passed-bytes` | `(+9/-3)[2M]` | `sun6i_video.c`, `sun6i_csi.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: sun6i-csi: Make the video device respect user passed bytesperline_ |
|  📜  ✅  | `[patches.megous/]` `ARM-sunxi-Add-experimental-suspend-to-memory-implementation-for` | `(+46/-0)[1M]` | `sunxi.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: sunxi: Add experimental suspend to memory implementation for A83T_ |
|  📜  ✅  | `[patches.megous/]` `media-sun6i-csi-Add-support-for-multiple-endpoints` | `(+73/-36)[3M]` | `sun6i_csi.c`, `sun6i_video.c`, `sun6i_csi.h` | `Ondrej Jirman` _media: sun6i-csi: Add support for multiple endpoints_ |
|  📜  ✅  | `[patches.megous/]` `ARM-sunxi-sunxi_cpu0_hotplug_support_set-is-not-supported-on-A8` | `(+3/-0)[1M]` | `mc_smp.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: sunxi: sunxi_cpu0_hotplug_support_set is not supported on A83T_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-media-Add-bindings-for-Himax-HM5065-camera-sensor` | `(+49/-0)[1A]` | `hm5065.txt` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _dt-bindings: media: Add bindings for Himax HM5065 camera sensor_ |
|  📜  ✅  | `[patches.megous/]` `firmware-scpi-Add-support-for-sending-a-SCPI_CMD_SET_SYS_PWR_ST` | `(+11/-0)[2M]` | `arm_scpi.c`, `scpi_protocol.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _firmware: scpi: Add support for sending a SCPI_CMD_SET_SYS_PWR_STATE msg_ |
|  📜  ✅  | `[patches.megous/]` `hm5065-yaml-bindings-wip` | `(+90/-0)[1A]` | `hm5065.yaml` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _hm5065: yaml bindings (wip)_ |
|  📜  ✅  | `[patches.megous/]` `ARM-sunxi-Use-SCPI-to-send-suspend-message-to-SCP-on-A83T` | `(+13/-2)[1M]` | `sunxi.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: sunxi: Use SCPI to send suspend message to SCP on A83T_ |
|  📜  ✅  | `[patches.megous/]` `media-hm5065-Add-subdev-driver-for-Himax-HM5065-camera-sensor` | `(+2217/-0)[2M, 1A]` | `hm5065.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: hm5065: Add subdev driver for Himax HM5065 camera sensor_ |
|  📜  ✅  | `[patches.megous/]` `gnss-ubx-Send-soft-powerdown-message-on-suspend` | `(+35/-0)[1M]` | `ubx.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _gnss: ubx: Send soft powerdown message on suspend_ |
|  📜  ✅  | `[patches.megous/]` `MAINTAINERS-Add-entry-for-Himax-HM5065` | `(+6/-0)[1M]` | `MAINTAINERS` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _MAINTAINERS: Add entry for Himax HM5065_ |
|  📜  ✅  | `[patches.megous/]` `media-gc2145-Galaxycore-camera-module-driver` | `(+2256/-0)[2M, 1A]` | `gc2145.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: gc2145: Galaxycore camera module driver_ |
|  📜  ✅  | `[patches.megous/]` `media-gc2145-Added-BGGR-bayer-mode` | `(+5/-0)[1M]` | `gc2145.c` | `Martijn Braam` _media: gc2145: Added BGGR bayer mode_ |
|  📜  ✅  | `[patches.megous/]` `media-gc2145-Disable-debug-output` | `(+2/-2)[1M]` | `gc2145.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: gc2145: Disable debug output_ |
|  📜  ✅  | `[patches.megous/]` `media-gc2145-Add-PIXEL_RATE-HBLANK-and-VBLANK-controls` | `(+264/-211)[1M]` | `gc2145.c` | `Benjamin Schaaf` _media: gc2145: Add PIXEL_RATE, HBLANK and VBLANK controls_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Add-more-framerates-to-the-driver-some-of-them-eve` | `(+11/-3)[1M]` | `ov5640.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: ov5640: Add more framerates to the driver (some of them even work!)_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Experiment-Try-to-disable-denoising-sharpening` | `(+17/-0)[1M]` | `ov5640.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: ov5640: [Experiment] Try to disable denoising/sharpening_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Sleep-after-poweroff-to-ensure-next-poweron-is-not` | `(+1/-0)[1M]` | `ov5640.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: ov5640: Sleep after poweroff to ensure next poweron is not too early_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Don-t-powerup-the-sensor-during-driver-probe` | `(+8/-27)[1M]` | `ov5640.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: ov5640: Don't powerup the sensor during driver probe_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-set-default-ae-target-lower` | `(+1/-1)[1M]` | `ov5640.c` | `Martijn Braam` _media: ov5640: set default ae target lower_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Improve-error-reporting` | `(+6/-2)[1M]` | `ov5640.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: ov5640: Improve error reporting_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Implement-autofocus` | `(+278/-0)[1M]` | `ov5640.c` | `Ondrej Jirman` _media: ov5640: Implement autofocus_ |
|  📜  ✅  | `[patches.megous/]` `net-stmmac-sun8i-Use-devm_regulator_get-for-PHY-regulator` | `(+10/-17)[1M]` | `dwmac-sun8i.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _net: stmmac: sun8i: Use devm_regulator_get for PHY regulator_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Improve-firmware-load-time` | `(+71/-26)[1M]` | `ov5640.c` | `Benjamin Schaaf` _media: ov5640: Improve firmware load time_ |
|  📜  ✅  | `[patches.megous/]` `net-stmmac-sun8i-Rename-PHY-regulator-variable-to-regulator_phy` | `(+9/-9)[1M]` | `dwmac-sun8i.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _net: stmmac: sun8i: Rename PHY regulator variable to regulator_phy_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Fix-focus-commands-blocking-until-complete` | `(+18/-49)[1M]` | `ov5640.c` | `Benjamin Schaaf` _media: ov5640: Fix focus commands blocking until complete_ |
|  📜  ✅  | `[patches.megous/]` `iio-adc-sun4i-gpadc-iio-Allow-to-use-sun5i-a13-gpadc-iio-from-D` | `(+8/-1)[3M]` | `sun5i.dtsi`, `sun4i-gpadc-iio.c`, `sun4i-gpadc.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _iio: adc: sun4i-gpadc-iio: Allow to use sun5i-a13-gpadc-iio from DT_ |
|  📜  ✅  | `[patches.megous/]` `mtd-spi-nor-Add-regulator-support` | `(+34/-6)[2M]` | `core.c`, `spi-nor.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _mtd: spi-nor: Add regulator support_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-De-obfuscate-platform-data-for-keys` | `(+9/-25)[2M]` | `cyttsp4_core.c`, `cyttsp4.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: De-obfuscate platform data for keys_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Remove-useless-indirection-with-driver-platform-d` | `(+128/-149)[3M]` | `cyttsp4_core.c`, `cyttsp4.h`, `cyttsp4_core.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Remove useless indirection with driver/platform data_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Remove-unused-enable_vkeys` | `(+0/-1)[1M]` | `cyttsp4.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Remove unused enable_vkeys_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-De-obfuscate-MT-signals-setup-platform-data` | `(+66/-89)[3M]` | `cyttsp4_core.c`, `cyttsp4.h`, `cyttsp4_core.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: De-obfuscate MT signals setup/platform data_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Clear-the-ids-buffer-in-a-saner-way` | `(+1/-2)[1M]` | `cyttsp4_core.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Clear the ids buffer in a saner way_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-ENOSYS-error-is-ok-when-powering-up` | `(+2/-1)[1M]` | `cyttsp4_core.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: ENOSYS error is ok when powering up_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Faster-recovery-from-failed-wakeup-HACK` | `(+1/-1)[1M]` | `cyttsp4_core.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Faster recovery from failed wakeup (HACK)_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Use-i2c-spi-names-directly-in-the-driver` | `(+3/-5)[3M]` | `cyttsp4_i2c.c`, `cyttsp4_spi.c`, `cyttsp4.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Use i2c/spi names directly in the driver_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Port-the-driver-to-use-device-properties` | `(+149/-189)[2M, 1D]` | `cyttsp4_core.c`, `cyttsp4.h`, `cyttsp4_core.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Port the driver to use device properties_ |
|  📜  ✅  | `[patches.megous/]` `net-stmmac-sun8i-Add-support-for-enabling-a-regulator-for-PHY-I` | `(+19/-1)[1M]` | `dwmac-sun8i.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _net: stmmac: sun8i: Add support for enabling a regulator for PHY I/O pins_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Restart-on-wakeup-wakeup-by-I2C-read-doesn-t-work` | `(+20/-10)[1M]` | `cyttsp4_core.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Restart on wakeup (wakeup by I2C read doesn't work)_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-orange-pi-3-Enable-ethernet` | `(+40/-0)[1M]` | `sun50i-h6-orangepi-3.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: allwinner: orange-pi-3: Enable ethernet_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Fix-warnings` | `(+3/-1)[1M]` | `cyttsp4_core.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Fix warnings_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Make-the-driver-not-hog-the-system-s-workqueue` | `(+16/-7)[2M]` | `cyttsp4_core.c`, `cyttsp4_core.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: cyttsp4: Make the driver not hog the system's workqueue_ |
|  📜  ✅  | `[patches.megous/]` `video-fbdev-eInk-display-driver-for-A13-based-PocketBooks` | `(+1223/-0)[2M, 2A]` | `sun5i-eink.c`, `sun5i-eink-neon.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _video: fbdev: eInk display driver for A13 based PocketBooks_ |
|  📜  ✅  | `[patches.megous/]` `regulator-Add-simple-driver-for-enabling-a-regulator-from-users` | `(+147/-0)[2M, 1A]` | `userspace-consumer-of.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _regulator: Add simple driver for enabling a regulator from userspace_ |
|  📜  ✅  | `[patches.megous/]` `regulator-tp65185x-Add-tp65185x-eInk-panel-regulator-driver` | `(+437/-0)[2M, 1A]` | `tp65185x.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _regulator: tp65185x: Add tp65185x eInk panel regulator driver_ |
|  📜  ✅  | `[patches.megous/]` `regulator-tp65185-Add-hwmon-device-for-reading-temperature` | `(+126/-5)[1M]` | `tp65185x.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _regulator: tp65185: Add hwmon device for reading temperature_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun5i-Add-soc-handle` | `(+1/-1)[1M]` | `sun5i.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun5i: Add soc handle_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun5i-Add-PocketBook-Touch-Lux-3-display-ctp-support` | `(+103/-2)[1M]` | `sun5i-a13-pocketbook-touch-lux-3.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun5i: Add PocketBook Touch Lux 3 display/ctp support_ |
|  📜  ✅  | `[patches.megous/]` `iio-core-Add-option-to-force-identity-mount-matrix` | `(+12/-0)[1M]` | `industrialio-core.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _iio: core: Add option to force identity mount matrix_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun5i-a13-pocketbook-touch-lux-3-Add-RTC-clock-cells` | `(+1/-0)[1M]` | `sun5i-a13-pocketbook-touch-lux-3.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun5i-a13-pocketbook-touch-lux-3: Add RTC clock-cells_ |
|  📜  ✅  | `[patches.megous/]` `input-touchscreen-goodix-Add-config-debugfs-file` | `(+18/-0)[2M]` | `goodix.c`, `goodix.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: touchscreen: goodix: Add config debugfs file_ |
|  📜  ✅  | `[patches.megous/]` `mfd-sun4i-gpadc-Interrupt-numbers-should-start-from-1` | `(+2/-2)[1M]` | `sun4i-gpadc.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _mfd: sun4i-gpadc: Interrupt numbers should start from 1_ |
|  📜  ✅  | `[patches.megous/]` `input-goodix-Add-option-to-power-off-the-controller-during-susp` | `(+38/-0)[2M]` | `goodix.c`, `goodix.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: goodix: Add option to power off the controller during suspend_ |
|  📜  ✅  | `[patches.megous/]` `input-cyttsp4-Fix-probe-oops` | `(+3/-0)[1M]` | `cyttsp4_core.c` | `Ondrej Jirman` _input: cyttsp4: Fix probe oops_ |
|  📜  ✅  | `[patches.megous/]` `input-goodix-Don-t-disable-regulators-during-suspend` | `(+0/-14)[1M]` | `goodix.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: goodix: Don't disable regulators during suspend_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-a64-Fix-LRADC-compatible` | `(+1/-1)[1M]` | `sun50i-a64.dtsi` | `Icenowy Zheng` _arm64: dts: allwinner: a64: Fix LRADC compatible_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-front-back-cameras` | `(+89/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add front/back cameras_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-Type-C-support-for-all-PP-va` | `(+299/-1)[4M]` | `sun50i-a64-pinephone-1.0.dts`, `sun50i-a64-pinephone-1.1.dts`, `sun50i-a64-pinephone.dtsi`, `sun50i-a64-pinephone-1.2.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add Type-C support for all PP variants 1.0-1.2_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-modem-power-manager` | `(+68/-0)[3M]` | `sun50i-a64-pinephone-1.1.dts`, `sun50i-a64-pinephone-1.2.dts`, `sun50i-a64-pinephone-1.0.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add modem power manager_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Fix-BH-modem-manager-behavior` | `(+2/-2)[1M]` | `sun50i-a64-pinephone-1.1.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Fix BH modem manager behavior_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-detailed-OCV-to-capactiy-con` | `(+151/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add detailed OCV to capactiy conversion table_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Shorten-post-power-on-delay-on-m` | `(+3/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Shorten post-power-on-delay on mmcs_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-mount-matrix-for-acceleromet` | `(+3/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add mount matrix for accelerometer_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-support-for-Bluetooth-audio` | `(+1/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `Samuel Holland` _arm64: dts: sun50i-a64-pinephone: Add support for Bluetooth audio_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Enable-internal-HMIC-bias` | `(+4/-0)[1M]` | `sun50i-a64-pinephone-1.0.dts` | `Samuel Holland` _arm64: dts: sun50i-a64-pinephone: Enable internal HMIC bias_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-support-for-modem-audio` | `(+24/-1)[1M]` | `sun50i-a64-pinephone.dtsi` | `Samuel Holland` _arm64: dts: sun50i-a64-pinephone: Add support for modem audio_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Retain-leds-state-in-suspend` | `(+3/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `Miles Alan` _arm64: dts: sun50i-a64-pinephone: Retain leds state in suspend_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Bump-I2C-frequency-to-400kHz` | `(+2/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Bump I2C frequency to 400kHz_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-interrupt-pin-for-WiFi` | `(+2/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add interrupt pin for WiFi_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Power-off-the-touch-controller-i` | `(+1/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Power off the touch controller in sleep_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Don-t-make-lradc-keys-a-wakeup-s` | `(+1/-1)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Don't make lradc keys a wakeup source_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Set-minimum-backlight-duty-cycle` | `(+2/-31)[2M]` | `sun50i-a64-pinephone-1.2.dts`, `sun50i-a64-pinephone-1.1.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Set minimum backlight duty cycle to 10%_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-supply-for-i2c-bus-to-anx768` | `(+3/-0)[3M]` | `sun50i-a64-pinephone-1.0.dts`, `sun50i-a64-pinephone-1.1.dts`, `sun50i-a64-pinephone-1.2.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add supply for i2c bus to anx7688_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Workaround-broken-HDMI-HPD-signa` | `(+15/-3)[3M]` | `sun50i-a64-pinephone-1.0.dts`, `sun50i-a64-pinephone-1.1.dts`, `sun50i-a64-pinephone-1.2.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Workaround broken HDMI HPD signal_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-AF8133J-to-PinePhone` | `(+9/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `Icenowy Zheng` _arm64: dts: sun50i-a64-pinephone: Add AF8133J to PinePhone_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-mount-matrix-for-PinePhone-m` | `(+6/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `Shoji Keita` _arm64: dts: sun50i-a64-pinephone: Add mount-matrix for PinePhone magnetometers._ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Add-support-for-Pinephone-keyboa` | `(+136/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64-pinephone: Add support for Pinephone keyboard_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-pinephone-Enable-Pinephone-Keyboard-power-` | `(+9/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `Ondrej Jirman` _arm64: dts: sun50i-a64-pinephone: Enable Pinephone Keyboard power manager_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-Add-missing-trip-points-for-GPU` | `(+18/-0)[1M]` | `sun50i-a64.dtsi` | `Ondrej Jirman` _arm64: dts: sun50i-a64: Add missing trip points for GPU_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-sun50i-a64-pinephone-Add-support-for-Pineph` | `(+30/-12)[2M, 1A]` | `sun50i-a64-pinephone-1.2b.dts`, `sun50i-a64-pinephone.dtsi`, `Makefile` | `Ondrej Jirman` _arm64: dts: allwinner: sun50i-a64-pinephone: Add support for Pinephone 1.2 beta_ |
|  📜  ✅  | `[patches.megous/]` `tty-serial-8250-dw-Use-fifo-size-from-DTS` | `(+7/-0)[2M]` | `8250_dw.c`, `8250_port.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _tty: serial: 8250-dw: Use fifo-size from DTS_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-sun50i-a64-Set-fifo-size-for-uarts` | `(+5/-0)[1M]` | `sun50i-a64.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: sun50i-a64: Set fifo-size for uarts_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Set-fifo-size-for-uarts` | `(+5/-0)[1M]` | `sun8i-a83t.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t: Set fifo-size for uarts_ |
|  📜  ✅  | `[patches.megous/]` `Mark-some-slow-drivers-for-async-probe-with-PROBE_PREFER_ASYNCH` | `(+2/-0)[2M]` | `bma180.c`, `i2c.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _Mark some slow drivers for async probe with PROBE_PREFER_ASYNCHRONOUS_ |
|  📜  ✅  | `[patches.megous/]` `clk-Implement-protected-clocks-for-all-OF-clock-providers` | `(+87/-0)[3M]` | `clk-conf.c`, `clk.c`, `clk.h` | `Samuel Holland` _clk: Implement protected-clocks for all OF clock providers_ |
|  📜  ✅  | `[patches.megous/]` `arm64-xor-Select-32regs-without-benchmark-to-speed-up-boot` | `(+4/-10)[1M]` | `xor.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: xor: Select 32regs without benchmark to speed up boot_ |
|  📜  ✅  | `[patches.megous/]` `Revert-clk-qcom-Support-protected-clocks-property` | `(+0/-18)[1M]` | `common.c` | `Samuel Holland` _Revert "clk: qcom: Support 'protected-clocks' property"_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sunxi-a83t-Protect-SCP-clocks` | `(+2/-0)[1M]` | `sun8i-a83t.dtsi` | `Samuel Holland` _ARM: dts: sunxi: a83t: Protect SCP clocks_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sunxi-h3-h5-Protect-SCP-clocks` | `(+2/-0)[1M]` | `sunxi-h3-h5.dtsi` | `Samuel Holland` _ARM: dts: sunxi: h3/h5: Protect SCP clocks_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-a64-Protect-SCP-clocks` | `(+2/-0)[1M]` | `sun50i-a64.dtsi` | `Samuel Holland` _arm64: dts: allwinner: a64: Protect SCP clocks_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-h6-Protect-SCP-clocks` | `(+2/-0)[1M]` | `sun50i-h6.dtsi` | `Samuel Holland` _arm64: dts: allwinner: h6: Protect SCP clocks_ |
|  📜  ✅  | `[patches.megous/]` `bus-sunxi-rsb-Always-check-register-address-validity` | `(+3/-0)[1M]` | `sunxi-rsb.c` | `Samuel Holland` _bus: sunxi-rsb: Always check register address validity_ |
|  📜  ✅  | `[patches.megous/]` `bus-sunxi-rsb-Use-devm_platform_ioremap_resource` | `(+2/-3)[1M]` | `sunxi-rsb.c` | `Samuel Holland` _bus: sunxi-rsb: Use devm_platform_ioremap_resource_ |
|  📜  ✅  | `[patches.megous/]` `firmware-arm_scpi-Support-unidirectional-mailbox-channels` | `(+46/-12)[1M]` | `arm_scpi.c` | `Samuel Holland` _firmware: arm_scpi: Support unidirectional mailbox channels_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sunxi-a83t-Add-SCPI-protocol` | `(+21/-0)[1M]` | `sun8i-a83t.dtsi` | `Samuel Holland` _ARM: dts: sunxi: a83t: Add SCPI protocol_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sunxi-h3-h5-Add-SCPI-protocol` | `(+33/-0)[3M]` | `sun8i-h3.dtsi`, `sun50i-h5.dtsi`, `sunxi-h3-h5.dtsi` | `Samuel Holland` _ARM: dts: sunxi: h3/h5: Add SCPI protocol_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-a64-Add-SCPI-protocol` | `(+20/-0)[1M]` | `sun50i-a64.dtsi` | `Samuel Holland` _arm64: dts: allwinner: a64: Add SCPI protocol_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-h6-Add-SCPI-protocol` | `(+20/-0)[1M]` | `sun50i-h6.dtsi` | `Samuel Holland` _arm64: dts: allwinner: h6: Add SCPI protocol_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-tbs-a711-Give-Linux-more-privileges-over-SCP` | `(+5/-2)[1M]` | `sun8i-a83t.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sun8i-a83t-tbs-a711: Give Linux more privileges over SCPI_ |
|  📜  ✅  | `[patches.megous/]` `rtc-sun6i-Allow-RTC-wakeup-after-shutdown` | `(+11/-1)[1M]` | `rtc-sun6i.c` | `Samuel Holland` _rtc: sun6i: Allow RTC wakeup after shutdown_ |
|  📜  ✅  | `[patches.megous/]` `mmc-sunxi-mmc-Remove-runtime-PM` | `(+19/-16)[1M]` | `sunxi-mmc.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _mmc: sunxi-mmc: Remove runtime-PM_ |
|  📜  ✅  | `[patches.megous/]` `usb-quirks-Add-USB_QUIRK_RESET-for-Quectel-EG25G-Modem` | `(+3/-0)[1M]` | `quirks.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: quirks: Add USB_QUIRK_RESET for Quectel EG25G Modem_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-pinephone-Add-reboot-mode-driver` | `(+37/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: pinephone: Add reboot mode driver_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-codec-es8316-DAC-Soft-Ramp-Rate-is-just-a-2-bit-control` | `(+1/-1)[1M]` | `es8316.c` | `Ondrej Jirman` _ASoC: codec: es8316: "DAC Soft Ramp Rate" is just a 2 bit control_ |
|  📜  ✅  | `[patches.megous/]` `misc-modem-power-Power-manager-for-modems` | `(+2000/-0)[2M, 1A]` | `modem-power.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _misc: modem-power: Power manager for modems_ |
|  📜  ✅  | `[patches.megous/]` `media-cedrus-Fix-missing-cleanup-in-error-path` | `(+2/-0)[1M]` | `cedrus.c` | `Samuel Holland` _media: cedrus: Fix missing cleanup in error path_ |
|  📜  ✅  | `[patches.megous/]` `media-cedrus-Fix-failure-to-clean-up-hardware-on-probe-failure` | `(+3/-1)[1M]` | `cedrus.c` | `Samuel Holland` _media: cedrus: Fix failure to clean up hardware on probe failure_ |
|  📜  ✅  | `[patches.megous/]` `Revert-drm-sun4i-lvds-Invert-the-LVDS-polarity` | `(+3/-1)[1M]` | `sun4i_tcon.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _Revert "drm/sun4i: lvds: Invert the LVDS polarity"_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-Enforce-consistent-MMC-numbering` | `(+18/-0)[3M]` | `sun50i-a64.dtsi`, `sun50i-h5.dtsi`, `sun50i-h6.dtsi` | `Samuel Holland` _arm64: dts: allwinner: Enforce consistent MMC numbering_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sunxi-Add-aliases-for-MMC` | `(+18/-0)[3M]` | `sun5i.dtsi`, `sun8i-a83t.dtsi`, `sun8i-h3.dtsi` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ARM: dts: sunxi: Add aliases for MMC_ |
|  📜  ✅  | `[patches.megous/]` `of-property-fw_devlink-Support-allwinner-sram-links` | `(+22/-0)[1M]` | `property.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _of: property: fw_devlink: Support allwinner,sram links_ |
|  📜  ✅  | `[patches.megous/]` `rtw89-Fix-crash-by-loading-compressed-firmware-file` | `(+12/-6)[2M]` | `fw.c`, `core.h` | `Takashi Iwai` _rtw89: Fix crash by loading compressed firmware file_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-Unify-sun8i_-_layer-structs` | `(+38/-48)[6M]` | `sun8i_ui_layer.h`, `sun8i_vi_layer.h`, `sun8i_mixer.h`, `sun8i_ui_layer.c`, `sun8i_vi_layer.c`, `sun8i_mixer.c` | `Ondrej Jirman` _drm/sun4i: Unify sun8i_*_layer structs_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-Add-more-parameters-to-sunxi_engine-commit-callback` | `(+18/-6)[4M]` | `sunxi_engine.h`, `sun8i_mixer.c`, `sun4i_backend.c`, `sun4i_crtc.c` | `Ondrej Jirman` _drm/sun4i: Add more parameters to sunxi_engine commit callback_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-Fix-layer-zpos-change-atomic-modesetting` | `(+81/-143)[4M]` | `sun8i_vi_layer.c`, `sun8i_ui_layer.c`, `sun8i_mixer.c`, `sun8i_mixer.h` | `Ondrej Jirman` _drm/sun4i: Fix layer zpos change/atomic modesetting_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-decouple-TCON_DCLK_DIV-value-from-pll_mipi-dotclock-r` | `(+25/-19)[1M]` | `sun4i_tcon.c` | `Roman Beranek` _drm/sun4i: decouple TCON_DCLK_DIV value from pll_mipi/dotclock ratio_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-Implement-gamma-correction` | `(+58/-1)[3M]` | `sun4i_tcon.c`, `sun4i_crtc.c`, `sun4i_tcon.h` | `Vasily Khoruzhick` _drm/sun4i: Implement gamma correction_ |
|  📜  ✅  | `[patches.megous/]` `drm-panel-st7703-Improve-the-power-up-down-sequence-of-the-pane` | `(+5/-5)[1M]` | `panel-sitronix-st7703.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _drm/panel: st7703: Improve the power up/down sequence of the panel_ |
|  📜  ✅  | `[patches.megous/]` `drm-panel-st7703-Fix-xbd599-timings-to-make-refresh-rate-exactl` | `(+4/-4)[1M]` | `panel-sitronix-st7703.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _drm/panel: st7703: Fix xbd599 timings to make refresh rate exactly 60.006Hz_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-add-support-for-rate-resetting-notifier` | `(+34/-0)[2M]` | `ccu_common.c`, `ccu_common.h` | `Icenowy Zheng` _clk: sunxi-ng: add support for rate resetting notifier_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-a64-try-to-keep-TCON0-clock-in-CCU` | `(+25/-2)[1M]` | `ccu-sun50i-a64.c` | `Icenowy Zheng` _clk: sunxi-ng: a64: try to keep TCON0 clock in CCU_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-tcon-hand-over-the-duty-to-keep-TCON0-clock-to-CCU-on` | `(+14/-2)[2M]` | `sun4i_tcon.c`, `sun4i_tcon.h` | `Ondrej Jirman` _drm/sun4i: tcon: hand over the duty to keep TCON0 clock to CCU on A64_ |
|  📜  ✅  | `[patches.megous/]` `drm-sun4i-Support-taking-over-display-pipeline-state-from-p-boo` | `(+167/-2)[11M]` | `sun8i_mixer.c`, `pwm_bl.c`, `sun4i_tcon.c`, `panel-sitronix-st7703.c`, `drm_fb_helper.c`, `phy-sun6i-mipi-dphy.c`, `sun6i_mipi_dsi.c`, `ccu-sun50i-a64.c`, `sun8i_mixer.h`, `sun4i_tcon.h`, `sun6i_mipi_dsi.h` | `Ondrej Jirman` _drm/sun4i: Support taking over display pipeline state from p-boot_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-sun50i-a64-Switch-parent-of-MIPI-DSI-to-periph0-1x` | `(+10/-1)[1M]` | `ccu-sun50i-a64.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _clk: sunxi-ng: sun50i-a64: Switch parent of MIPI-DSI to periph0(1x)_ |
|  📜  ✅  | `[patches.megous/]` `drm-lima-add-LIMA_BO_FLAG_FORCE_VA` | `(+46/-13)[5M]` | `lima_drv.c`, `lima_vm.c`, `lima_drm.h`, `lima_gem.c`, `lima_gem.h` | `Qiang Yu` _drm/lima: add LIMA_BO_FLAG_FORCE_VA_ |
|  📜  ✅  | `[patches.megous/]` `video-pwm_bl-Allow-to-change-lth_brightness-via-sysfs` | `(+70/-2)[1M]` | `pwm_bl.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _video: pwm_bl: Allow to change lth_brightness via sysfs_ |
|  📜  ✅  | `[patches.megous/]` `phy-allwinner-sun4i-usb-Add-support-for-usb_role_switch` | `(+51/-1)[2M]` | `phy-sun4i-usb.c`, `Kconfig` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _phy: allwinner: sun4i-usb: Add support for usb_role_switch_ |
|  📜  ✅  | `[patches.megous/]` `regulator-axp20x-Add-support-for-vin-supply-for-drivevbus` | `(+27/-3)[1M]` | `axp20x-regulator.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _regulator: axp20x: Add support for vin-supply for drivevbus_ |
|  📜  ✅  | `[patches.megous/]` `regulator-axp20x-Turn-N_VBUSEN-to-input-on-x-powers-sense-vbus-` | `(+12/-0)[2M]` | `axp20x-regulator.c`, `sun50i-a64-pinephone-1.2.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _regulator: axp20x: Turn N_VBUSEN to input on x-powers,sense-vbus-en_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-usb-power-Support-input-current-limit` | `(+104/-1)[2M]` | `axp20x_usb_power.c`, `axp20x.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: axp20x-usb-power: Support input current limit_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-Add-support-for-USB_BC_ENABLED-and-USB_DCP_INPUT_C` | `(+4/-0)[2M]` | `power_supply_sysfs.c`, `power_supply.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: Add support for USB_BC_ENABLED and USB_DCP_INPUT_CURRENT_LIMIT_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-Export-usb_type-usb_bc_enabled-dcp-current-` | `(+144/-10)[2M]` | `axp20x_usb_power.c`, `axp20x.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: axp20x: Export usb_type, usb_bc_enabled, dcp current limit_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-usb-power-Don-t-require-exact-values-for-in` | `(+17/-30)[1M]` | `axp20x_usb_power.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: axp20x-usb-power: Don't require exact values for input current limit_ |
|  📜  ✅  | `[patches.megous/]` `drm-bridge-dw-hdmi-Allow-to-accept-HPD-status-from-other-driver` | `(+59/-4)[1M]` | `dw-hdmi.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _drm: bridge: dw-hdmi: Allow to accept HPD status from other drivers_ |
|  📜  ✅  | `[patches.megous/]` `drm-bridge-dw-hdmi-Report-HDMI-hotplug-events` | `(+2/-2)[1M]` | `dw-hdmi.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _drm: bridge: dw-hdmi: Report HDMI hotplug events_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-anx7688-Add-driver-for-ANX7688-USB-C-HDMI-bridge` | `(+2254/-0)[2M, 1A]` | `anx7688.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: anx7688: Add driver for ANX7688 USB-C HDMI bridge_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-axp20x-adc-allow-to-use-TS-pin-as-GPADC` | `(+5/-0)[1M]` | `x-powers,axp209-adc.yaml` | `Icenowy Zheng` _dt-bindings: axp20x-adc: allow to use TS pin as GPADC_ |
|  📜  ✅  | `[patches.megous/]` `iio-adc-axp20x_adc-allow-to-set-TS-pin-to-GPADC-mode` | `(+6/-0)[1M]` | `axp20x_adc.c` | `Icenowy Zheng` _iio: adc: axp20x_adc: allow to set TS pin to GPADC mode_ |
|  📜  ✅  | `[patches.megous/]` `power-axp20x_battery-Allow-to-set-target-voltage-to-4.35V` | `(+5/-0)[1M]` | `axp20x_battery.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: axp20x_battery: Allow to set target voltage to 4.35V_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x_battery-Add-support-for-reporting-OCV` | `(+23/-0)[1M]` | `axp20x_battery.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: axp20x_battery: Add support for reporting OCV_ |
|  📜  ✅  | `[patches.megous/]` `regulator-axp20x-Enable-over-temperature-protection-and-16s-res` | `(+7/-0)[1M]` | `axp20x-regulator.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _regulator: axp20x: Enable over-temperature protection and 16s reset function_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x_battery-Setup-thermal-regulation-experiment` | `(+54/-0)[1M]` | `axp20x_battery.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: axp20x_battery: Setup thermal regulation (experimental)_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x_battery-Fix-charging-done-detection` | `(+3/-2)[1M]` | `axp20x_battery.c` | `Samuel Holland` _power: supply: axp20x_battery: Fix charging done detection_ |
|  📜  ✅  | `[patches.megous/]` `mfd-axp20x-Add-battery-IRQ-resources` | `(+36/-0)[1M]` | `axp20x.c` | `Samuel Holland` _mfd: axp20x: Add battery IRQ resources_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x_battery-Send-uevents-for-status-changes` | `(+53/-2)[1M]` | `axp20x_battery.c` | `Samuel Holland` _power: supply: axp20x_battery: Send uevents for status changes_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x_battery-Monitor-battery-health` | `(+56/-2)[1M]` | `axp20x_battery.c` | `Samuel Holland` _power: supply: axp20x_battery: Monitor battery health_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-usb-power-Change-Vbus-hold-voltage-to-4.5V` | `(+12/-0)[1M]` | `axp20x_usb_power.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: axp20x-usb-power: Change Vbus hold voltage to 4.5V_ |
|  📜  ✅  | `[patches.megous/]` `power-axp803-Add-interrupts-for-low-battery-power-condition` | `(+4/-0)[2M]` | `axp20x.c`, `axp20x_battery.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: axp803: Add interrupts for low battery power condition_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-battery-Support-POWER_SUPPLY_PROP_CHARGE_BE` | `(+30/-0)[1M]` | `axp20x_battery.c` | `Ondrej Jirman` _power: supply: axp20x-battery: Support POWER_SUPPLY_PROP_CHARGE_BEHAVIOUR_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-battery-Enable-poweron-by-RTC-alarm` | `(+5/-0)[1M]` | `axp20x_battery.c` | `Ondrej Jirman` _power: supply: axp20x-battery: Enable poweron by RTC alarm_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-axp20x-battery-Add-support-for-POWER_SUPPLY_PROP_E` | `(+18/-4)[1M]` | `axp20x_battery.c` | `Ondrej Jirman` _power: supply: axp20x-battery: Add support for POWER_SUPPLY_PROP_ENERGY_FULL_DESIGN_ |
|  📜  ✅  | `[patches.megous/]` `mfd-axp20x-Improve-interrupt-order-for-POK-handling-during-slee` | `(+5/-5)[1M]` | `axp20x.h` | `Ondrej Jirman` _mfd: axp20x: Improve interrupt order for POK handling during sleep_ |
|  📜  ✅  | `[patches.megous/]` `ASOC-sun9i-hdmi-audio-Initial-implementation` | `(+189/-0)[2M, 1A]` | `sun9i-hdmi-audio.c`, `Kconfig`, `Makefile` | `Jernej Skrabec` _ASOC: sun9i-hdmi-audio: Initial implementation_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sunxi-h3-h5-Add-hdmi-sound-card` | `(+15/-0)[1M]` | `sunxi-h3-h5.dtsi` | `Jernej Skrabec` _ARM: dts: sunxi: h3/h5: Add hdmi sound card_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-h3-Enable-hdmi-sound-card-on-boards-with-hdmi` | `(+80/-0)[10M]` | `sun8i-h3-beelink-x2.dts`, `sun8i-h3-emlid-neutis-n5h3-devboard.dts`, `sun8i-h3-nanopi-m1-plus.dts`, `sun8i-h3-nanopi-m1.dts`, `sun8i-h3-orangepi-2.dts`, `sun8i-h3-orangepi-lite.dts`, `sun8i-h3-orangepi-one.dts`, `sun8i-h3-orangepi-pc.dts`, `sun8i-h3-orangepi-zero-plus2.dts`, `sun8i-h3-rervision-dvk.dts` | `Jernej Skrabec` _ARM: dts: sun8i: h3: Enable hdmi sound card on boards with hdmi_ |
|  📜  ✅  | `[patches.megous/]` `sunxi-Use-dev_err_probe-to-handle-EPROBE_DEFER-errors` | `(+25/-12)[5M]` | `phy-sun4i-usb.c`, `i2c-gpio.c`, `phy-sun6i-mipi-dphy.c`, `topology.c`, `panel-sitronix-st7703.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _sunxi: Use dev_err_probe to handle EPROBE_DEFER errors_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-h2-plus-bananapi-m2-zero-Enable-HDMI-audio` | `(+8/-0)[1M]` | `sun8i-h2-plus-bananapi-m2-zero.dts` | `Jernej Skrabec` _ARM: dts: sun8i: h2-plus: bananapi-m2-zero: Enable HDMI audio_ |
|  📜  ✅  | `[patches.megous/]` `thermal-sun8i-Be-loud-when-probe-fails` | `(+29/-6)[1M]` | `sun8i_thermal.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _thermal: sun8i: Be loud when probe fails_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Add-hdmi-sound-card` | `(+15/-0)[1M]` | `sun8i-a83t.dtsi` | `Jernej Skrabec` _ARM: dts: sun8i: a83t: Add hdmi sound card_ |
|  📜  ✅  | `[patches.megous/]` `i2c-mv64xxx-Don-t-make-a-fuss-when-pinctrl-recovery-state-is-no` | `(+8/-0)[1M]` | `i2c-mv64xxx.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _i2c: mv64xxx: Don't make a fuss when pinctrl recovery state is not present_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Enable-hdmi-sound-card-on-boards-with-hdmi` | `(+16/-0)[2M]` | `sun8i-a83t-bananapi-m3.dts`, `sun8i-a83t-cubietruck-plus.dts` | `Jernej Skrabec` _ARM: dts: sun8i: a83t: Enable hdmi sound card on boards with hdmi_ |
|  📜  ✅  | `[patches.megous/]` `iio-st_sensors-Don-t-report-error-when-the-device-is-not-presen` | `(+9/-1)[1M]` | `st_sensors_core.c` | `Ondrej Jirman` _iio: st_sensors: Don't report error when the device is not present on I2C bus_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-r40-Add-hdmi-sound-card` | `(+15/-0)[1M]` | `sun8i-r40.dtsi` | `Jernej Skrabec` _ARM: dts: sun8i: r40: Add hdmi sound card_ |
|  📜  ✅  | `[patches.megous/]` `opp-core-Avoid-confusing-error-when-no-regulator-is-defined-in-` | `(+5/-0)[1M]` | `core.c` | `Ondrej Jirman` _opp: core: Avoid confusing error when no regulator is defined in DT_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-r40-bananapi-m2-ultra-Enable-HDMI-audio` | `(+8/-0)[1M]` | `sun8i-r40-bananapi-m2-ultra.dts` | `Jernej Skrabec` _ARM: dts: sun8i: r40: bananapi-m2-ultra: Enable HDMI audio_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-v40-bananapi-m2-berry-Enable-HDMI-audio` | `(+8/-0)[1M]` | `sun8i-v40-bananapi-m2-berry.dts` | `Jernej Skrabec` _ARM: dts: sun8i: v40: bananapi-m2-berry: Enable HDMI audio_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-h6-Add-hdmi-sound-card` | `(+15/-0)[1M]` | `sun50i-h6.dtsi` | `Jernej Skrabec` _arm64: dts: allwinner: h6: Add hdmi sound card_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-h6-Enable-hdmi-sound-card-on-boards-with-hd` | `(+32/-0)[4M]` | `sun50i-h6-beelink-gs1.dts`, `sun50i-h6-orangepi-3.dts`, `sun50i-h6-orangepi.dtsi`, `sun50i-h6-pine-h64.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: allwinner: h6: Enable hdmi sound card on boards with hdmi_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-a64-Add-hdmi-sound-card` | `(+15/-0)[1M]` | `sun50i-a64.dtsi` | `Jernej Skrabec` _arm64: dts: allwinner: a64: Add hdmi sound card_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-a64-Enable-hdmi-sound-card-on-boards-with-h` | `(+55/-0)[7M]` | `sun50i-a64-bananapi-m64.dts`, `sun50i-a64-nanopi-a64.dts`, `sun50i-a64-orangepi-win.dts`, `sun50i-a64-pine64.dts`, `sun50i-a64-sopine-baseboard.dts`, `sun50i-a64-teres-i.dts`, `sun50i-a64-olinuxino.dts` | `Jernej Skrabec` _arm64: dts: allwinner: a64: Enable hdmi sound card on boards with hdmi_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-h5-Enable-hdmi-sound-card-on-boards-with-hd` | `(+32/-0)[4M]` | `sun50i-h5-emlid-neutis-n5-devboard.dts`, `sun50i-h5-orangepi-pc2.dts`, `sun50i-h5-orangepi-prime.dts`, `sun50i-h5-orangepi-zero-plus2.dts` | `Jernej Skrabec` _arm64: dts: allwinner: h5: Enable hdmi sound card on boards with hdmi_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-sun50i-codec-analog-Add-support-for-internal-bias` | `(+27/-0)[1M]` | `sun50i-codec-analog.c` | `Arnaud Ferraris` _ASoC: sun50i-codec-analog: Add support for internal bias_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-sun50i-codec-analog-Move-suspend-resume-to-set_bias_level` | `(+19/-11)[1M]` | `sun50i-codec-analog.c` | `Samuel Holland` _ASoC: sun50i-codec-analog: Move suspend/resume to set_bias_level_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-sun50i-codec-analog-Enable-jack-detection-on-startup` | `(+31/-1)[1M]` | `sun50i-codec-analog.c` | `Arnaud Ferraris` _ASoC: sun50i-codec-analog: Enable jack detection on startup_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-sun8i-codec-Enable-bus-clock-at-STANDBY-and-higher-bias` | `(+33/-8)[1M]` | `sun8i-codec.c` | `Samuel Holland` _ASoC: sun8i-codec: Enable bus clock at STANDBY and higher bias_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-sun8i-codec-Implement-jack-and-accessory-detection` | `(+269/-0)[1M]` | `sun8i-codec.c` | `Arnaud Ferraris` _ASoC: sun8i-codec: Implement jack and accessory detection_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-ec25-New-codec-driver-for-the-EC25-modem` | `(+99/-0)[2M, 1A]` | `ec25.c`, `Kconfig`, `Makefile` | `Samuel Holland` _ASoC: ec25: New codec driver for the EC25 modem_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-a64-Increase-PLL_AUDIO-base-frequency` | `(+32/-9)[1M]` | `ccu-sun50i-a64.c` | `Samuel Holland` _clk: sunxi-ng: a64: Increase PLL_AUDIO base frequency_ |
|  📜  ✅  | `[patches.megous/]` `sound-soc-sun8i-codec-Add-support-for-digital-part-of-the-AC100` | `(+218/-8)[2M]` | `sun8i-codec.c`, `Kconfig` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _sound: soc: sun8i-codec: Add support for digital part of the AC100 codec_ |
|  📜  ✅  | `[patches.megous/]` `sound-soc-sun8i-codec-Drop-debug-statements` | `(+1/-8)[1M]` | `sun8i-codec.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _sound: soc: sun8i-codec: Drop debug statements_ |
|  📜  ✅  | `[patches.megous/]` `sound-soc-ac100-codec-Support-analog-part-of-X-Powers-AC100-cod` | `(+1007/-0)[4M, 1A]` | `ac100-codec.c`, `Kconfig`, `ac100.c`, `ac100.h`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _sound: soc: ac100-codec: Support analog part of X-Powers AC100 codec_ |
|  📜  ✅  | `[patches.megous/]` `sound-soc-ac100-Make-sure-we-shutdown-the-audio-outputs-on-rebo` | `(+11/-0)[1M]` | `ac100-codec.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _sound: soc: ac100: Make sure we shutdown the audio outputs on reboot_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-sunxi-sun8i-codec-Improve-jack-button-handling-and-mic-det` | `(+188/-65)[2M]` | `sun8i-codec.c`, `sun50i-codec-analog.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _ASoC: sunxi: sun8i-codec: Improve jack button handling and mic detection_ |
|  📜  ✅  | `[patches.megous/]` `arm64-dts-allwinner-a64-pinetab-add-front-camera` | `(+44/-6)[1M]` | `sun50i-a64-pinetab.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _arm64: dts: allwinner: a64: pinetab: add front camera_ |
|  📜  ✅  | `[patches.megous/]` `clk-sunxi-ng-Export-CLK_DRAM-for-devfreq` | `(+2/-7)[2M]` | `sun8i-a83t-ccu.h`, `ccu-sun8i-a83t.h` | `Samuel Holland` _clk: sunxi-ng: Export CLK_DRAM for devfreq_ |
|  📜  ✅  | `[patches.megous/]` `Make-microbuttons-on-Orange-Pi-PC-and-PC-2-work-as-power-off-bu` | `(+2/-2)[2M]` | `sun8i-h3-orangepi-one.dts`, `sun50i-h5-orangepi-pc2.dts` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _Make microbuttons on Orange Pi PC and PC 2 work as power off buttons_ |
|  📜  ✅  | `[patches.megous/]` `arm64-allwinner-dts-a64-enable-K101-IM2BYL02-panel-for-PineTab` | `(+3/-5)[1M]` | `sun50i-a64-pinetab.dts` | `Icenowy Zheng` _arm64: allwinner: dts: a64: enable K101-IM2BYL02 panel for PineTab_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Add-MBUS-node` | `(+15/-0)[1M]` | `sun8i-a83t.dtsi` | `Samuel Holland` _ARM: dts: sun8i: a83t: Add MBUS node_ |
|  📜  ✅  | `[patches.megous/]` `Add-support-for-my-private-Sapomat-device` | `(+35/-0)[1M, 1A]` | `sun8i-h3-orangepi-pc-sapomat.dts`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _Add support for my private Sapomat device_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-h3-orange-pi-one-Enable-all-gpio-header-UARTs` | `(+6/-3)[1M]` | `sun8i-h3-orangepi-one.dts` | `Ondrej Jirman` _ARM: dts: sun8i-h3-orange-pi-one: Enable all gpio header UARTs_ |
|  📜  ✅  | `[patches.megous/]` `Defconfigs-for-all-my-devices` | `(+5112/-0)[8A]` | `pinebook_pro_defconfig`, `pinephone_pro_defconfig`, `pinephone_defconfig`, `orangepi_defconfig`, `pinephone_multidist_defconfig`, `tbs_a711_defconfig`, `pocketbook_touch_lux_3_defconfig` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _Defconfigs for all my devices_ |
|  📜  ✅  | `[patches.megous/]` `sdhci-arasan-Add-runtime-PM-support` | `(+86/-2)[1M]` | `sdhci-of-arasan.c` | `Manish Narani` _sdhci: arasan: Add runtime PM support_ |
|  📜  ✅  | `[patches.megous/]` `mtd-spi-nor-gigadevice-add-support-for-gd25lq128e` | `(+4/-0)[1M]` | `gigadevice.c` | `Martijn Braam` _mtd: spi-nor: gigadevice: add support for gd25lq128e_ |
|  📜  ✅  | `[patches.megous/]` `drm-bridge-dw-mipi-dsi-Fix-enable-disable-of-dsi-controller` | `(+36/-15)[1M]` | `dw-mipi-dsi.c` | `Ondrej Jirman` _drm: bridge: dw-mipi-dsi: Fix enable/disable of dsi controller_ |
|  📜  ✅  | `[patches.megous/]` `drm-panel-hx8394-Add-driver-for-HX8394-based-HannStar-HSD060BHW` | `(+418/-0)[2M, 1A]` | `panel-himax-hx8394.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Kamil=20Trzci=C5=84ski?=` _drm: panel: hx8394: Add driver for HX8394 based HannStar HSD060BHW4 panel_ |
|  📜  ✅  | `[patches.megous/]` `drm-panel-hx8394-Improve-the-panel-driver-make-it-work-with-DSI` | `(+52/-32)[1M]` | `panel-himax-hx8394.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _drm: panel: hx8394: Improve the panel driver (make it work with DSI fixes)_ |
|  📜  ✅  | `[patches.megous/]` `drm-panel-hx8394-Fix-mode-to-have-refresh-rate-of-60-Hz` | `(+6/-21)[1M]` | `panel-himax-hx8394.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _drm: panel: hx8394: Fix mode to have refresh rate of 60 Hz_ |
|  📜  ✅  | `[patches.megous/]` `drm-panel-hx8394-Add-mode-init-sequence-update-via-firmware-loa` | `(+77/-1)[1M]` | `panel-himax-hx8394.c` | `Ondrej Jirman` _drm: panel: hx8394: Add mode/init sequence update via firmware load_ |
|  📜  ✅  | `[patches.megous/]` `input-touchscreen-goodix-Respect-IRQ-flags-from-DT-when-asked-t` | `(+7/-1)[2M]` | `goodix.c`, `goodix.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _input: touchscreen: goodix: Respect IRQ flags from DT when asked to_ |
|  📜  ✅  | `[patches.megous/]` `power-rk818-Configure-rk808-clkout2-function` | `(+3/-0)[2M]` | `rk808.h`, `rk808.c` | `=?UTF-8?q?Kamil=20Trzci=C5=84ski?=` _power: rk818: Configure `rk808-clkout2` function_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Add-battery-driver-for-RK818` | `(+3863/-3)[4M, 2A]` | `rk818_battery.c`, `rk818_battery.h`, `rk808.h`, `rk808.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Kamil=20Trzci=C5=84ski?=` _power: supply: rk818-battery: Add battery driver for RK818_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Use-a-more-propper-compatible-string` | `(+3/-3)[2M]` | `rk818_battery.c`, `rk808.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: rk818-battery: Use a more propper compatible string_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-charger-Implement-charger-driver-for-RK818-P` | `(+660/-0)[3M, 1A]` | `rk818_charger.c`, `Kconfig`, `rk808.c`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: rk818-charger: Implement charger driver for RK818 PMIC_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-charger-Change-charger-type-to-MAINS` | `(+1/-1)[1M]` | `rk818_charger.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: rk818-charger: Change charger type to MAINS_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Report-charging-status-based-on-char` | `(+1/-62)[1M]` | `rk818_battery.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _power: supply: rk818-battery: Report charging status based on charging current_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Drop-dependency-on-framebuffer` | `(+5/-38)[1M]` | `rk818_battery.c` | `Ondrej Jirman` _power: supply: rk818-battery: Drop dependency on framebuffer_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-charger-Unify-rk818-charger-and-rk818-batter` | `(+95/-33)[4M]` | `rk818_charger.c`, `rk818_battery.c`, `Kconfig`, `Makefile` | `Ondrej Jirman` _power: supply: rk818-charger: Unify rk818-charger and rk818-battery_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Speed-up-battery-current-readout` | `(+2/-2)[1M]` | `rk818_battery.c` | `Ondrej Jirman` _power: supply: rk818-battery: Speed up battery current readout_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-charger-Delay-applying-input-current-limit-u` | `(+17/-0)[1M]` | `rk818_charger.c` | `Ondrej Jirman` _power: supply: rk818-charger: Delay applying input current limit until first BC detection finishes_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Don-t-auto-poweroff-the-PMIC-on-low-` | `(+9/-6)[1M]` | `rk818_battery.c` | `Ondrej Jirman` _power: supply: rk818-battery: Don't auto-poweroff the PMIC on low battery_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-charger-Add-support-for-POWER_SUPPLY_PROP_EN` | `(+10/-0)[1M]` | `rk818_charger.c` | `Ondrej Jirman` _power: supply: rk818-charger: Add support for POWER_SUPPLY_PROP_ENERGY_FULL_DESIGN_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-ip5xxx-Report-remaining-battery-capacity` | `(+43/-0)[1M]` | `ip5xxx_power.c` | `Ondrej Jirman` _power: supply: ip5xxx: Report remaining battery capacity_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-ip5xxx-Modify-initial-configuration` | `(+15/-7)[1M]` | `ip5xxx_power.c` | `Ondrej Jirman` _power: supply: ip5xxx: Modify initial configuration_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-ip5xxx-Add-boost-status-property` | `(+12/-1)[1M]` | `ip5xxx_power.c` | `Ondrej Jirman` _power: supply: ip5xxx: Add boost status property_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-ip5xxx-Add-ip5xxx-usb-supply` | `(+44/-0)[1M]` | `ip5xxx_power.c` | `Ondrej Jirman` _power: supply: ip5xxx: Add ip5xxx-usb supply_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-ip5xxx-Add-support-for-POWER_SUPPLY_PROP_CHARGE_BE` | `(+29/-0)[1M]` | `ip5xxx_power.c` | `Ondrej Jirman` _power: supply: ip5xxx: Add support for POWER_SUPPLY_PROP_CHARGE_BEHAVIOUR_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-ip5xxx-Add-support-for-POWER_SUPPLY_PROP_ENERGY_FU` | `(+10/-0)[1M]` | `ip5xxx_power.c` | `Ondrej Jirman` _power: supply: ip5xxx: Add support for POWER_SUPPLY_PROP_ENERGY_FULL_DESIGN_ |
|  📜  ✅  | `[patches.megous/]` `input-pinephone-keyboard-Allow-disabling-the-keyboard-input` | `(+7/-0)[1M]` | `pinephone-keyboard.c` | `Ondrej Jirman` _input: pinephone-keyboard: Allow disabling the keyboard input_ |
|  📜  ✅  | `[patches.megous/]` `input-pinephone-keyboard-Allow-to-disable-Fn-layer-processing` | `(+12/-0)[1M]` | `pinephone-keyboard.c` | `Ondrej Jirman` _input: pinephone-keyboard: Allow to disable Fn layer processing_ |
|  📜  ✅  | `[patches.megous/]` `input-pinephone-keyboard-Don-t-print-error-when-the-keyboard-is` | `(+5/-0)[1M]` | `pinephone-keyboard.c` | `Ondrej Jirman` _input: pinephone-keyboard: Don't print error when the keyboard is not connected_ |
|  📜  ✅  | `[patches.megous/]` `misc-ppkb-manager-Pinephone-Keyboard-power-manager` | `(+953/-0)[2M, 1A]` | `ppkb-manager.c`, `Kconfig`, `Makefile` | `Ondrej Jirman` _misc: ppkb-manager: Pinephone Keyboard power manager_ |
|  📜  ✅  | `[patches.megous/]` `input-pinephone-keyboard-Wait-a-bit-after-enabling-vbus` | `(+2/-0)[1M]` | `pinephone-keyboard.c` | `Ondrej Jirman` _input: pinephone-keyboard: Wait a bit after enabling vbus_ |
|  📜  ✅  | `[patches.megous/]` `misc-ppkb-manager-Remove-BLOCKED-flag` | `(+0/-8)[1M]` | `ppkb-manager.c` | `Ondrej Jirman` _misc: ppkb-manager: Remove BLOCKED flag_ |
|  📜  ✅  | `[patches.megous/]` `misc-ppkb-manager-Disable-ppkb-manager-by-default-can-be-enable` | `(+2/-1)[1M]` | `ppkb-manager.c` | `Ondrej Jirman` _misc: ppkb-manager: Disable ppkb-manager by default (can be enabled at runtime)_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-vendor-prefix-add-prefix-for-Voltafield` | `(+2/-0)[1M]` | `vendor-prefixes.yaml` | `Icenowy Zheng` _dt-bindings: vendor-prefix: add prefix for Voltafield_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-iio-magnetometer-add-DT-binding-for-Voltafield-AF81` | `(+59/-0)[1A]` | `voltafield,af8133j.yaml` | `Icenowy Zheng` _dt-bindings: iio: magnetometer: add DT binding for Voltafield AF8133J_ |
|  📜  ✅  | `[patches.megous/]` `MAINTAINERS-add-an-entry-for-AF8133J-driver` | `(+6/-0)[1M]` | `MAINTAINERS` | `Icenowy Zheng` _MAINTAINERS: add an entry for AF8133J driver_ |
|  📜  ✅  | `[patches.megous/]` `iio-magnetometer-add-a-driver-for-Voltafield-AF8133J-magnetomet` | `(+365/-0)[2M, 1A]` | `af8133j.c`, `Kconfig`, `Makefile` | `Icenowy Zheng` _iio: magnetometer: add a driver for Voltafield AF8133J magnetometer_ |
|  📜  ✅  | `[patches.megous/]` `iio-af8133j-Cleanup-probe-and-power-up-down` | `(+73/-92)[1M]` | `af8133j.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _iio: af8133j: Cleanup probe and power up/down_ |
|  📜  ✅  | `[patches.megous/]` `iio-af8133j-Add-runtime-power-management` | `(+81/-19)[1M]` | `af8133j.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _iio: af8133j: Add runtime power management_ |
|  📜  ✅  | `[patches.megous/]` `misc-ppkb-manager-Show-read-write-error-codes` | `(+3/-3)[1M]` | `ppkb-manager.c` | `Ondrej Jirman` _misc: ppkb-manager: Show read/write error codes_ |
|  📜  ✅  | `[patches.megous/]` `iio-af8133j-Add-support-for-buffer` | `(+37/-2)[1M]` | `af8133j.c` | `Ondrej Jirman` _iio: af8133j: Add support for buffer_ |
|  📜  ✅  | `[patches.megous/]` `misc-ppkb-manager-Disable-debug-mode` | `(+1/-1)[1M]` | `ppkb-manager.c` | `Ondrej Jirman` _misc: ppkb-manager: Disable debug mode_ |
|  📜  ✅  | `[patches.megous/]` `iio-af8133j-Avoid-compiler-warning` | `(+1/-1)[1M]` | `af8133j.c` | `Ondrej Jirman` _iio: af8133j: Avoid compiler warning_ |
|  📜  ✅  | `[patches.megous/]` `wifi-rtw89-parse-PHY-status-only-when-PPDU-is-to_self` | `(+3/-0)[1M]` | `core.c` | `Eric Huang` _wifi: rtw89: parse PHY status only when PPDU is to_self_ |
|  📜  ✅  | `[patches.megous/]` `power-supply-rk818-battery-Don-t-reset-dsoc-to-0-on-rk818_vb_lo` | `(+0/-1)[1M]` | `rk818_battery.c` | `Ondrej Jirman` _power: supply: rk818-battery: Don't reset dsoc to 0 on rk818_vb_low_irq_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Add-support-for-powerdown-gpio` | `(+12/-0)[1M]` | `imx258.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: i2c: imx258: Add support for powerdown gpio_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Don-t-be-too-strict-about-clock-rate` | `(+7/-2)[1M]` | `imx258.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: i2c: imx258: Don't be too strict about clock rate_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Add-support-for-reset-gpio` | `(+13/-1)[1M]` | `imx258.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: i2c: imx258: Add support for reset gpio_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Add-support-for-power-supplies` | `(+37/-2)[1M]` | `imx258.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _media: i2c: imx258: Add support for power supplies_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Powerdown-the-sensor-if-clock-enable-fails` | `(+1/-0)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Powerdown the sensor if clock enable fails_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Add-i2c-supply` | `(+1/-0)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Add i2c supply_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Set-xvclk-rate-before-each-power-on` | `(+18/-6)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Set xvclk rate before each power on_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Simplify-register-settings` | `(+477/-382)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Simplify register settings_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Don-t-flip-the-image-and-fix-the-mbus-format` | `(+9/-7)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Don't flip the image and fix the mbus format_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Fix-lower-modes-still-broken` | `(+47/-47)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Fix lower modes (still broken)_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Fix-smaller-formats-corruption-issues` | `(+60/-63)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Fix smaller formats corruption issues_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Add-debug-register-access` | `(+48/-0)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Add debug register access_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-imx258-Fix-4208x3120-mode` | `(+6/-6)[1M]` | `imx258.c` | `Ondrej Jirman` _media: i2c: imx258: Fix 4208x3120 mode_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-ov8858-Add-BSP-driver-for-OV8858-from-Rockchip-kernel` | `(+3178/-0)[2M, 2A]` | `ov8858.c`, `rk-camera-module.h`, `Kconfig`, `Makefile` | `Ondrej Jirman` _media: i2c: ov8858: Add BSP driver for OV8858 from Rockchip kernel tree_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-ov8858-Port-BSP-driver-to-5.18-and-improve-DT-binding` | `(+50/-82)[1M]` | `ov8858.c` | `Ondrej Jirman` _media: i2c: ov8858: Port BSP driver to 5.18 and improve DT bindings_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-ov8858-Increase-analog-gain-range` | `(+2/-2)[1M]` | `ov8858.c` | `Ondrej Jirman` _media: i2c: ov8858: Increase analog gain range_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-ov8858-Add-support-for-digital-gain-control` | `(+28/-0)[1M]` | `ov8858.c` | `Ondrej Jirman` _media: i2c: ov8858: Add support for digital gain control_ |
|  📜  ✅  | `[patches.megous/]` `media-i2c-ov8858-Use-default-subdev-name` | `(+0/-3)[1M]` | `ov8858.c` | `Ondrej Jirman` _media: i2c: ov8858: Use default subdev name_ |
|  📜  ✅  | `[patches.megous/]` `media-rkisp1-Allow-higher-input-resolution` | `(+2/-2)[1M]` | `rkisp1-common.h` | `Ondrej Jirman` _media: rkisp1: Allow higher input resolution_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-altmodes-displayport-Respect-DP_CAP_RECEPTACLE-bit` | `(+44/-4)[1M]` | `displayport.c` | `Ondrej Jirman` _usb: typec: altmodes: displayport: Respect DP_CAP_RECEPTACLE bit_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Slightly-increase-wait-time-for-BC1.2-result` | `(+2/-2)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Slightly increase wait time for BC1.2 result_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Set-the-current-before-enabling-pullups` | `(+8/-8)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Set the current before enabling pullups_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Extend-debugging-interface-with-driver-state-` | `(+78/-0)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Extend debugging interface with driver state dumps_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Retry-reading-of-CC-pins-status-if-activity-i` | `(+32/-2)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Retry reading of CC pins status if activity is detected_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-More-useful-of-logging-status-on-interrupt` | `(+104/-17)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: More useful of logging status on interrupt_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Update-VBUS-state-even-if-VBUS-interrupt-is-n` | `(+8/-6)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Update VBUS state even if VBUS interrupt is not triggered_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Make-tcpm-fusb302-logs-less-polluted-by-PD-co` | `(+27/-18)[2M]` | `tcpm.c`, `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Make tcpm/fusb302 logs less polluted by PD comm stuff_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Add-OF-extcon-support` | `(+10/-0)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Add OF extcon support_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Fix-register-definitions` | `(+7/-9)[1M]` | `fusb302_reg.h` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Fix register definitions_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-fusb302-Clear-interrupts-before-we-start-toggling` | `(+7/-0)[1M]` | `fusb302.c` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: fusb302: Clear interrupts before we start toggling_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-typec-extcon-Add-typec-extcon-bridge-driver` | `(+340/-0)[2M, 1A]` | `typec-extcon.c`, `Kconfig`, `Makefile` | `=?UTF-8?q?Ond=C5=99ej=20Jirman?=` _usb: typec: typec-extcon: Add typec -> extcon bridge driver_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-typec-extcon-Enable-debugging-for-now` | `(+1/-0)[1M]` | `typec-extcon.c` | `Ondrej Jirman` _usb: typec: typec-extcon: Enable debugging for now_ |
|  📜  ✅  | `[patches.megous/]` `usb-dwc3-Track-the-power-state-of-usb3_generic_phy` | `(+7/-1)[2M]` | `core.c`, `core.h` | `Ondrej Jirman` _usb: dwc3: Track the power state of usb3_generic_phy_ |
|  📜  ✅  | `[patches.megous/]` `usb-dwc3-Add-support-for-snps-usb3-phy-reset-quirk` | `(+73/-15)[3M]` | `core.c`, `drd.c`, `core.h` | `Ondrej Jirman` _usb: dwc3: Add support for snps,usb3-phy-reset-quirk_ |
|  📜  ✅  | `[patches.megous/]` `usb-typec-tcpm-Unregister-altmodes-before-registering-new-ones` | `(+3/-0)[1M]` | `tcpm.c` | `Ondrej Jirman` _usb: typec: tcpm: Unregister altmodes before registering new ones_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-rt5640-Allow-configuration-of-LOUT-to-mono-differential-mo` | `(+6/-0)[2M]` | `rt5640.c`, `rt5640.h` | `Ondrej Jirman` _ASoC: rt5640: Allow configuration of LOUT to mono differential mode_ |
|  📜  ✅  | `[patches.megous/]` `dt-bindings-sound-rt5640-Allow-to-describe-how-LOUT-is-wired` | `(+3/-0)[1M]` | `rt5640.txt` | `Ondrej Jirman` _dt-bindings: sound: rt5640: Allow to describe how LOUT is wired_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-codec-rt5640-Fix-output-mixer-input-channel-list` | `(+13/-17)[2M]` | `rt5640.h`, `rt5640.c` | `Ondrej Jirman` _ASoC: codec: rt5640: Fix output mixer input channel list_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-codec-rt5640-Fix-hpout-restore-when-lout-is-enabled` | `(+2/-1)[1M]` | `rt5640.c` | `Ondrej Jirman` _ASoC: codec: rt5640: Fix hpout restore when lout is enabled_ |
|  📜  ✅  | `[patches.megous/]` `ASoC-codec-rt5640-Resolve-failure-to-set-DMIC-clock-after-playb` | `(+3/-0)[1M]` | `rt5640.c` | `Ondrej Jirman` _ASoC: codec: rt5640: Resolve failure to set DMIC clock after playback_ |
|  📜  ✅  | `[patches.megous/]` `media-ov5640-Fix-sensor-probe-with-the-anti-click-patch` | `(+1/-10)[1M]` | `ov5640.c` | `Ondrej Jirman` _media: ov5640: Fix sensor probe with the "anti-click" patch_ |
|  📜  ✅  | `[patches.megous/]` `ARM-dts-sun8i-a83t-Add-missing-GPU-trip-point` | `(+9/-0)[1M]` | `sun8i-a83t.dtsi` | `Ondrej Jirman` _ARM: dts: sun8i-a83t: Add missing GPU trip point_ |
|  📜  ✅  | `[patches.fixes/]` `Fix-ISO-C90-forbids-mixed-declarations` | `(+13/-9)[1M]` | `fusb302.c` | `The-going` _Fix: ISO C90 forbids mixed declarations_ |
|  📜  ✅  | `[patches.fixes/]` `Fix-warning-multi-line-comment` | `(+1/-1)[1M]` | `af8133j.c` | `The-going` _Fix: warning: multi-line comment_ |
|  📜  ✅  | `[patches.fixes/]` `Fix-warning-unused-variable-delay_us` | `(+1/-1)[1M]` | `ov8858.c` | `The-going` _=?UTF-8?q?Fix:=20warning:=20unused=20variable=20?= =?UTF-8?q?=E2=80=98delay=5Fus=E2=80=99?=_ |
|  📜  ✅  | `[patches.fixes/]` `Fix-depends-only-ARM-eInk-display-FB` | `(+1/-1)[1M]` | `Kconfig` | `The-going` _Fix: depends only ARM: eInk display FB_ |
|  📜  ✅  | `[patches.fixes/]` `Fix-duplicate-nodes-for-sun50i-h5-orangepi-pc2` | `(+0/-20)[1M]` | `sun50i-h5-orangepi-pc2.dts` | `The-going` _Fix duplicate nodes for sun50i-h5-orangepi-pc2_ |
|  📜  ✅  | `[patches.armbian/]` `Doc-dt-bindings-usb-add-binding-for-DWC3-controller-on-Allwinne` | `(+39/-0)[1A]` | `allwinner,dwc3.txt` | `Icenowy Zheng` _Doc:dt-bindings:usb: add binding for DWC3 controller on Allwinner SoC_ |
|  📜  ✅  | `[patches.armbian/]` `drv-pinctrl-pinctrl-sun50i-a64-disable_strict_mode` | `(+1/-0)[1M]` | `pinctrl-sun50i-a64.c` | `WaterByWind` _drv:pinctrl: pinctrl-sun50i-a64 disable_strict_mode_ |
|  📜  ✅  | `[patches.armbian/]` `drv-rtc-sun6i-support-RTCs-without-external-LOSCs` | `(+11/-5)[1M]` | `rtc-sun6i.c` | `Andre Przywara` _drv:rtc:sun6i: support RTCs without external LOSCs_ |
|  📜  ✅  | `[patches.armbian/]` `drv-gpu-drm-gem-dma-Export-with-handle-allocator` | `(+6/-1)[2M]` | `drm_gem_dma_helper.h`, `drm_gem_dma_helper.c` | `Maxime Ripard` _drv:gpu:drm: gem: dma: Export with handle allocator_ |
|  📜  ✅  | `[patches.armbian/]` `drv-gpu-drm-sun4i-Add-GEM-allocator` | `(+56/-0)[1M, 1A]` | `sun4i_drm.h`, `sun4i_drv.c` | `Maxime Ripard` _drv:gpu:drm:sun4i: Add GEM allocator_ |
|  📜  ✅  | `[patches.armbian/]` `drv-gpu-drm-sun4i-Add-HDMI-audio-sun4i-hdmi-encoder` | `(+516/-0)[4M, 1A]` | `sun4i_hdmi_audio.c`, `sun4i_hdmi.h`, `sun4i_hdmi_enc.c`, `Kconfig`, `Makefile` | `The-going` _drv:gpu:drm:sun4i: Add HDMI audio sun4i-hdmi encoder_ |
|  📜  ✅  | `[patches.armbian/]` `drv-net-stmmac-dwmac-sun8i-second-EMAC-clock-register` | `(+10/-2)[1M]` | `dwmac-sun8i.c` | `Andre Przywara` _drv:net:stmmac:dwmac-sun8i: second EMAC clock register_ |
|  📜  ✅  | `[patches.armbian/]` `drv-phy-sun4i-usb-Allow-reset-line-to-be-shared` | `(+1/-1)[1M]` | `phy-sun4i-usb.c` | `Andre Przywara` _drv:phy: sun4i-usb: Allow reset line to be shared_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-rename-A33-specified-registers-to-c` | `(+4/-4)[2M]` | `sun4i-gpadc.h`, `sun4i-gpadc-iio.c` | `Icenowy Zheng` _drv:iio:adc: sun4i-gpadc-iio: rename A33-specified registers to contain A33_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-sampling-start-end-code-readout-reg` | `(+94/-12)[2M]` | `sun4i-gpadc-iio.c`, `sun4i-gpadc.h` | `Philipp Rossak` _drv:iio:adc: sun4i-gpadc-iio: sampling start/end code readout reg rework_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-support-clocks-and-reset` | `(+80/-0)[1M]` | `sun4i-gpadc-iio.c` | `Philipp Rossak` _drv:iio:adc: sun4i-gpadc-iio: support clocks and reset_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-multible-sensors-support` | `(+29/-10)[2M]` | `sun4i-gpadc-iio.c`, `sun4i-gpadc.h` | `Philipp Rossak` _drv:iio:adc:sun4i-gpadc-iio: multible sensors support_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-support-nvmem-calibration-data` | `(+54/-0)[2M]` | `sun4i-gpadc-iio.c`, `sun4i-gpadc.h` | `Philipp Rossak` _drv:iio:adc:sun4i-gpadc-iio: support nvmem calibration data_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-add-interrupt-support` | `(+95/-6)[2M]` | `sun4i-gpadc-iio.c`, `sun4i-gpadc.h` | `Philipp Rossak` _drv:iio:adc:sun4i-gpadc-iio: add interrupt support_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-add-H3-thermal-sensor` | `(+29/-0)[1M]` | `sun4i-gpadc-iio.c` | `Philipp Rossak` _drv:iio:adc: sun4i-gpadc-iio: add H3 thermal sensor_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-add-A83T-thermal-sensor` | `(+38/-0)[1M]` | `sun4i-gpadc-iio.c` | `Philipp Rossak` _drv:iio:adc:sun4i-gpadc-iio: add A83T thermal sensor_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-Kconfig-enable-A80-A64-H5-for-THS` | `(+1/-1)[1M]` | `Kconfig` | `Philipp Rossak` _drv:iio:adc: Kconfig: enable A80,A64,H5 for THS_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-add-A80-thermal-sensor` | `(+46/-0)[1M]` | `sun4i-gpadc-iio.c` | `Philipp Rossak` _drv:iio:adc:sun4i-gpadc-iio: add A80 thermal sensor_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-sun4i-gpadc-iio-add-A64-thermal-sensor` | `(+50/-0)[1M]` | `sun4i-gpadc-iio.c` | `Philipp Rossak` _drv:iio: adc: sun4i-gpadc-iio: add A64 thermal sensor_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-sun4i-gpadc-iio-don-t-force-poweroff` | `(+6/-0)[1M]` | `sun4i-gpadc-iio.c` | `Vasily Khoruzhick` _drv:iio:sun4i-gpadc-iio: don`t force poweroff_ |
|  📜  ✅  | `[patches.armbian/]` `drv-staging-media-sunxi-cedrus-add-H616-variant` | `(+13/-0)[1M]` | `cedrus.c` | `Jernej Skrabec` _drv:staging:media:sunxi:cedrus: add H616 variant_ |
|  📜  ✅  | `[patches.armbian/]` `drv-soc-sunxi-sram-Add-SRAM-C1-H616-handling` | `(+10/-0)[1M]` | `sunxi_sram.c` | `Jernej Skrabec` _drv:soc: sunxi: sram: Add SRAM C1 H616 handling_ |
|  📜  ✅  | `[patches.armbian/]` `drv-media-dvb-frontends-si2168-fix-cmd-timeout` | `(+1/-1)[1M]` | `si2168.c` | `Koumes` _drv:media:dvb-frontends:si2168: fix cmd timeout_ |
|  📜  ✅  | `[patches.armbian/]` `include-uapi-drm_fourcc-add-ARM-tiled-format-modifier` | `(+9/-0)[1M]` | `drm_fourcc.h` | `Qiang Yu` _include:uapi:drm_fourcc: add ARM tiled format modifier_ |
|  📜  ✅  | `[patches.armbian/]` `drv-clk-sunxi-ng-ccu-add-min-max-rate-sun50i-a64` | `(+10/-0)[3M]` | `ccu_nkm.c`, `ccu_nkm.h`, `ccu-sun50i-a64.c` | `Vasily Khoruzhick` _drv:clk:sunxi-ng: ccu: add min/max rate sun50i-a64_ |
|  📜  ✅  | `[patches.armbian/]` `drv-clk-sunxi-ng-ccu-sun50i-a64-revert-ccu-Pinebook-A64` | `(+9/-9)[1M]` | `ccu-sun50i-a64.c` | `The-going` _drv:clk:sunxi-ng:ccu-sun50i-a64: revert ccu Pinebook-A64_ |
|  📜  ✅  | `[patches.armbian/]` `drv-clocksource-arm_arch_timer-fix-a64-timejump` | `(+14/-11)[1M]` | `arm_arch_timer.c` | `The-going` _drv:clocksource:arm_arch_timer fix a64 timejump_ |
|  📜  ✅  | `[patches.armbian/]` `sound-soc-sunxi-sun4i-spdif-add-mclk_multiplier` | `(+7/-0)[1M]` | `sun4i-spdif.c` | `The-going` _sound:soc:sunxi:sun4i-spdif add mclk_multiplier_ |
|  📜  ✅  | `[patches.armbian/]` `sound-soc-sunxi-sun8i-codec-analog-enable-sound` | `(+6/-2)[1M]` | `sun8i-codec-analog.c` | `The-going` _sound:soc:sunxi:sun8i-codec-analog enable sound_ |
|  📜  ✅  | `[patches.armbian/]` `sound-soc-sunxi-Provoke-the-early-load-of-sun8i-codec-analog` | `(+1/-1)[1M]` | `Makefile` | `wuweidong` _sound:soc:sunxi: Provoke the early load of sun8i-codec-analog_ |
|  📜  ✅  | `[patches.armbian/]` `sound-soc-sunxi-sun4i-codec-adcis-select-capture-source` | `(+47/-4)[1M]` | `sun4i-codec.c` | `The-going` _sound:soc:sunxi:sun4i-codec adcis select capture source_ |
|  📜  ✅  | `[patches.armbian/]` `drv-mmc-host-sunxi-mmc-add-h5-emmc-compatible` | `(+8/-0)[1M]` | `sunxi-mmc.c` | `The-going` _drv:mmc:host:sunxi-mmc: add h5 emmc compatible_ |
|  📜  ✅  | `[patches.armbian/]` `drv-pinctrl-sunxi-pinctrl-sun50i-h6.c-GPIO-disable_strict_mode` | `(+1/-0)[1M]` | `pinctrl-sun50i-h6.c` | `The-going` _drv:pinctrl:sunxi:pinctrl-sun50i-h6.c GPIO disable_strict_mode_ |
|  📜  ✅  | `[patches.armbian/]` `drv-gpu-drm-sun4i-sun8i_mixer.c-add-h3-mixer1` | `(+12/-0)[1M]` | `sun8i_mixer.c` | `The-going` _drv:gpu:drm:sun4i:sun8i_mixer.c add h3 mixer1_ |
|  📜  ✅  | `[patches.armbian/]` `drv-mtd-nand-raw-nand_ids.c-add-H27UBG8T2BTR-BC-nand` | `(+4/-0)[1M]` | `nand_ids.c` | `The-going` _drv:mtd:nand:raw:nand_ids.c add H27UBG8T2BTR-BC nand_ |
|  📜  ✅  | `[patches.armbian/]` `drv-mfd-axp20x-add-sysfs-interface` | `(+614/-0)[1M]` | `axp20x.c` | `The-going` _drv:mfd:axp20x add sysfs interface_ |
|  📜  ✅  | `[patches.armbian/]` `drv-spi-spidev-Add-armbian-spi-dev-compatible` | `(+3/-0)[1M]` | `spidev.c` | `The-going` _drv:spi:spidev Add armbian spi-dev compatible_ |
|  📜  ✅  | `[patches.armbian/]` `drv-spi-spi-sun4i.c-spi-bug-low-on-sck` | `(+3/-1)[1M]` | `spi-sun4i.c` | `The-going` _drv:spi:spi-sun4i.c spi bug low on sck_ |
|  📜  ✅  | `[patches.armbian/]` `drv-nvmem-sunxi_sid-Support-SID-on-H616` | `(+7/-0)[1M]` | `sunxi_sid.c` | `Kali Prasad` _drv:nvmem:sunxi_sid: Support SID on H616_ |
|  📜  ✅  | `[patches.armbian/]` `drv-thermal-sun8i_thermal-Add-for-H616` | `(+102/-0)[1M]` | `sun8i_thermal.c` | `Kali Prasad` _drv:thermal:sun8i_thermal Add for H616_ |
|  📜  ✅  | `[patches.armbian/]` `drv-iio-adc-axp20x_adc-arm64-dts-axp803-hwmon-enable-thermal` | `(+89/-0)[2M]` | `axp20x_adc.c`, `axp803.dtsi` | `Mitko Gamishev` _drv:iio:adc:axp20x_adc arm64:dts:axp803 hwmon enable thermal_ |
|  📜  ✅  | `[patches.armbian/]` `drv-gpu-drm-panel-simple-Add-compability-olinuxino-lcd` | `(+122/-4)[1M]` | `panel-simple.c` | `The-going` _drv:gpu:drm: panel-simple Add compability olinuxino lcd_ |
|  📜  ✅  | `[patches.armbian/]` `drv-input-touchscreen-sun4i-ts-Enable-parsing` | `(+15/-4)[1M]` | `sun4i-ts.c` | `Mitko Gamishev` _drv:input:touchscreen:sun4i-ts Enable parsing_ |
|  📜  ✅  | `[patches.armbian/]` `drv-mmc-host-sunxi-mmc-Disable-DDR52-mode-on-all-A20-based-boar` | `(+3/-1)[1M]` | `sunxi-mmc.c` | `Mitko Gamishev` _drv:mmc:host:sunxi-mmc Disable DDR52 mode on all A20 based boards_ |
|  📜  ✅  | `[patches.armbian/]` `drv-usb-gadget-composite-rename-gadget-serial-console-manufactu` | `(+1/-1)[1M]` | `composite.c` | `The-going` _drv:usb:gadget:composite rename gadget serial console manufacturer_ |
|  📜  ✅  | `[patches.armbian/]` `arm-arm64-dts-Add-leds-axp20x-charger` | `(+20/-0)[4M]` | `axp209.dtsi`, `axp22x.dtsi`, `axp81x.dtsi`, `axp803.dtsi` | `The-going` _arm:arm64:dts: Add leds axp20x charger_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun9i-a80-add-thermal-sensor` | `(+11/-0)[1M]` | `sun9i-a80.dtsi` | `Philipp Rossak` _arm:dts: sun9i-a80 add thermal sensor_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun9i-a80-add-thermal-zone` | `(+26/-0)[1M]` | `sun9i-a80.dtsi` | `Philipp Rossak` _arm:dts: sun9i-a80 add thermal zone_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-Disable-OOB-IRQ-for-brcm-wifi-on-Cubietruck-a` | `(+26/-6)[2M]` | `sun7i-a20-bananapro.dts`, `sun7i-a20-cubietruck.dts` | `The-going` _arm:dts:sun7i-a20 Disable OOB IRQ for brcm-wifi on Cubietruck and Banana-Pro_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-a20-orangepi-and-mini-fix-phy-mode-hdmi` | `(+31/-2)[2M]` | `sun7i-a20-orangepi.dts`, `sun7i-a20-orangepi-mini.dts` | `The-going` _arm:dts: a20-orangepi and mini fix phy-mode, hdmi_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-nanopi-add-leds-pio-pins` | `(+23/-0)[1M]` | `sun8i-h3-nanopi.dtsi` | `The-going` _arm:dts: sun8i-h3-nanopi add leds pio pins_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-a10-cubiebord-a20-cubietruck-green-LED-mmc0-default-tri` | `(+2/-1)[2M]` | `sun4i-a10-cubieboard.dts`, `sun7i-a20-cubietruck.dts` | `The-going` _arm:dts: a10-cubiebord a20-cubietruck green LED mmc0 default-trigger_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-Add-sun8i-h2-plus-nanopi-duo-device` | `(+165/-0)[1M, 1A]` | `sun8i-h2-plus-nanopi-duo.dts`, `Makefile` | `The-going` _arm:dts: Add sun8i-h2-plus-nanopi-duo device_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-Add-sun8i-h2-plus-sunvell-r69-device` | `(+226/-0)[1M, 1A]` | `sun8i-h2-plus-sunvell-r69.dts`, `Makefile` | `The-going` _arm:dts: Add sun8i-h2-plus-sunvell-r69 device_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-h3-nanopi-neo-Add-regulator-leds-mmc2` | `(+57/-0)[1M]` | `sun8i-h3-nanopi-neo.dts` | `The-going` _arm:dts: h3-nanopi-neo Add regulator, leds, mmc2_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-h3-nanopi-neo-air-Add-regulator-camera-wifi-bluetooth-o` | `(+153/-0)[1M]` | `sun8i-h3-nanopi-neo-air.dts` | `The-going` _arm:dts: h3-nanopi-neo-air Add regulator camera wifi bluetooth otg_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-h3-orangepi-2-Add-regulator-vdd-cpu` | `(+29/-0)[1M]` | `sun8i-h3-orangepi-2.dts` | `The-going` _arm:dts: h3-orangepi-2 Add regulator vdd cpu_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-r40-bananapi-m2-ultra-add-codec-analog` | `(+28/-0)[2M]` | `sun8i-r40.dtsi`, `sun8i-r40-bananapi-m2-ultra.dts` | `The-going` _arm:dts: sun8i-r40 bananapi-m2-ultra add codec analog_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-cubietruck-add-alias-uart2` | `(+1/-0)[1M]` | `sun7i-a20-cubietruck.dts` | `The-going` _arm:dts: sun7i-a20-cubietruck add alias uart2_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-v3s-s3-pinecube-enable-sound-codec` | `(+28/-0)[2M]` | `sun8i-s3-pinecube.dts`, `sun8i-v3s.dtsi` | `The-going` _arm:dts: sun8i-v3s/s3-pinecube enable sound codec_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-r40-add-clk_out_a-fix-bananam2ultra` | `(+17/-0)[1M]` | `sun8i-r40.dtsi` | `The-going` _arm:dts: sun8i-r40 add clk_out_a fix bananam2ultra_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-bananapi-m2-plus-add-wifi_pwrseq` | `(+5/-0)[1M]` | `sun8i-h3-bananapi-m2-plus.dts` | `The-going` _arm:dts:sun8i-h3-bananapi-m2-plus add wifi_pwrseq_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-bananapro-add-hdmi-connector-de` | `(+30/-0)[1M]` | `sun7i-a20-bananapro.dts` | `The-going` _arm:dts: sun7i-a20-bananapro add hdmi-connector, de_ |
|  📜  ✅  | `[patches.armbian/]` `Bananapro-add-AXP209-regulators` | `(+50/-0)[1M]` | `sun7i-a20-bananapro.dts` | `The-going` _Bananapro add AXP209 regulators_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sunxi-h3-h5.dtsi-force-mmc0-bus-width` | `(+1/-0)[1M]` | `sunxi-h3-h5.dtsi` | `The-going` _arm:dts: sunxi-h3-h5.dtsi force mmc0 bus-width_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-pine64-enable-wifi-mmc1` | `(+16/-0)[1M]` | `sun50i-a64-pine64.dts` | `Icenowy Zheng` _arm64:dts: sun50i-a64-pine64 enable wifi mmc1_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-sopine-baseboard-Add-i2s2-mmc1` | `(+14/-0)[1M]` | `sun50i-a64-sopine-baseboard.dts` | `Vasily Khoruzhick` _arm64:dts: sun50i-a64-sopine-baseboard Add i2s2 mmc1_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-Add-r_uart-uart2-3-pins` | `(+50/-10)[1M]` | `sun50i-h6.dtsi` | `The-going` _arm64:dts: sun50i-h6 Add r_uart uart2-3 pins_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwiner-sun50i-h616.dtsi-add-usb-ehci-ohci` | `(+181/-2)[1M]` | `sun50i-h616.dtsi` | `The-going` _arm64: dts: allwiner: sun50i-h616.dtsi: add usb,ehci,ohci_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-orangepi-zero2-Add-reg_usb1_vbus-usbotg-u` | `(+32/-0)[1M]` | `sun50i-h616-orangepi-zero2.dts` | `The-going` _arm64: dts: sun50i-h616-orangepi-zero2: Add reg_usb1_vbus, usbotg, usbphy_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-orangepi-zero2-Enable-ehci1-ohci1` | `(+8/-0)[1M]` | `sun50i-h616-orangepi-zero2.dts` | `The-going` _arm64:dts: sun50i-h616-orangepi-zero2 Enable ehci1, ohci1_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-x96-mate-ehci-ohci-usbotg-usbphy-enable` | `(+25/-0)[1M]` | `sun50i-h616-x96-mate.dts` | `The-going` _arm64:dts: sun50i-h616-x96-mate ehci ohci usbotg usbphy enable_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-sun50i-h616-Add-GPU-node` | `(+14/-0)[1M]` | `sun50i-h616.dtsi` | `Jernej Skrabec` _arm64:dts: allwinner: sun50i-h616 Add GPU node_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-orangepi-zero2-Enable-GPU-mali` | `(+5/-0)[1M]` | `sun50i-h616-orangepi-zero2.dts` | `Jernej Skrabec` _arm64:dts: sun50i-h616-orangepi-zero2 Enable GPU mali_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-sun50i-h616-Add-VPU-node` | `(+24/-0)[1M]` | `sun50i-h616.dtsi` | `Jernej Skrabec` _arm64:dts:allwinner: sun50i-h616 Add VPU node_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-x96-mate-T95-eth-sd-card-hack` | `(+46/-1)[2M]` | `sun50i-h616.dtsi`, `sun50i-h616-x96-mate.dts` | `Jernej Skrabec` _arm64:dts: sun50i-h616-x96-mate T95 eth & sd card hack_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-x96-mate-add-hdmi` | `(+26/-0)[1M]` | `sun50i-h616-x96-mate.dts` | `Jernej Skrabec` _arm64:dts: sun50i-h616-x96-mate add hdmi_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h616-Add-device-node-for-SID` | `(+15/-0)[1M]` | `sun50i-h616.dtsi` | `Kali Prasad` _arm64: dts: allwinner: h616: Add device node for SID_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h616-Add-efuse_xlate-cpu-frequency-scaling-v1_6_1` | `(+149/-24)[3M, 1A]` | `sun50i-cpufreq-nvmem.c`, `sun50i-h616-cpu-opp.dtsi`, `sun50i-h616-orangepi-zero2.dts`, `cpufreq-dt-platdev.c` | `AGM1968` _arm64-dts-allwinner-h616-Add-efuse_xlate-cpu-frequency-scaling-v1_6_2 arch/arm64/boot/dts/allwinner/sun50i-h616-cpu-opp.dtsi arch/arm64/boot/dts/allwinner/sun50i-h616-orangepi-zero2.dts drivers/cpufreq/cpufreq-dt-platdev.c drivers/cpufreq/sun50i-cpufreq-nvmem.c_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h616-Add-thermal-sensor-and-thermal-zones` | `(+75/-0)[1M]` | `sun50i-h616.dtsi` | `Kali Prasad` _arm64: dts: allwinner: h616: Add thermal sensor and thermal zones_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h616-Fix-thermal-zones-missing-trips` | `(+29/-0)[1M]` | `sun50i-h616.dtsi` | `=?UTF-8?q?Micha=C5=82=20Dzieko=C5=84ski?=` _arm64: dts: allwinner: h616: Fix thermal zones (add missing trips)_ |
|  📜  ✅  | `[patches.armbian/]` `drv-pmic-add-axp313a` | `(+156/-0)[5M]` | `axp20x.c`, `axp20x-regulator.c`, `axp20x.h`, `axp20x-i2c.c`, `x-powers,axp152.yaml` | `Martin Botka` _axp20x: Add support for AXP313a PMIC_ |
|  📜  ✅  | `[patches.armbian/]` `drv-staging-fbtft-add-st7796s` | `(+111/-0)[2M, 1A]` | `fb_st7796s.c`, `Kconfig`, `Makefile` | `Alan` _Add: FB_TFT ST7796S driver_ |
|  📜  ✅  | `[patches.armbian/]` `drv-touchscreen-tsc2007-polling` | `(+108/-8)[2M]` | `tsc2007_core.c`, `tsc2007.h` | `Alan` _Optimize: TSC2007 touchscreen add polling method_ |
|  📜  ✅  | `[patches.armbian/]` `drv-rgb-add-ws2812` | `(+238/-0)[2M, 1A]` | `leds-ws2812.c`, `Kconfig`, `Makefile` | `Alan` _Add: ws2812 RGB driver for allwinner H616_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h616-LED-green_power_on-red_status_heartbeat` | `(+4/-3)[1M]` | `sun50i-h616-orangepi-zero2.dts` | `AGM1968` _LED-green_power_on-red_status_heartbeat arch/arm64/boot/dts/allwinner/sun50i-h616-orangepi-zero2.dts_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h616-orangepi-zero2-Enable-expansion-board-USB-ports` | `(+9/-0)[1M]` | `sun50i-h616-orangepi-zero2.dts` | `=?UTF-8?q?Micha=C5=82=20Dzieko=C5=84ski?=` _arm64: dts: allwinner: h616 orangepi zero2: Enable expansion board USB ports_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-pinebook-enable-Bluetooth` | `(+14/-0)[1M]` | `sun50i-a64-pinebook.dts` | `Vasily Khoruzhick` _arm64:dts: sun50i-a64-pinebook enable Bluetooth_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-pine64-enable-Bluetooth` | `(+9/-1)[1M]` | `sun50i-a64-pine64.dts` | `Vasily Khoruzhick` _arm64:dts: sun50i-a64-pine64 enable Bluetooth_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-sopine-baseboard-enable-Bluetooth` | `(+14/-0)[1M]` | `sun50i-a64-sopine-baseboard.dts` | `Vasily Khoruzhick` _arm64:dts: sun50i-a64-sopine-baseboard enable Bluetooth_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-nanopi-a64-set-right-phy-mode-to-rgmii-id` | `(+1/-1)[1M]` | `sun50i-a64-nanopi-a64.dts` | `root` _arm64:dts: nanopi-a64 set right phy-mode to rgmii-id_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-FIXME-a64-olinuxino-add-regulator-audio-mmc` | `(+46/-0)[1M]` | `sun50i-a64-olinuxino.dts` | `The-going` _arm64:dts: FIXME: a64-olinuxino add regulator audio mmc_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-Add-sun50i-h5-nanopi-k1-plus-device` | `(+397/-0)[1M, 1A]` | `sun50i-h5-nanopi-k1-plus.dts`, `Makefile` | `wuweidong` _arm64:dts: Add sun50i-h5-nanopi-k1-plus device_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-Add-sun50i-h5-nanopi-neo-core2-device` | `(+211/-0)[1M, 1A]` | `sun50i-h5-nanopi-neo-core2.dts`, `Makefile` | `The-going` _arm64:dts: Add sun50i-h5-nanopi-neo-core2 device_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-Add-sun50i-h5-nanopi-neo2-v1.1-device` | `(+181/-0)[1M, 1A]` | `sun50i-h5-nanopi-neo2-v1.1.dts`, `Makefile` | `The-going` _arm64:dts: Add sun50i-h5-nanopi-neo2-v1.1 device_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-Add-sun50i-h5-nanopi-m1-plus2-device` | `(+241/-0)[1M, 1A]` | `sun50i-h5-nanopi-m1-plus2.dts`, `Makefile` | `The-going` _arm64:dts: Add sun50i-h5-nanopi-m1-plus2 device_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-nanopi-neo2-add-regulator-led-triger` | `(+22/-1)[1M]` | `sun50i-h5-nanopi-neo2.dts` | `The-going` _arm64:dts: sun50i-h5-nanopi-neo2 add regulator, led triger_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-orangepi-pc2-add-spi-flash` | `(+19/-6)[1M]` | `sun50i-h5-orangepi-pc2.dts` | `The-going` _arm64:dts: sun50i-h5-orangepi-pc2 add spi flash_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-orangepi-prime-add-regulator` | `(+36/-7)[1M]` | `sun50i-h5-orangepi-prime.dts` | `The-going` _arm64:dts: sun50i-h5-orangepi-prime add regulator_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-orangepi-zero-plus-add-regulator` | `(+24/-1)[1M]` | `sun50i-h5-orangepi-zero-plus.dts` | `The-going` _arm64:dts: sun50i-h5-orangepi-zero-plus add regulator_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-orangepi-zero-plus2-regulator-gpio-fix` | `(+45/-13)[1M]` | `sun50i-h5-orangepi-zero-plus2.dts` | `The-going` _arm64:dts: sun50i-h5-orangepi-zero-plus2 regulator-gpio fix_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6.dtsi-improve-thermals` | `(+55/-13)[1M]` | `sun50i-h6.dtsi` | `The-going` _arm64:dts: sun50i-h6.dtsi improve thermals_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-orangepi-3-delete-node-spi0` | `(+2/-0)[1M]` | `sun50i-h6-orangepi-3.dts` | `The-going` _arm64:dts: sun50i-h6-orangepi-3 delete-node &spi0_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-orangepi-lite2-spi0-usb3phy-dwc3-enable` | `(+26/-0)[1M]` | `sun50i-h6-orangepi-lite2.dts` | `Igor Pecovnik` _arm64:dts: sun50i-h6-orangepi-lite2 spi0, usb3phy, dwc3 enable_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-pine-h64-add-wifi-rtl8723cs` | `(+38/-0)[1M]` | `sun50i-h6-pine-h64.dts` | `The-going` _arm64:dts: sun50i-h6-pine-h64 add wifi rtl8723cs_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-pine-h64-add-dwc3-usb3phy` | `(+9/-0)[1M]` | `sun50i-h6-pine-h64.dts` | `The-going` _arm64:dts: sun50i-h6-pine-h64 add dwc3 usb3phy_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-pine64-add-spi0` | `(+29/-0)[1M]` | `sun50i-a64-pine64.dts` | `The-going` _arm64:dts: sun50i-a64-pine64 add spi0_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6.dtsi-add-pinctrl-pins-for-spi` | `(+4/-0)[1M]` | `sun50i-h6.dtsi` | `The-going` _arm64:dts: sun50i-h6.dtsi add pinctrl pins for spi_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-orangepi-win-add-aliase-ethernet1` | `(+1/-0)[1M]` | `sun50i-a64-orangepi-win.dts` | `The-going` _arm64:dts: sun50i-a64-orangepi-win add aliase ethernet1_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-force-mmc0-bus-width` | `(+1/-0)[1M]` | `sun50i-a64.dtsi` | `The-going` _arm64:dts: sun50i-a64 force mmc0 bus-width_ |
|  📜  ✅  | `[patches.armbian/]` `drv-of-Device-Tree-Overlay-ConfigFS-interface` | `(+286/-1)[3M, 1A]` | `configfs.c`, `Kconfig`, `fdt_address.c`, `Makefile` | `The-going` _drv:of: Device Tree Overlay ConfigFS interface_ |
|  📜  ✅  | `[patches.armbian/]` `scripts-add-overlay-compilation-support` | `(+47/-15)[3M]` | `Makefile.dtbinst`, `Makefile.lib`, `.gitignore` | `The-going` _scripts: add overlay compilation support_ |
|  📜  ✅  | `[patches.armbian/]` `scripts-enable-kernel-dtbs-symbol-generation` | `(+2/-1)[1M]` | `Makefile.lib` | `The-going` _scripts: enable kernel dtbs symbol generation_ |
|  📜  ✅  | `[patches.armbian/]` `Makefile-CONFIG_SHELL-fix-for-builddeb-packaging` | `(+3/-1)[1M]` | `Makefile` | `The-going` _Makefile: CONFIG_SHELL fix for builddeb packaging_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-overlay-Add-Overlays-for-sunxi` | `(+4176/-0)[1M, 96A]` | `README.sun7i-a20-overlays`, `README.sun4i-a10-overlays`, `README.sun8i-h3-overlays`, `README.sun5i-a13-overlays`, `sun7i-a20-fixup.scr-cmd`, `sun4i-a10-fixup.scr-cmd`, `sun8i-h3-fixup.scr-cmd`, `sun4i-a10-nand.dts`, `sun7i-a20-nand.dts`, `Makefile`, `sun5i-a13-nand.dts`, `sun4i-a10-spi-jedec-nor.dts`, `sun4i-a10-spi-spidev.dts`, `sun5i-a13-spi-jedec-nor.dts`, `sun5i-a13-spi-spidev.dts`, _and 81 more_ | `The-going` _arm:dts:overlay Add Overlays for sunxi_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-overlay-Add-Overlays-for-sunxi64` | `(+2067/-0)[1M, 48A]` | `README.sun50i-h5-overlays`, `README.sun50i-a64-overlays`, `sun50i-h5-fixup.scr-cmd`, `sun50i-h6-fixup.scr-cmd`, `sun50i-a64-fixup.scr-cmd`, `Makefile`, `sun50i-a64-spi-spidev.dts`, `sun50i-h5-spi-jedec-nor.dts`, `sun50i-h5-spi-spidev.dts`, `sun50i-h6-spi-jedec-nor.dts`, `sun50i-h6-spi-spidev.dts`, `sun50i-a64-spi-add-cs1.dts`, `sun50i-h5-spi-add-cs1.dts`, `sun50i-h6-spi-add-cs1.dts`, `sun50i-h5-pwm.dts`, _and 33 more_ | `The-going` _arm64:dts:allwinner:overlay: Add Overlays for sunxi64_ |
|  📜  ✅  | `[patches.armbian/]` `scripts-Makefile.lib-Add-Overlays-for-sunxi-sunxi64` | `(+3/-0)[1M]` | `Makefile.lib` | `The-going` _scripts:Makefile.lib Add Overlays for sunxi sunxi64_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-overlay-sun8i-h3-cpu-clock-add-overclock` | `(+162/-0)[1M, 3A]` | `sun8i-h3-cpu-clock-1.368GHz-1.3v.dts`, `sun8i-h3-cpu-clock-1.3GHz-1.3v.dts`, `sun8i-h3-cpu-clock-1.2GHz-1.3v.dts`, `Makefile` | `The-going` _arm:dts:overlay: sun8i-h3-cpu-clock add overclock_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-overlay-sun50i-a64-pine64-7inch-lcd` | `(+93/-0)[2M, 1A]` | `sun50i-a64-pine64-7inch-lcd.dts`, `README.sun50i-a64-overlays`, `Makefile` | `The-going` _arm64:dts:overlay: sun50i-a64-pine64-7inch-lcd_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-overlay-sun50i-h5-add-gpio-regulator-overclock` | `(+165/-0)[1M, 4A]` | `sun50i-h5-cpu-clock-1.3GHz-1.3v.dts`, `sun50i-h5-gpio-regulator-1.3v.dts`, `sun50i-h5-cpu-clock-1.0GHz-1.1v.dts`, `sun50i-h5-cpu-clock-1.2GHz-1.3v.dts`, `Makefile` | `The-going` _arm64:dts:overlay sun50i-h5 add gpio regulator overclock_ |
|  📜  ✅  | `[patches.armbian/]` `Move-sun50i-h6-pwm-settings-to-its-own-overlay` | `(+25/-14)[1M, 1A]` | `sun50i-h6-pwm.dts`, `sun50i-h6-fixup.scr-cmd` | `afaulkner420` _Move sun50i-h6-pwm settings to its own overlay_ |
|  📜  ✅  | `[patches.armbian/]` `Compile-the-pwm-overlay` | `(+1/-0)[1M]` | `Makefile` | `afaulkner420` _Compile the pwm overlay_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-overlay-sun50i-h616-bigtreetech-cb1` | `(+381/-2)[1M, 11A]` | `sun50i-h616-fixup.scr-cmd`, `sun50i-h616-spi-spidev.dts`, `sun50i-h616-tft35_spi.dts`, `sun50i-h616-spidev0_0.dts`, `sun50i-h616-spidev1_0.dts`, `sun50i-h616-spidev1_1.dts`, `sun50i-h616-spidev1_2.dts`, `sun50i-h616-light.dts`, `sun50i-h616-mcp2515.dts`, `Makefile`, `sun50i-h616-ir.dts`, `sun50i-h616-ws2812.dts` | `Your Name` _cb1-overlay_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sunxi-h3-h5.dtsi-add-i2s0-i2s1-pins` | `(+10/-0)[1M]` | `sunxi-h3-h5.dtsi` | `The-going` _arm:dts:sunxi-h3-h5.dtsi add i2s0 i2s1 pins_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun5i-a13-olinuxino-micro-add-panel-lcd-olinuxino-4.3` | `(+60/-2)[1M]` | `sun5i-a13-olinuxino-micro.dts` | `Mitko Gamishev` _arm:dts:sun5i-a13-olinuxino-micro add panel lcd-olinuxino-4.3_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun5i-a13-olinuxino-Add-panel-lcd-olinuxino-4.3-needed-` | `(+44/-35)[1M]` | `sun5i-a13-olinuxino.dts` | `hehopmajieh` _arm:dts:sun5i-a13-olinuxino Add panel lcd-olinuxino-4.3 needed to fix overlay tests_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-olinuxino-micro-emmc-Add-vqmmc-node` | `(+1/-0)[1M]` | `sun7i-a20-olinuxino-micro-emmc.dts` | `hehopmajieh` _arm:dts:sun7i-a20-olinuxino-micro-emmc Add vqmmc node_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-olinuxino-lime2-enable-audio-codec` | `(+4/-0)[1M]` | `sun7i-a20-olinuxino-lime2.dts` | `Stefan Saraev` _arm:dts:sun7i-a20-olinuxino-lime2 enable audio codec_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-olinuxino-lime2-enable-ldo3-always-on` | `(+1/-1)[1M]` | `sun7i-a20-olinuxino-lime2.dts` | `hehopmajieh` _arm:dts:sun7i-a20-olinuxino-lime2 enable ldo3 always-on_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun7i-a20-olimex-som-204-evb-olinuxino-micro-decrease-d` | `(+3/-3)[3M]` | `sun7i-a20-olimex-som-evb.dts`, `sun7i-a20-olimex-som204-evb.dts`, `sun7i-a20-olinuxino-micro.dts` | `Stefan Saraev` _arm:dts:sun7i-a20: olimex-som(204)-evb,olinuxino-micro decrease dcdc2 min voltage_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-add-thermal-zones` | `(+55/-13)[1M]` | `sun8i-h3.dtsi` | `The-going` _arm:dts:sun8i-h3 add thermal zones_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-olinuxino-add-boards` | `(+540/-0)[1M, 5A]` | `sun50i-a64-olinuxino-1G.dts`, `sun50i-a64-olinuxino-1Ge4GW.dts`, `sun50i-a64-olinuxino-1Gs16M.dts`, `sun50i-a64-olinuxino-2Ge8G.dts`, `sun50i-a64-olinuxino-1Ge16GW.dts`, `Makefile` | `Mitko Gamishev` _arm64:dts:sun50i-a64-olinuxino add boards_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-olinuxino-emmc-enable-bluetooth` | `(+17/-0)[1M]` | `sun50i-a64-olinuxino-emmc.dts` | `Stefan Saraev` _arm64:dts: sun50i-a64-olinuxino-emmc: enable bluetooth_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-olinuxino-1Ge16GW-enable-bluetooth` | `(+21/-0)[1M]` | `sun50i-a64-olinuxino-1Ge16GW.dts` | `Stefan Saraev` _arm64:dts: sun50i-a64-olinuxino-1Ge16GW: enable bluetooth_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64.dtsi-adjust-thermal-trip-points` | `(+3/-3)[1M]` | `sun50i-a64.dtsi` | `Stefan Saraev` _arm64:dts:sun50i-a64.dtsi adjust thermal trip points_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-olinuxino-1Ge16GW-Disable-clock-phase-and-` | `(+2/-2)[1M]` | `sun50i-a64-olinuxino-1Ge16GW.dts` | `hehopmajieh` _arm64:dts:sun50i-a64-olinuxino-1Ge16GW Disable clock phase and hs just for test_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-a64-pinephone-wowlan` | `(+1/-0)[1M]` | `sun50i-a64-pinephone.dtsi` | `Paolo` _[ARCHEOLOGY] sunxi, media: Realtek rtl8723cs driver consolidation (step 2) (#4924)_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-orangepi-3-add-r_uart-aliase` | `(+1/-0)[1M]` | `sun50i-h6-orangepi-3.dts` | `The-going` _arm64:dts: sun50i-h6-orangepi-3 add r_uart aliase_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-add-cpu-opp-refs` | `(+9/-1)[8M]` | `sun50i-h5-nanopi-k1-plus.dts`, `sun50i-h5-bananapi-m2-plus.dts`, `sun50i-h5-nanopi-m1-plus2.dts`, `sun50i-h5-nanopi-neo-core2.dts`, `sun50i-h5-nanopi-neo-plus2.dts`, `sun50i-h5-nanopi-neo2-v1.1.dts`, `sun50i-h5-nanopi-neo2.dts`, `sun50i-h5-orangepi-prime.dts` | `The-going` _arm64:dts:sun50i-h5 add cpu opp refs_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-add-termal-zones` | `(+54/-12)[1M]` | `sun50i-h5.dtsi` | `The-going` _arm64:dts:sun50i-h5 add termal zones_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-orangepi-add-cpu-opp-refs` | `(+5/-0)[1M]` | `sun50i-h6-orangepi.dtsi` | `The-going` _arm64:dts: sun50i-h6-orangepi add cpu opp refs_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-orangepi-enable-higher-clock-regulator-max-` | `(+1/-1)[1M]` | `sun50i-h6-orangepi.dtsi` | `The-going` _arm64:dts: sun50i-h6-orangepi enable higher clock regulator-max-microvolt_ |
|  📜  ✅  | `[patches.armbian/]` `drv-staging-rtl8723bs-AP-bugfix` | `(+1/-1)[1M]` | `ioctl_cfg80211.c` | `The-going` _drv:staging:rtl8723bs: AP bugfix_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-orangepi-pc-plus-add-wifi_pwrseq` | `(+6/-0)[1M]` | `sun8i-h3-orangepi-pc-plus.dts` | `The-going` _arm:dts: sun8i-h3-orangepi-pc-plus add wifi_pwrseq_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-orangepi-prime-add-rtl8723cs` | `(+5/-0)[1M]` | `sun50i-h5-orangepi-prime.dts` | `The-going` _arm64:dts: sun50i-h5-orangepi-prime add rtl8723cs_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h2-plus-orangepi-zero-fix-xradio-interrupt` | `(+5/-0)[1M]` | `sun8i-h2-plus-orangepi-zero.dts` | `The-going` _arm:dts: sun8i-h2-plus-orangepi-zero fix xradio interrupt_ |
|  📜  ✅  | `[patches.armbian/]` `Fix-include-uapi-spi-spidev-module` | `(+1/-2)[1M]` | `spidev.c` | `The-going` _Fix include uapi spi spidev module_ |
|  📜  ✅  | `[patches.armbian/]` `fix-cpu-opp-table-sun8i-a83t` | `(+32/-20)[1M]` | `sun8i-a83t.dtsi` | `The-going` _fix: cpu opp table sun8i-a83t_ |
|  📜  ✅  | `[patches.armbian/]` `Add-dump_reg-and-sunxi-sysinfo-drivers` | `(+1449/-0)[2M, 8A]` | `dump_reg.c`, `dump_reg_misc.c`, `sunxi-sysinfo.c`, `dump_reg.h`, `Kconfig`, `Makefile` | `afaulkner420` _Add dump_reg and sunxi-sysinfo drivers_ |
|  📜  ✅  | `[patches.armbian/]` `Add-sunxi-addr-driver-Used-to-fix-uwe5622-bluetooth-MAC-address` | `(+549/-0)[2M, 4A]` | `sunxi-addr.c`, `sha256.c`, `Kconfig`, `Makefile` | `afaulkner420` _Add sunxi-addr driver - Used to fix uwe5622 bluetooth MAC addresses_ |
|  📜  ✅  | `[patches.armbian/]` `net-phy-Support-yt8531c` | `(+2152/-79)[2M, 2A]` | `motorcomm.c`, `yt8614-phy.h`, `motorcomm_phy.h`, `stmmac_main.c` | `afaulkner420` _net: phy: Support yt8531c_ |
|  📜  ✅  | `[patches.armbian/]` `nvmem-sunxi_sid-add-sunxi_get_soc_chipid-sunxi_get_serial` | `(+28/-0)[1M]` | `sunxi_sid.c` | `The-going` _nvmem: sunxi_sid: add sunxi_get_soc_chipid, sunxi_get_serial_ |
|  📜  ✅  | `[patches.armbian/]` `mmc-host-sunxi-mmc-Fix-H6-emmc` | `(+4/-1)[1M]` | `sunxi-mmc.c` | `Ukhellfire` _mmc/host/sunxi-mmc: Fix H6 emmc_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-sun50i-h6-Fix-H6-emmc` | `(+1/-2)[1M]` | `sun50i-h6.dtsi` | `Ukhellfire` _arm64: dts/allwinner/sun50i-h6: Fix H6 emmc_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-nanopi-r1s-h5-add-rtl8153-support` | `(+9/-1)[1M]` | `sun50i-h5-nanopi-r1s-h5.dts` | `The-going` _arm64: dts: sun50i-h5-nanopi-r1s-h5: add rtl8153 support_ |
|  📜  ✅  | `[patches.armbian/]` `net-usb-r8152-add-LED-configuration-from-OF` | `(+23/-0)[1M]` | `r8152.c` | `David Bauer` _net: usb: r8152: add LED configuration from OF_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h6-orangepi.dtsi-Rollback-r_rsb-to-r_i2c` | `(+3/-3)[1M]` | `sun50i-h6-orangepi.dtsi` | `The-going` _arm64: dts: sun50i-h6-orangepi.dtsi: Rollback r_rsb to r_i2c_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sunxi-h3-h5-add_tve` | `(+310/-14)[14M, 2A]` | `sunxi-h3-h5.dtsi`, `sun8i_mixer.c`, `sun4i_tv.c`, `sun8i-h3-tve.dts`, `sun50i-h5-tve.dts`, `sun8i-h3.dtsi`, `sun50i-h5.dtsi`, `ccu-sun8i-h3.c`, `README.sun8i-h3-overlays`, `README.sun50i-h5-overlays`, `sun8i_mixer.h`, `sun8i-h2-plus-orangepi-zero.dts`, `sun8i-h3-orangepi-pc.dts`, `Makefile` | `Radoslav` _[ARCHEOLOGY] h3-tve (arm-dts-sun8i-h3-orangepizero-add_tve.patch)_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-fix-thermal-read` | `(+31/-3)[1M]` | `sun8i_thermal.c` | `Radoslav` _[ARCHEOLOGY] h3-dth_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-bigtreetech-cb1` | `(+407/-0)[1M, 3A]` | `sun50i-h616-bigtreetech-cb1.dtsi`, `sun50i-h616-bigtreetech-cb1-emmc.dts`, `sun50i-h616-bigtreetech-cb1-sd.dts`, `Makefile` | `Your Name` _add bigtreetech-cb1 dts_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-nanopi-duo2-enable-powerbutton-and-ethernet` | `(+2/-1)[1M]` | `sun8i-h3-nanopi-duo2.dts` | `Gunjan Gupta` _ARM: dts: sun8i: nanopiduo2: Use key-0 as power button_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-nanopi-duo2-enable-powerbutton-and-ethernet` | `(+7/-0)[1M]` | `sun8i-h3-nanopi-duo2.dts` | `Gunjan Gupta` _ARM: dts: sun8i: nanopiduo2: enable ethernet_ |
|  📜  ✅  | `[patches.armbian/]` `arm-dts-sun8i-h3-reduce-opp-microvolt-to-prevent-not` | `(+4/-3)[1M]` | `sun8i-h3.dtsi` | `Gunjan Gupta` _arm: dts: sun8i: h3: reduce opp-microvolt to prevent not supported by regulator error_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-enable-power-button-for-orangepi-prime` | `(+2/-1)[1M]` | `sun50i-h5-orangepi-prime.dts` | `Gunjan Gupta` _arm64: dts: sun50i: h5: enable power button for orangepi prime_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h5-Add-missing-GPU-trip-point` | `(+9/-0)[1M]` | `sun50i-h5.dtsi` | `Ondrej Jirman` _arm64: dts: sun50i-h5: Add missing GPU trip point_ |
|  📜  ✅  | `[patches.armbian/]` `drivers-devfreq-sun8i-a33-mbus-disable-autorefresh` | `(+2/-2)[1M]` | `sun8i-a33-mbus.c` | `Gunjan Gupta` _drivers: devfreq: sun8i-a33-mbus: disable autorefresh_ |
|  📜  ✅  | `[patches.armbian/]` `clk-gate-add-support-for-regmap-based-gates` | `(+89/-7)[2M]` | `clk-gate.c`, `clk-provider.h` | `Andre Przywara` _clk: gate: add support for regmap based gates_ |
|  📜  ✅  | `[patches.armbian/]` `mfd-Add-support-for-X-Powers-AC200` | `(+204/-0)[2M, 1A]` | `ac200.c`, `Kconfig`, `Makefile` | `Jernej Skrabec` _mfd: Add support for X-Powers AC200_ |
|  📜  ✅  | `[patches.armbian/]` `mfd-Add-support-for-X-Powers-AC200-EPHY-syscon` | `(+311/-0)[2M, 1A]` | `ac200-ephy-ctl.c`, `Kconfig`, `Makefile` | `Andre Przywara` _mfd: Add support for X-Powers AC200 EPHY syscon_ |
|  📜  ✅  | `[patches.armbian/]` `net-phy-Add-support-for-AC200-EPHY` | `(+90/-0)[2M, 1A]` | `ac200-phy.c`, `Kconfig`, `Makefile` | `Jernej Skrabec` _net: phy: Add support for AC200 EPHY_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h6-Add-AC200-EPHY-nodes` | `(+73/-0)[1M]` | `sun50i-h6.dtsi` | `Jernej Skrabec` _arm64: dts: allwinner: h6: Add AC200 EPHY nodes_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h6-tanix-enable-Ethernet` | `(+38/-0)[1M]` | `sun50i-h6-tanix.dtsi` | `Jernej Skrabec` _arm64: dts: allwinner: h6: tanix: enable Ethernet_ |
|  📜  ✅  | `[patches.armbian/]` `ASoC-AC200-Initial-driver` | `(+786/-0)[2M, 1A]` | `ac200.c`, `Kconfig`, `Makefile` | `Jernej Skrabec` _ASoC: AC200: Initial driver_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h6-add-AC200-codec-nodes` | `(+42/-0)[1M]` | `sun50i-h6.dtsi` | `Jernej Skrabec` _arm64: dts: allwinner: h6: add AC200 codec nodes_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-allwinner-h6-enable-AC200-codec` | `(+64/-0)[3M]` | `sun50i-h6-orangepi-3.dts`, `sun50i-h6-pine-h64.dts`, `sun50i-h6-tanix-tx6-mini.dts` | `Jernej Skrabec` _arm64: dts: allwinner: h6: enable AC200 codec_ |
|  📜  ✅  | `[patches.armbian/]` `add-nodes-for-sunxi-info-addr-dump-reg` | `(+38/-0)[2M]` | `sun50i-h6.dtsi`, `sun50i-h616.dtsi` | `The-going` _add nodes for sunxi-info, sunxi-addr and sunxi-dump-reg_ |
|  📜  ✅  | `[patches.armbian/]` `add-initial-support-for-orangepi3-lts` | `(+400/-0)[1M, 1A]` | `sun50i-h6-orangepi-3-lts.dts`, `Makefile` | `The-going` _add initial support for orangepi3-lts_ |
|  📜  ✅  | `[patches.armbian/]` `drivers-input-axp20x-pek-allow-wakeup-after-shutdown` | `(+6/-0)[1M]` | `axp20x-pek.c` | `Samuel Holland` _Input: axp20x-pek - allow wakeup after shutdown_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-add-wifi-nodes-for-Inovato-Quadra` | `(+57/-0)[1M, 1A]` | `sun50i-h6-inovato-quadra.dts`, `Makefile` | `Gunjan Gupta` _Add wifi nodes for Inovato Quadra_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-h616-add-wifi-support-for-orange-pi-zero-2` | `(+38/-0)[1M]` | `sun50i-h616-orangepi-zero2.dts` | `Gunjan Gupta` _arm64: dts: h616: add wifi support for orange pi zero 2 and zero3_ |
|  📜  ✅  | `[patches.armbian/]` `drivers-hack-for-h616-hdmi-video-output` | `(+547/-50)[11M, 2A]` | `sun8i_mixer.c`, `ccu-sun8i-de33.c`, `sun8i_hdmi_phy.c`, `sun8i_csc.c`, `sun8i_mixer.h`, `sun8i_ui_layer.c`, `ccu-sun8i-de33.h`, `sun8i_vi_layer.c`, `Kconfig`, `sun4i_tcon.c`, `sun8i_vi_scaler.c`, `Makefile`, `sun4i_tcon.h` | `orangepi-xunlong` _drivers: hack for h616 hdmi video output_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-h616-add-hdmi-support-for-zero2` | `(+239/-0)[2M]` | `sun50i-h616.dtsi`, `sun50i-h616-orangepi-zero2.dts` | `Gunjan Gupta` _arm64: dts: h616: add hdmi support for zero2_ |
|  📜  ✅  | `[patches.armbian/]` `arm64-dts-sun50i-h616-Add-dma-node` | `(+16/-0)[1M]` | `sun50i-h616.dtsi` | `Gunjan Gupta` _arm64: dts: sun50i-h616: Add dma node_ |
| ✅  | `Add-RepkaPi3-Kernel-Support` | `(+1008/-0)[1M, 4A]` | `sun50i-h5-repka-pi3.dts`, `sun50i-h5-repka-3-1.4p.dtsi`, `axp22x.dtsi`, `sun50i-h5-cpu-opp-1.368ghz.dtsi`, `Makefile` | `John Doe` _Patching kernel sunxi64 files arch/arm64/boot/dts/allwinner/Makefile arch/arm64/boot/dts/allwinner/axp22x.dtsi arch/arm64/boot/dts/allwinner/sun50i-h5-cpu-opp-1.368ghz.dtsi arch/arm64/boot/dts/allwinner/sun50i-h5-repka-3-1.4p.dtsi arch/arm64/boot/dts/allwinner/sun50i-h5-repka-pi3.dts_ |
| ✅  | `Add-sun50i-h3-h5` | `(+986/-0)[1A]` | `sunxi-h3-h5.dtsi` | `John Doe` _Patching kernel sunxi64 files arch/arm64/boot/dts/allwinner/sunxi-h3-h5.dtsi_ |
| ✅  | `allwinner-add-support-for-Recore-dtbs` | `(+570/-0)[1M, 5A]` | `sun50i-a64-recore.dtsi`, `sun50i-a64-recore-a5.dts`, `sun50i-a64-recore-a7.dts`, `sun50i-a64-recore.dts`, `sun50i-a64-recore-a6.dts`, `Makefile` | `Elias Bakken` _[ARCHEOLOGY] Add support for Recore (#5351)_ |
| ✅  | `arm-patch-call-patch_unmap-after-flushing-dcache-and-icache` | `(+8/-1)[1M]` | `patch.c` | `The-going` _arm: patch: call 'patch_unmap' after flushing dcache and icache_ |
| ✅  | `sunxi-gpio-sysfs-build` | `(+1/-1)[1M]` | `Kconfig` | `schwar3kat` _fix-gpio-kconfig remove if EXPERT to allow normal build_ |


</p></details>
