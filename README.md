Copyright 2018 - The LineageOS Project

Device configuration for Motorola X4 (payton)
==================================

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core 2.2 GHz Cortex-A53
CHIPSET | Qualcomm SDM630 Snapdragon 630
GPU     | Adreno 508
Memory  | 3GB, 4GB or 6GB
Shipped Android Version | 7.1.1 (Nougat)
Storage | 32GB or 64GB
Battery | 3000 mAh
Dimensions | 148.4 x 73.4 x 8 mm
Display | 1080 x 1920 pixels, 5.2" LTPS IPS
Rear Camera  | 12 MP (f/2.0, 1.4µm, PDAF, dual pixel)
Front Camera | 8 MP (f/2.2, 1.12µm, no AF)

git clone https://github.com/munchycool/android_device_motorola_sdm660-common -b cr-6.1 device/motorola/sdm660-common

git clone https://github.com/munchycool/android_device_motorola_payton -b cr-6.1 device/motorola/payton

git clone https://github.com/munchycool/proprietary_vendor_motorola_sdm660-common -b lineage-15.1 vendor/motorola/sdm660-common

git clone https://github.com/munchycool/proprietary_vendor_motorola_payton -b lineage-15.1 vendor/motorola/payton

git clone https://github.com/munchycool/android_kernel_motorola_msm8998 -b lineage-15.1 kernel/motorola/msm8998

git clone https://github.com/LineageOS/android_external_bson -b lineage-15.1 external/bson

git clone https://github.com/LineageOS/android_packages_resources_devicesettings -b lineage-15.1 packages/resources/devicesettings

git clone https://github.com/munchycool/carbon_android_hardware_qcom_bootctrl -b cr-6.1 hardware/qcom/bootctrl

git clone https://github.com/LineageOS/android_external_json-c -b cr-6.1 external/json-c

cherry-pick or manually do this 

https://github.com/munchycool/carbon_android_build_make/commit/02f616ceaf700aa822b957c97ab0bf352ba8e08f
