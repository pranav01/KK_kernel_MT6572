Explay Golf

export PATH=~/Your_Toolchain_PATH/
for example /alps/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.6/bin

Build Command:

cd KK_kernel_MT6572
./mk -o=TARGET_BUILD_VARIANT=user golf n k

Then, to create the boot.img:

./pack_bootimage.sh
