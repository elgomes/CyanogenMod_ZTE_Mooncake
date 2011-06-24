###############################################################################
#
#                 CyanogenMod - ZTE Racer (Mooncake Board)
#
###############################################################################


This is an attempt to add in CyanogenMod the support of ZTE Racer with
Mooncake board.

With this repository you can build sucessfully for ZTE Racer, but the screen
doesn't work.

The kernel placed in device/zte/mooncake is builded with TomGiordano Kernel
This is the link: https://github.com/TomGiordano/kernel_zte_blade

The recovery_kernel placed in device/zte/mooncake is the same of Blade
device of CyanogenMod repository.

Is "forked" of the ZTE Blade of CyanogenMod.

Help is welcome, because i don't have an good knowledge in AOSP and
CyanogenMod, so to fix things i spend an long time.

The repository is based in root directory of CyanogenMod. If you copy those
directory's of this repository to root directory of CyanogenMod is the
correct way.

To build in CyanogenMod, run this in root directory:

. build/envsetup.sh

brunch mooncake


###############################################################################
