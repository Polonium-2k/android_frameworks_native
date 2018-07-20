# android_frameworks_native

solves the error : 

    build/core/product_config.mk:243: *** _nic.PRODUCTS.[[device/motorola/lux/lineage.mk]]: "frameworks/native/build/phone-xxhdpi-2048-hwui-memory.mk" does not exist.  Stop.

Command to add the file : 

    wget -O frameworks/native/build/phone-xxhdpi-2048-hwui-memory.mk 'https://raw.githubusercontent.com/Polonium-2k/android_frameworks_native/master/build/phone-xxhdpi-2048-hwui-memory.mk'
